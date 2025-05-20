# Function: <code>__skb_dequeue</code>

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
In kernel/audit.c (ffffffff81121b8a)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/xen-netfront.c (ffffffff815fb69c)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81704ecd)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff8170e146)
Location: include/linux/skbuff.h:1657
Inline: True
```
```
In net/core/dev.c (ffffffff8171994d)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_callback
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81725ac6)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
```
```
In net/core/netpoll.c (ffffffff81738a32)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/sched/sch_generic.c (ffffffff81740bdd)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_reset
```
```
In net/sched/sch_fifo.c (ffffffff81748fb1)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_queue_drop_head
```
```
In net/netlink/af_netlink.c (ffffffff8174a6ed)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_set_ring
```
```
In net/ipv4/ip_output.c (ffffffff8175f046)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff817664d4)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_prequeue_process
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8176b136)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
```
```
In net/ipv4/tcp_timer.c (ffffffff81779dfe)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177c927)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff8178887b)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/af_inet.c (ffffffff81794796)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff817aa128)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b5f9d)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/unix/garbage.c (ffffffff817c274e)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff817c7d7e)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff817fb002)
Location: include/linux/skbuff.h:1657
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In kernel/audit.c (ffffffff81129aca)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/xen-netfront.c (ffffffff8165b5c2)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8176ba9d)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81775866)
Location: include/linux/skbuff.h:1758
Inline: True
```
```
In net/core/dev.c (ffffffff81781e30)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_callback
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff817925bc)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff817a4d02)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/sched/sch_generic.c (ffffffff817ada0d)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff817b6040)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_output.c (ffffffff817cb2b6)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff817d4926)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_prequeue_process
```
```
In net/ipv4/tcp_input.c (ffffffff817d9ab9)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_timer.c (ffffffff817e7019)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea220)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff817f61cb)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/af_inet.c (ffffffff81802116)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81817613)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81822fbd)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/unix/garbage.c (ffffffff8182f77d)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81834ebe)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff8186a84f)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In kernel/audit.c (ffffffff811337e4)
Location: include/linux/skbuff.h:1773
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/xen-netfront.c (ffffffff816893e2)
Location: include/linux/skbuff.h:1773
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81798f2b)
Location: include/linux/skbuff.h:1773
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff817a2ae6)
Location: include/linux/skbuff.h:1773
Inline: True
```
```
In net/core/dev.c (ffffffff817af730)
Location: include/linux/skbuff.h:1773
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff817bfe8c)
Location: include/linux/skbuff.h:1773
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff817d3772)
Location: include/linux/skbuff.h:1773
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/ipv4/ip_output.c (ffffffff817faf16)
Location: include/linux/skbuff.h:1773
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81804666)
Location: include/linux/skbuff.h:1773
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_prequeue_process
```
```
In net/ipv4/tcp_timer.c (ffffffff8181774b)
Location: include/linux/skbuff.h:1773
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818a5d)
Location: include/linux/skbuff.h:1773
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff81824e4a)
Location: include/linux/skbuff.h:1773
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff818330a6)
Location: include/linux/skbuff.h:1773
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81848e83)
Location: include/linux/skbuff.h:1773
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81854903)
Location: include/linux/skbuff.h:1773
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/unix/garbage.c (ffffffff8186120e)
Location: include/linux/skbuff.h:1773
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff818669f4)
Location: include/linux/skbuff.h:1773
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff8189d69f)
Location: include/linux/skbuff.h:1773
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In kernel/audit.c (ffffffff81134cdd)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff81694ca9)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8169eb0f)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff817b7539)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff817c0c86)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff817ce015)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff817de3b4)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff817f2ac2)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff817f997b)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/ipv4/ip_output.c (ffffffff8181b306)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff818248ea)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_prequeue_process
```
```
In net/ipv4/tcp_timer.c (ffffffff81837b7e)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183924b)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff81845b2e)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff818549e6)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff8186c4a2)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff818783b2)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/unix/garbage.c (ffffffff8188594a)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff8188b11f)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff818c3c11)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In kernel/audit.c (ffffffff81141a2d)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In kernel/bpf/sockmap.c (ffffffff811b0b08)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_gc_work
```
```
In drivers/net/tun.c (ffffffff816ff53c)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/xen-netfront.c (ffffffff81709caf)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8182fb39)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff8183a6a6)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff8184ad15)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81858c16)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff8186e082)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff8187729b)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/ipv4/ip_output.c (ffffffff8189a236)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff818a67a8)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/udp.c (ffffffff818c556e)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff818d4886)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff818ecd81)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8ca4)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff818feb62)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/unix/garbage.c (ffffffff81906afa)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff8190c33f)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81946eaa)
Location: include/linux/skbuff.h:1848
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In kernel/audit.c (ffffffff811503b9)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In kernel/bpf/sockmap.c (ffffffff811cff58)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_gc_work
```
```
In drivers/net/tun.c (ffffffff8173ef0e)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/xen-netfront.c (ffffffff81748768)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8187a305)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81884de2)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff818950f5)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff818a405b)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff818bf054)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff818c89e2)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff818ccf34)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff818ee6f5)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff818fb884)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/udp.c (ffffffff8191d85e)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff8192aa42)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81942c76)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194f6cc)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819556d9)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff819584f3)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff8195daed)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff819637c7)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff8199f58e)
Location: include/linux/skbuff.h:1859
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffff8115d076)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff8176310d)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/xen-netfront.c (ffffffff8176c818)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8189af15)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff818a5852)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff818b5bc5)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff818c74c9)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff818e74e6)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff818e7e44)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff818f3902)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff818f8272)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff8191bea5)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff819297e4)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/udp.c (ffffffff8194c7de)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff81959f62)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81972d42)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81982d06)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a2e9)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff8198d0f3)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff8199262d)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81998787)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff819d60b5)
Location: include/linux/skbuff.h:1937
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffff81169796)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff817a0c79)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/xen-netfront.c (ffffffff817aa608)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff818e5296)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff818f0b72)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff818ff524)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81913b9f)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff81936e5b)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff819377a2)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff819527a0)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff819579ae)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff8197e1b5)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff8198c8ab)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/udp.c (ffffffff819b0f7e)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff819beba6)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff819dc5d5)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819eca23)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4559)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff819f8963)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff819fdc1f)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81a045d6)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81a4515a)
Location: include/linux/skbuff.h:2026
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffff81175636)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff817c5c49)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/xen-netfront.c (ffffffff817ce068)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81917426)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81922ac2)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81931884)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff8194620f)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff81969d2b)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff8196a662)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff819754a1)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81988af0)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff8198de4e)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff819b4b65)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff819c321b)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/udp.c (ffffffff819e7a8e)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff819f57d6)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81a135c5)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a23a3b)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b1f9)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f5c3)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff81a3480f)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b1c6)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81a7bd4a)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffff81187d16)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In fs/io_uring.c (ffffffff8137ff74)
Location: include/linux/skbuff.h:2063
Inline: True
```
```
In drivers/net/tun.c (ffffffff8188e5d9)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_receive
```
```
In drivers/net/xen-netfront.c (ffffffff8189a146)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_fill_frags
```
```
In net/core/skbuff.c (ffffffff819e9cb4)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff819f61f2)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81a0704f)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81a16658)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/skmsg.c (ffffffff81a3d83b)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff81a3ddc2)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81a49ced)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81a6079d)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81a658ad)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a9ed64)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81aae8b9)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/udp.c (ffffffff81ad3f90)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff81ae3b16)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81b02db2)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15989)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d879)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81b221d3)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81b2323f)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/garbage.c (ffffffff81b29633)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81b30785)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81b764b2)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
```
```
In net/mptcp/protocol.c (ffffffff81bab09b)
Location: include/linux/skbuff.h:2063
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
In kernel/audit.c (ffffffff8118508b)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In fs/io_uring.c (ffffffff8138ea94)
Location: include/linux/skbuff.h:2084
Inline: True
```
```
In drivers/net/tun.c (ffffffff8189cb69)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_receive
```
```
In drivers/net/xen-netfront.c (ffffffff818a929f)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_fill_frags
```
```
In net/core/skbuff.c (ffffffff819e9a54)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff819f5a32)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81a085ff)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81a166e3)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/skmsg.c (ffffffff81a4041b)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff81a40ae2)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81a4f58d)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81a6903d)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81a6d9c7)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81aa8ca4)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81ab8af9)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/udp.c (ffffffff81ae04d0)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff81af0a36)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81b11192)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b23df5)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c149)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30bd3)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81b31c2f)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/garbage.c (ffffffff81b37f63)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f3b5)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81b85272)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
```
```
In net/mptcp/protocol.c (ffffffff81bbb1d7)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clear_xmit
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
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
In kernel/audit.c (ffffffff81185f1b)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In fs/io_uring.c (ffffffff8139b88f)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - fs/io_uring.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff8187f784)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/xen-netfront.c (ffffffff8188c366)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff819cfb76)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff819dbbd2)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff819eed27)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff819fd2ef)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff81a25792)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81a34c66)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81a4c3fd)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81a5609f)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a93da5)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81aa3da9)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/udp.c (ffffffff81acc4f0)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff81adc1e6)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81b0045f)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11989)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19dac)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e903)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81b1f961)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/garbage.c (ffffffff81b25bfb)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d24e)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/mcast.c (ffffffff81b625b6)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff81b742a7)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/mptcp/protocol.c (ffffffff81baa817)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clear_xmit
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
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
In kernel/audit.c (ffffffff811ae30b)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In fs/io_uring.c (ffffffff813e48d4)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - fs/io_uring.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff819108f4)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/xen-netfront.c (ffffffff8191f7d9)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81a7feb6)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81a8bdb2)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81aa0096)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81aaf67b)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff81ada242)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81aea028)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81b048ad)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81b0ee58)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81b4f1e5)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81b5ffbe)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/udp.c (ffffffff81b8ad80)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff81b9b406)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81bc254f)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd5479)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde34c)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81be3443)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81be4601)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/garbage.c (ffffffff81beb315)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81bf3405)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/mcast.c (ffffffff81c2a046)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff81c3eb56)
Location: include/linux/skbuff.h:2129
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffff811e01f2)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In io_uring/io_uring.c (ffffffff816c8c55)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff81a66f79)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/xen-netfront.c (ffffffff81a748b5)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81bf4403)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81c01692)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81c15b42)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81c28c70)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81c5b792)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81c6c854)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81c8a16e)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81c95978)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81cdcb75)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81cee97a)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/udp.c (ffffffff81d1a2f0)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff81d2d422)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81d553af)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6bc7b)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81d7514a)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a672)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81d7ba6b)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/garbage.c (ffffffff81d834c9)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c01d)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/mcast.c (ffffffff81dc74b6)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff81ddd326)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/mptcp/protocol.c (ffffffff81e23a8b)
Location: include/linux/skbuff.h:2480
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
In kernel/audit.c (ffffffff81225f72)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In io_uring/rsrc.c (ffffffff817a0435)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff81bf25a3)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/xen-netfront.c (ffffffff81c08b15)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81da2253)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81db0a22)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81dc6f22)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81ddb910)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81e11ac2)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81e24446)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81e44d5e)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81e514e8)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81e9d5e5)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81eb1bea)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/udp.c (ffffffff81ee0f90)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_common
```
```
In net/ipv4/af_inet.c (ffffffff81ef5292)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81f1f6bf)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f36fbb)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41320)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81f47582)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81f48b1b)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/garbage.c (ffffffff81f50b1e)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81f59fdd)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/mcast.c (ffffffff81f98196)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff81fae7c0)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/mptcp/protocol.c (ffffffff81ffb1cb)
Location: include/linux/skbuff.h:2338
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
In kernel/audit.c (ffffffff8123c552)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In io_uring/rsrc.c (ffffffff817e143a)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_file_scm_put
```
```
In drivers/net/tun.c (ffffffff81c4b23d)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/xen-netfront.c (ffffffff81c6e27c)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81e10b23)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81e20ee2)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81e36712)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81e4c660)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81e853d2)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81e9998a)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81e9fb5e)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81eacd38)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81efbd35)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81f10298)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/udp.c (ffffffff81f408a0)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_common
```
```
In net/ipv4/af_inet.c (ffffffff81f54b72)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81f7f1b5)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f96a0b)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa0bb0)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa7052)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81fa898b)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/garbage.c (ffffffff81fb04c5)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81fb9c8e)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/mcast.c (ffffffff81ff8b86)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff8200fc40)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/mptcp/protocol.c (ffffffff8207754b)
Location: include/linux/skbuff.h:2374
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
In kernel/audit.c (ffffffff81256432)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In drivers/net/tun.c (ffffffff81cf8e31)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_rx_batched
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/xen-netfront.c (ffffffff81d22b64)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81ecd653)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_errqueue_purge
  - net/core/skbuff.c:skb_queue_purge_reason
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81ededb2)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81ef4a02)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81f0b374)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81f47a37)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81f5c0ba)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81f6218e)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81f6f7c8)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81fbfc75)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81fd4486)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/udp.c (ffffffff820064f0)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_common
```
```
In net/ipv4/af_inet.c (ffffffff8201ade2)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff82045835)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/xfrm/xfrm_policy.c (ffffffff82063e39)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8206df10)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff82074302)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff82075c7b)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/garbage.c (ffffffff8207daee)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff82087155)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/mcast.c (ffffffff820c67f6)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff820debd0)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/mptcp/protocol.c (ffffffff8214c57b)
Location: include/linux/skbuff.h:2381
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
In kernel/audit.c (ffff8000101ea448)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffff8000109e109c)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/xen-netfront.c (ffff800010a08864)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffff800010bb3e84)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffff800010bbd3c4)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffff800010bd01b8)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffff800010be6370)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/skmsg.c (ffff800010c0ff58)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffff800010c10818)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffff800010c1b2e0)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffff800010c309f0)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffff800010c39504)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffff800010c6531c)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffff800010c75f58)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/udp.c (ffff800010c9b9b4)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffff800010cab5ec)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffff800010ccde5c)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0b90)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffff800010ce9a88)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffff800010cee790)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffff800010cf4e78)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffff800010cfc324)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffff800010d458c0)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (c042a1dc)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (c0ac4eb8)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/skbuff.c (c0ccddf8)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (c0cd9850)
Location: include/linux/skbuff.h:2040
Inline: True
```
```
In net/core/dev.c (c0ce6454)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (c0cfe92c)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (c0d27d54)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (c0d28934)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (c0d3367c)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (c0d47ad4)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (c0d4b92c)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (c0d74f44)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (c0d84610)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/udp.c (c0da78b8)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (c0db844c)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (c0dd8c9c)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c0de9fd4)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (c0df1b84)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (c0df65d0)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (c0dfba58)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (c0e036f8)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (c0e48474)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (c00000000025b5e0)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (c000000000aa2210)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/skbuff.c (c000000000c86884)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (c000000000c96a64)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (c000000000cacf10)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (c000000000cc7914)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (c000000000cfc29c)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (c000000000cfd2b4)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (c000000000d0c0d0)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (c000000000d29abc)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (c000000000d321f0)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (c000000000d69848)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (c000000000d7d968)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/udp.c (c000000000dab094)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (c000000000dc1d80)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (c000000000dea5ec)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000e02f58)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (c000000000e0d3c4)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (c000000000e13430)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (c000000000e1aea8)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (c000000000e23dd4)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (c000000000e7b4c4)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffe00015eee0)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffe00062ab04)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/skbuff.c (ffffffe0007418a0)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffe00074bbce)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffe00075a22e)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffe00076ace6)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffe00078c46c)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffe00078cf9c)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffe000795b26)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffe0007a6bc4)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffe0007aa92c)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffe0007ccb6c)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffe0007d915e)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/udp.c (ffffffe0007f9cb4)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffe0008062a8)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffe000820034)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082f860)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffe000837904)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b912)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffe000840b10)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffe000846bf6)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffe000880bb6)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffff8116dc56)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff8178a729)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/xen-netfront.c (ffffffff81792c88)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff818b7426)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff818c2ac2)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff818d1884)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff818e61df)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff81909cfb)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff8190a632)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81915471)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81928960)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff8192dcbe)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff819549d5)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff8196308b)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/udp.c (ffffffff819878fe)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff81995576)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff819b2dc5)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c30cb)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819ca889)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff819cec53)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff819d3e9f)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff819da856)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81a1b3da)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffff81160df6)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff8176a079)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/skbuff.c (ffffffff81871376)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff8187ca02)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff8188b708)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff818a001f)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff818c3b0b)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff818c44e2)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff818cf221)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff818e2710)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff818e77be)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff8190e4c5)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff8191cb7b)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/udp.c (ffffffff819413be)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff8194f036)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff8196f3f5)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197febb)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81987679)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff8198ba13)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff81990c5f)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81997616)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff819d819a)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffff8116ba26)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff817baac9)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/xen-netfront.c (ffffffff817c2ee8)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81908426)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81913ac2)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81922884)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff8193720f)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff8195ad2b)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff8195b662)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff819664a1)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81979af0)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff8197ee4e)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff819bf1a5)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff819cd85b)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/udp.c (ffffffff819f20ce)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff819ffe16)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81a1d665)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2db4b)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35309)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81a396d3)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff81a3e91f)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81a452d6)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81a85e5a)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffff811791e5)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff817d2f1e)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/xen-netfront.c (ffffffff817dd1a8)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81929406)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81934c52)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81943a54)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff819589ea)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff8197cf4b)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff8197d882)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81988731)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff8199c020)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff819a13d1)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff819c8b25)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff819d73eb)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/udp.c (ffffffff819f924e)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff81a09f46)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81a28827)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a39307)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a40c29)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81a45101)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff81a4a28c)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81a50fa6)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81a9297c)
Location: include/linux/skbuff.h:2040
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
</details>
</li>
</ul>

## Differences

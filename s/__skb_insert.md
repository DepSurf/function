# Function: <code>__skb_insert</code>

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
In drivers/net/ppp/ppp_generic.c (ffffffff815f6fa4)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff815fb655)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81702f92)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81704fb3)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_insert
```
```
In net/core/dev.c (ffffffff8171949f)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81724cb4)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff8173806b)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/sched/sch_generic.c (ffffffff8174133a)
Location: include/linux/skbuff.h:1482
Inline: True
```
```
In net/sched/sch_fifo.c (ffffffff81749114)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
```
```
In net/netlink/af_netlink.c (ffffffff8174b44d)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_sendskb
```
```
In net/ipv4/ip_output.c (ffffffff8175dd9d)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81765d9f)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff8176ccfe)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8177448e)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177d152)
Location: include/linux/skbuff.h:1482
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81782b45)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/udp.c (ffffffff81788995)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b38dd)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (ffffffff817c04d1)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff817c2065)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff817c66e4)
Location: include/linux/skbuff.h:1482
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81806cc8)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/ppp/ppp_generic.c (ffffffff8165711d)
Location: include/linux/skbuff.h:1583
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff8165bafe)
Location: include/linux/skbuff.h:1583
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff8176844a)
Location: include/linux/skbuff.h:1583
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8176bce9)
Location: include/linux/skbuff.h:1583
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_insert
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
```
```
In net/core/dev.c (ffffffff81781988)
Location: include/linux/skbuff.h:1583
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff8178e783)
Location: include/linux/skbuff.h:1583
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff817a4354)
Location: include/linux/skbuff.h:1583
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/sched/sch_generic.c (ffffffff817ae136)
Location: include/linux/skbuff.h:1583
Inline: True
```
```
In net/sched/sch_fifo.c (ffffffff817b60e8)
Location: include/linux/skbuff.h:1583
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817cb0f0)
Location: include/linux/skbuff.h:1583
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff817d221f)
Location: include/linux/skbuff.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff817da5fe)
Location: include/linux/skbuff.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff817e133e)
Location: include/linux/skbuff.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea7f0)
Location: include/linux/skbuff.h:1583
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efcec)
Location: include/linux/skbuff.h:1583
Inline: True
```
```
In net/ipv4/udp.c (ffffffff817f62e5)
Location: include/linux/skbuff.h:1583
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
```
```
In net/xfrm/xfrm_policy.c (ffffffff818210ed)
Location: include/linux/skbuff.h:1583
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (ffffffff8182d077)
Location: include/linux/skbuff.h:1583
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff8182f075)
Location: include/linux/skbuff.h:1583
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff818337c8)
Location: include/linux/skbuff.h:1583
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81877795)
Location: include/linux/skbuff.h:1583
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/ppp/ppp_generic.c (ffffffff81684dfd)
Location: include/linux/skbuff.h:1598
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff816898d6)
Location: include/linux/skbuff.h:1598
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff8179548f)
Location: include/linux/skbuff.h:1598
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81798db9)
Location: include/linux/skbuff.h:1598
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_insert
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
```
```
In net/core/dev.c (ffffffff817af298)
Location: include/linux/skbuff.h:1598
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff817bc053)
Location: include/linux/skbuff.h:1598
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff817d2dc4)
Location: include/linux/skbuff.h:1598
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/ipv4/ip_output.c (ffffffff817fad45)
Location: include/linux/skbuff.h:1598
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81801ffc)
Location: include/linux/skbuff.h:1598
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81808f94)
Location: include/linux/skbuff.h:1598
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff8181180e)
Location: include/linux/skbuff.h:1598
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181ad90)
Location: include/linux/skbuff.h:1598
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818206fc)
Location: include/linux/skbuff.h:1598
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81824d8d)
Location: include/linux/skbuff.h:1598
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff818528fd)
Location: include/linux/skbuff.h:1598
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (ffffffff8185eb57)
Location: include/linux/skbuff.h:1598
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81860af5)
Location: include/linux/skbuff.h:1598
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff8186525e)
Location: include/linux/skbuff.h:1598
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818aafa5)
Location: include/linux/skbuff.h:1598
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff81695014)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8169a229)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff8169f055)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff817b3a4b)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff817b7369)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_insert
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
```
```
In net/core/dev.c (ffffffff817cdba9)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff817da725)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff817f21d4)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/gro_cells.c (ffffffff817f990a)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_output.c (ffffffff8181b1b6)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8182212d)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81829254)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff81831a7e)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183b5b0)
Location: include/linux/skbuff.h:1591
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840c0c)
Location: include/linux/skbuff.h:1591
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81848241)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81875a25)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (ffffffff8188287e)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff8188525d)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff818883ef)
Location: include/linux/skbuff.h:1591
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d4298)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff816ff0f0)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817049d9)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff8170a1ec)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff8182d0e0)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8182f969)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_insert
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff818476a9)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81854ec5)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff8186d6e4)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/gro_cells.c (ffffffff8187722a)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_output.c (ffffffff8189a0e6)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818a119d)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff818ae28e)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff818b4ae7)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c037f)
Location: include/linux/skbuff.h:1673
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c7c92)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f6116)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff818feec6)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffff81903924)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81906410)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff8190a99d)
Location: include/linux/skbuff.h:1673
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81958ceb)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff8173f042)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8174311d)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81748fc4)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81876ec6)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81879e89)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_insert
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81891ead)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff818a187e)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff818be914)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/gro_cells.c (ffffffff818c895a)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff818ccea9)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffffffff818ee53d)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818f5cea)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff8190393d)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff8190a116)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81915ecd)
Location: include/linux/skbuff.h:1684
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8191df1a)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194c2f5)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff8195597c)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffff8195ba31)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff8195d4a4)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81961de4)
Location: include/linux/skbuff.h:1684
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819b29ac)
Location: include/linux/skbuff.h:1684
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff81762aa6)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81767957)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff8176d05f)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81897666)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8189aa99)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff818b280d)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff818c47be)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff818e7744)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/gro_cells.c (ffffffff818f3880)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff818f81ea)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffffffff8191bd01)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81923947)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81931afa)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff819383be)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81944674)
Location: include/linux/skbuff.h:1762
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194cb6a)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197f582)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a45c)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffff81990252)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81991fe4)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81996892)
Location: include/linux/skbuff.h:1762
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e9919)
Location: include/linux/skbuff.h:1762
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff817a090e)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a516a)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff817aae3c)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff818e1aa3)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818e50bf)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff818fefb9)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff819105ef)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff819370cc)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/gro_cells.c (ffffffff81952725)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81957a32)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffffffff8197dff2)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81986366)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819951f8)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff8199b1e3)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a8c64)
Location: include/linux/skbuff.h:1852
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b1328)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e9252)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff819f47b0)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffff819fb93f)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff819fd7ff)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a02dce)
Location: include/linux/skbuff.h:1852
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a57e89)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff817c58dc)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c926a)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff817ce87f)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81913c93)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8191724f)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81931329)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81942c5c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff81969f8c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff819747f7)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81988a75)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff8198ded2)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffffffff819b4a08)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819bcaf6)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819cbd48)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff819d1c09)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819df904)
Location: include/linux/skbuff.h:1862
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e8054)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a20282)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b460)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffff81a325cf)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81a343ef)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a399a3)
Location: include/linux/skbuff.h:1862
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a90478)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In fs/io_uring.c (ffffffff81380551)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
```
```
In drivers/net/tun.c (ffffffff8188dd1f)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8189377f)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
```
```
In drivers/net/xen-netfront.c (ffffffff8189a2d6)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
```
```
In net/core/sock.c (ffffffff819e5da5)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb758)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81a06ae5)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81a12f24)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff81a3da8c)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff81a49988)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81a606e9)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81a65b94)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:try_bulk_dequeue_skb_slow
```
```
In net/ipv4/ip_output.c (ffffffff81a9eb5f)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aa7a46)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81ab1fc4)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81abeb16)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81accda6)
Location: include/linux/skbuff.h:1885
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad5f97)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11ae6)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d933)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/xfrm/espintcp.c (ffffffff81b223bc)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_queue_out
```
```
In net/unix/af_unix.c (ffffffff81b2712d)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81b2920a)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f235)
Location: include/linux/skbuff.h:1885
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b8ba47)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bab6a2)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In fs/io_uring.c (ffffffff8138ee21)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
```
```
In drivers/net/tun.c (ffffffff8189c134)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a1c0f)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
```
```
In drivers/net/xen-netfront.c (ffffffff818a945b)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
```
```
In net/core/sock.c (ffffffff819e5878)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb478)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81a080b5)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81a1328b)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff81a4071c)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff81a4f15d)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81a68f78)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81a6dcb4)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:try_bulk_dequeue_skb_slow
```
```
In net/ipv4/ip_output.c (ffffffff81aa8aa3)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ab20c6)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81abcf88)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81aca476)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8da6)
Location: include/linux/skbuff.h:1906
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ae2577)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1f276)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c203)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/xfrm/espintcp.c (ffffffff81b30dbc)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_queue_out
```
```
In net/unix/af_unix.c (ffffffff81b35a2f)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81b37b3a)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81b3dc85)
Location: include/linux/skbuff.h:1906
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b9aeb6)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bbb864)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In fs/io_uring.c (ffffffff8139bcba)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_rsrc_file_put
  - fs/io_uring.c:io_rsrc_file_put
  - fs/io_uring.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff8187e69b)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818840d8)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
```
```
In drivers/net/xen-netfront.c (ffffffff8188c82c)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
```
```
In net/core/sock.c (ffffffff819cb988)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819d1988)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/dev.c (ffffffff819ee795)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff819fa82a)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff81a253cc)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff81a34183)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81a4c338)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81a5651d)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a93bc0)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81a9d356)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81aa7dd4)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ab52f0)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3e15)
Location: include/linux/skbuff.h:1922
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81acd497)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0cef6)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19e63)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/xfrm/espintcp.c (ffffffff81b1eaec)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_queue_out
```
```
In net/unix/af_unix.c (ffffffff81b23617)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81b257d8)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b140)
Location: include/linux/skbuff.h:1922
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81b5ed1b)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff81b8a8a8)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81baf78b)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In fs/io_uring.c (ffffffff813e73b1)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
  - fs/io_uring.c:io_rsrc_file_put
  - fs/io_uring.c:io_rsrc_file_put
  - fs/io_uring.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff8190feb0)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81915a98)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
```
```
In drivers/net/xen-netfront.c (ffffffff8191fd0a)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
```
```
In net/core/sock.c (ffffffff81a7b03e)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81a8157c)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:msg_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81a9fa45)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81aad76f)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff81ada0ec)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff81ae9c83)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81b047e8)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81b0f2ae)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81b4f000)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81b59226)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81b641c4)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81b722e0)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b824a5)
Location: include/linux/skbuff.h:1951
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b8be57)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd00e6)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde483)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/xfrm/espintcp.c (ffffffff81be373c)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_queue_out
```
```
In net/unix/af_unix.c (ffffffff81be7aa7)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81beaee5)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81bf125b)
Location: include/linux/skbuff.h:1951
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81c264bb)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff81c569c5)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81c77d94)
Location: include/linux/skbuff.h:1951
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In io_uring/io_uring.c (ffffffff816c8c0d)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_rsrc_file_put
  - io_uring/io_uring.c:io_rsrc_file_put
  - io_uring/io_uring.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff81a63b90)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6bc07)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81a74e1f)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
```
```
In net/core/sock.c (ffffffff81bee660)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81bf5209)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81c11146)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81c22be3)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81c5b61b)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff81c6c4e3)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81c8a081)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81c96499)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81cdc960)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ce97d0)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81cf3060)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81d019f6)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d129a5)
Location: include/linux/skbuff.h:2302
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d18b05)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6630e)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81d7529d)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/xfrm/espintcp.c (ffffffff81d7aa5c)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_queue_out
```
```
In net/unix/af_unix.c (ffffffff81d809ee)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81d83135)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81d89a65)
Location: include/linux/skbuff.h:2302
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81dc4150)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff81df5d79)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81e1ce09)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In io_uring/rsrc.c (ffffffff817a03ed)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_file_put
  - io_uring/rsrc.c:io_rsrc_file_put
  - io_uring/rsrc.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff81bf2d70)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfeb27)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81c090a9)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
```
```
In net/core/sock.c (ffffffff81d9e120)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81da3729)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81dc0db6)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81dd81e2)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81e1192b)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff81e23ee3)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81e44c61)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81e52089)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81e9d3c0)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ead510)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81eb7690)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ec6b66)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed87e5)
Location: include/linux/skbuff.h:2160
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee19c8)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f3109e)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81f417b7)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue_net
```
```
In net/xfrm/espintcp.c (ffffffff81f479ec)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_queue_out
```
```
In net/unix/af_unix.c (ffffffff81f4e54e)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81f507a5)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81f5791c)
Location: include/linux/skbuff.h:2160
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81f942b0)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff81fca304)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81ff4339)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/fastopen.c (ffffffff8200ef9a)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
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
In io_uring/rsrc.c (ffffffff817e13f2)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_file_scm_put
  - io_uring/rsrc.c:io_rsrc_file_scm_put
  - io_uring/rsrc.c:io_rsrc_file_scm_put
```
```
In drivers/net/tun.c (ffffffff81c49f4f)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c64187)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81c6e851)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
```
```
In net/core/sock.c (ffffffff81e0c995)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81e1231e)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81e309c8)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81e494ff)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81e8523b)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff81e99423)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81e9fa61)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81ead8f9)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81efa93f)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81f0bc20)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81f15d6f)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81f2530f)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f378f5)
Location: include/linux/skbuff.h:2196
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f413c9)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f9184d)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1057)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue_net
```
```
In net/xfrm/espintcp.c (ffffffff81fa749c)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_queue_out
```
```
In net/unix/af_unix.c (ffffffff81faec7a)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81fb0115)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81fb73f1)
Location: include/linux/skbuff.h:2196
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81ff4c30)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff8202b108)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff82070b49)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/fastopen.c (ffffffff8208bb91)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
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
In drivers/net/tun.c (ffffffff81cff8df)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_rx_batched
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1aba7)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81d230fc)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
```
```
In net/core/sock.c (ffffffff81ec930d)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81ecf4de)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:skb_errqueue_purge
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81eecf4e)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81f081ef)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81f4722b)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff81f5bb12)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81f622d1)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81f70399)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81fbe87d)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81fcfcd0)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81fda145)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9bc8)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffd9cf)
Location: include/linux/skbuff.h:2203
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82007019)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205f5ad)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff8206e377)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue_net
```
```
In net/xfrm/espintcp.c (ffffffff8207474c)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_queue_out
```
```
In net/unix/af_unix.c (ffffffff8207c19c)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff8207d775)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff82084a8b)
Location: include/linux/skbuff.h:2203
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff820c2800)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff820fac0f)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff82144d59)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/fastopen.c (ffffffff82161991)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
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
In drivers/net/tun.c (ffff8000109e0e10)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a036c0)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffff800010a08f54)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffff800010bad09c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffff800010bb398c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffff800010bcfac4)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffff800010be3248)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffff800010c109d8)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffff800010c1b988)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffff800010c30c18)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffff800010c3956c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffff800010c65168)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffff800010c6ed40)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffff800010c7e994)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffff800010c847d0)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93494)
Location: include/linux/skbuff.h:1862
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9c588)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdc00c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffff800010cea00c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffff800010cf3460)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffff800010cf497c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffff800010cf98e4)
Location: include/linux/skbuff.h:1862
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d5dc78)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (c0ac51c0)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad0d30)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_find_ts
```
```
In drivers/net/ppp/ppp_generic.c (c0ade588)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/core/sock.c (c0cca3f0)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c0ccdc4c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (c0ce4228)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (c0cfbc78)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (c0d28060)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (c0d327d4)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (c0d47a2c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (c0d4b9b0)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (c0d74d40)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (c0d7d860)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (c0d8d9ac)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (c0d93ad0)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (c0da1c9c)
Location: include/linux/skbuff.h:1862
Inline: True
```
```
In net/ipv4/udp.c (c0da7728)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (c0de582c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (c0df1ea8)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (c0df8ff4)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (c0dfb600)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (c0e01134)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
```
```
In net/packet/af_packet.c (c0e5c7cc)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (c000000000aa1e44)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa9870)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/core/sock.c (c000000000c824b4)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c000000000c8647c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (c000000000cac680)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (c000000000cc4d28)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (c000000000cfc6e4)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (c000000000d0ac20)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (c000000000d2999c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (c000000000d32274)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (c000000000d69520)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (c000000000d74e98)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (c000000000d88d50)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (c000000000d90508)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (c000000000da36f4)
Location: include/linux/skbuff.h:1862
Inline: True
```
```
In net/ipv4/udp.c (c000000000daea68)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (c000000000dfe004)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (c000000000e0d864)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (c000000000e16810)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (c000000000e1a8e4)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (c000000000e216d4)
Location: include/linux/skbuff.h:1862
Inline: True
```
```
In net/packet/af_packet.c (c000000000e968a0)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffe00062a7a6)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062da68)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/core/sock.c (ffffffe00073f072)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffe0007416bc)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffe000759c80)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffe0007693f8)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffe00078c74e)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffe000794d10)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffe0007a6b38)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffe0007aa9c6)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffffffe0007cc9e0)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffe0007d3af6)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffe0007e0c7a)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffe0007e61e8)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f299e)
Location: include/linux/skbuff.h:1862
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007fa5da)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082b564)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffe000837bd6)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffe00083e532)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffe000840708)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffe0008455ec)
Location: include/linux/skbuff.h:1862
Inline: True
```
```
In net/packet/af_packet.c (ffffffe000893a0e)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff8178a3bc)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178dd4a)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff8179349f)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff818b3c93)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818b724f)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff818d1329)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff818e2c2c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff81909f5c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff819147c7)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff819288e5)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff8192dd42)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffffffff81954878)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8195c966)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff8196bbb8)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff81971a79)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197f774)
Location: include/linux/skbuff.h:1862
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81987ec4)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bf912)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff819caaf0)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffff819d1c5f)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff819d3a7f)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff819d9033)
Location: include/linux/skbuff.h:1862
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2fb08)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff81769d0c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81776b1a)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/core/sock.c (ffffffff8186dbe3)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8187119f)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff8188b1c5)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff8189ca6c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff818c3e0c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff818ce587)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff818e2695)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff818e7842)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffffffff8190e368)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81916456)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819256a8)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff8192b549)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81939234)
Location: include/linux/skbuff.h:1862
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81941984)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c702)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff819878e0)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffff8198ea1f)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff8199083f)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81995df3)
Location: include/linux/skbuff.h:1862
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819eccf8)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff817ba75c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817be0ea)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff817c36ff)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81904c93)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8190824f)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81922329)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81933c5c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff8195af8c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff819657f7)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81979a75)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff8197eed2)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffffffff819bf048)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819c7136)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819d6388)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff819dc249)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e9f44)
Location: include/linux/skbuff.h:1862
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f2694)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2a392)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35570)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffff81a3c6df)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81a3e4ff)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a43ab3)
Location: include/linux/skbuff.h:1862
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a9b6b8)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff817d2bf0)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d891a)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff817dd9bd)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81925d33)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8192928f)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81943374)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff8195405c)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff8197d1ac)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff81987a37)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff8199bf89)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff819a1452)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffffffff819c89cb)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819d0c86)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819dffa8)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff819e5ec9)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f3d74)
Location: include/linux/skbuff.h:1862
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fc4e2)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a35922)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81a40ed0)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffff81a47384)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81a49f5f)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a4f753)
Location: include/linux/skbuff.h:1862
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa5eab)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
</details>
</li>
</ul>

## Differences

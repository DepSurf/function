# Function: <code>__skb_queue_tail</code>

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
In drivers/net/xen-netfront.c (ffffffff815fb651)
Location: include/linux/skbuff.h:1625
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81702f87)
Location: include/linux/skbuff.h:1625
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81705000)
Location: include/linux/skbuff.h:1625
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_tail
```
```
In net/core/dev.c (ffffffff8171948b)
Location: include/linux/skbuff.h:1625
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81724ca9)
Location: include/linux/skbuff.h:1625
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff81738064)
Location: include/linux/skbuff.h:1625
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/sched/sch_generic.c (ffffffff81741336)
Location: include/linux/skbuff.h:1625
Inline: True
```
```
In net/sched/sch_fifo.c (ffffffff81749103)
Location: include/linux/skbuff.h:1625
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
```
```
In net/netlink/af_netlink.c (ffffffff8174b434)
Location: include/linux/skbuff.h:1625
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_sendskb
```
```
In net/ipv4/ip_output.c (ffffffff8175dd77)
Location: include/linux/skbuff.h:1625
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81765d95)
Location: include/linux/skbuff.h:1625
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff8176ccee)
Location: include/linux/skbuff.h:1625
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81774484)
Location: include/linux/skbuff.h:1625
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177d144)
Location: include/linux/skbuff.h:1625
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81782b34)
Location: include/linux/skbuff.h:1625
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/udp.c (ffffffff81788991)
Location: include/linux/skbuff.h:1625
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b38c5)
Location: include/linux/skbuff.h:1625
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (ffffffff817c04ca)
Location: include/linux/skbuff.h:1625
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff817c2061)
Location: include/linux/skbuff.h:1625
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff817c66ac)
Location: include/linux/skbuff.h:1625
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81806cb2)
Location: include/linux/skbuff.h:1625
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
In drivers/net/xen-netfront.c (ffffffff8165b578)
Location: include/linux/skbuff.h:1726
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81768443)
Location: include/linux/skbuff.h:1726
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8176bbd0)
Location: include/linux/skbuff.h:1726
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_tail
```
```
In net/core/dev.c (ffffffff81781974)
Location: include/linux/skbuff.h:1726
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff8178e778)
Location: include/linux/skbuff.h:1726
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff817a434d)
Location: include/linux/skbuff.h:1726
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/sched/sch_generic.c (ffffffff817ae132)
Location: include/linux/skbuff.h:1726
Inline: True
```
```
In net/sched/sch_fifo.c (ffffffff817b60d7)
Location: include/linux/skbuff.h:1726
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817cb0e9)
Location: include/linux/skbuff.h:1726
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff817d2215)
Location: include/linux/skbuff.h:1726
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff817df1c6)
Location: include/linux/skbuff.h:1726
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff817e1334)
Location: include/linux/skbuff.h:1726
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea7e2)
Location: include/linux/skbuff.h:1726
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efce1)
Location: include/linux/skbuff.h:1726
Inline: True
```
```
In net/ipv4/udp.c (ffffffff817f62e1)
Location: include/linux/skbuff.h:1726
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
```
```
In net/xfrm/xfrm_policy.c (ffffffff818210d5)
Location: include/linux/skbuff.h:1726
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (ffffffff8182d070)
Location: include/linux/skbuff.h:1726
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff8182f071)
Location: include/linux/skbuff.h:1726
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81833790)
Location: include/linux/skbuff.h:1726
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8187777d)
Location: include/linux/skbuff.h:1726
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
In drivers/net/xen-netfront.c (ffffffff81689398)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81795485)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81798ca0)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_tail
```
```
In net/core/dev.c (ffffffff817af284)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff817bc048)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff817d2dbd)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/ipv4/ip_output.c (ffffffff817fad3e)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81801ff2)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81809140)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff81811804)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181ad82)
Location: include/linux/skbuff.h:1741
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818206f1)
Location: include/linux/skbuff.h:1741
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81824d78)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff818528e5)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (ffffffff8185eb50)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81860af1)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81865226)
Location: include/linux/skbuff.h:1741
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818aaf8d)
Location: include/linux/skbuff.h:1741
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
In drivers/net/tun.c (ffffffff8169500a)
Location: include/linux/skbuff.h:1734
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8169eabe)
Location: include/linux/skbuff.h:1734
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff817b3a41)
Location: include/linux/skbuff.h:1734
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff817b7250)
Location: include/linux/skbuff.h:1734
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_tail
```
```
In net/core/dev.c (ffffffff817cdb94)
Location: include/linux/skbuff.h:1734
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff817da71a)
Location: include/linux/skbuff.h:1734
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff817f21c4)
Location: include/linux/skbuff.h:1734
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/gro_cells.c (ffffffff817f9906)
Location: include/linux/skbuff.h:1734
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_output.c (ffffffff8181b1af)
Location: include/linux/skbuff.h:1734
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81822123)
Location: include/linux/skbuff.h:1734
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff818293f1)
Location: include/linux/skbuff.h:1734
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff81831a74)
Location: include/linux/skbuff.h:1734
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183b5a2)
Location: include/linux/skbuff.h:1734
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840c01)
Location: include/linux/skbuff.h:1734
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8184822c)
Location: include/linux/skbuff.h:1734
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81875a0d)
Location: include/linux/skbuff.h:1734
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (ffffffff81882877)
Location: include/linux/skbuff.h:1734
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81885259)
Location: include/linux/skbuff.h:1734
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff818883e4)
Location: include/linux/skbuff.h:1734
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d4282)
Location: include/linux/skbuff.h:1734
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
In drivers/net/tun.c (ffffffff816ff0e2)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81709c5e)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff8182d0d6)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8182f850)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81847694)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81854eba)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff8186d6d4)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/gro_cells.c (ffffffff81877226)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_output.c (ffffffff8189a0df)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818a1193)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff818ae3f1)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff818b4ae0)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c0374)
Location: include/linux/skbuff.h:1816
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c7c7c)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f60fe)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff818feebb)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffff8190391d)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff8190640c)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff8190a996)
Location: include/linux/skbuff.h:1816
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81958cd5)
Location: include/linux/skbuff.h:1816
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
In drivers/net/tun.c (ffffffff8173f034)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81748648)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81876ebf)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81879d70)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81891ea6)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff818a1876)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff818be90d)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/gro_cells.c (ffffffff818c8956)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff818ccea2)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffffffff818ee536)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818f5ce3)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81903aa0)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff8190a10f)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81915ec5)
Location: include/linux/skbuff.h:1827
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8191df13)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194c2ee)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81955978)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffff8195ba2a)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff8195d4a0)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81961dd9)
Location: include/linux/skbuff.h:1827
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819b29ac)
Location: include/linux/skbuff.h:1827
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
In drivers/net/tun.c (ffffffff81762a9b)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8176c6f8)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff8189765f)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8189a9e0)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff818b2806)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff818c47b6)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff818e773d)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/gro_cells.c (ffffffff818f387c)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff818f81e3)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffffffff8191bcfa)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81923940)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81931c72)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff819383b7)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8194466c)
Location: include/linux/skbuff.h:1905
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194cb63)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197f57b)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a458)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffff8199024b)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81991fe0)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81996873)
Location: include/linux/skbuff.h:1905
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e9919)
Location: include/linux/skbuff.h:1905
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
In drivers/net/tun.c (ffffffff817a0903)
Location: include/linux/skbuff.h:1994
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817aa509)
Location: include/linux/skbuff.h:1994
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff818e1a9b)
Location: include/linux/skbuff.h:1994
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818e5006)
Location: include/linux/skbuff.h:1994
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff818fefb2)
Location: include/linux/skbuff.h:1994
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff819105e8)
Location: include/linux/skbuff.h:1994
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff819370c5)
Location: include/linux/skbuff.h:1994
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/gro_cells.c (ffffffff81952721)
Location: include/linux/skbuff.h:1994
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81957a2b)
Location: include/linux/skbuff.h:1994
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffffffff8197dfeb)
Location: include/linux/skbuff.h:1994
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8198635f)
Location: include/linux/skbuff.h:1994
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81995368)
Location: include/linux/skbuff.h:1994
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff8199b1dc)
Location: include/linux/skbuff.h:1994
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a8c5c)
Location: include/linux/skbuff.h:1994
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b1320)
Location: include/linux/skbuff.h:1994
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e924b)
Location: include/linux/skbuff.h:1994
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff819f47ac)
Location: include/linux/skbuff.h:1994
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffff819fb938)
Location: include/linux/skbuff.h:1994
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff819fd7fb)
Location: include/linux/skbuff.h:1994
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a02daf)
Location: include/linux/skbuff.h:1994
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a57e82)
Location: include/linux/skbuff.h:1994
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
In drivers/net/tun.c (ffffffff817c58d1)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817cdf69)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81913c8b)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81917196)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81931322)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81942c55)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff81969f85)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff819747f3)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81988a71)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff8198decb)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffffffff819b4a01)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819bcaef)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819cbeb8)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff819d1c02)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819df8fc)
Location: include/linux/skbuff.h:2008
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e804c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2027b)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b45c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffff81a325c8)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81a343eb)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a39984)
Location: include/linux/skbuff.h:2008
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a90471)
Location: include/linux/skbuff.h:2008
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
In fs/io_uring.c (ffffffff81380044)
Location: include/linux/skbuff.h:2031
Inline: True
```
```
In drivers/net/tun.c (ffffffff8188dd18)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81899f3a)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
```
```
In net/core/sock.c (ffffffff819e5d9d)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb750)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81a06ae5)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81a12f24)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff81a3da85)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff81a49988)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81a606e5)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81a65b94)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:try_bulk_dequeue_skb_slow
```
```
In net/ipv4/ip_output.c (ffffffff81a9eb58)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aa7a3f)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81ab2235)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81abeb16)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81accd9e)
Location: include/linux/skbuff.h:2031
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad5f8f)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11ae6)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d92f)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/xfrm/espintcp.c (ffffffff81b223bc)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_queue_out
```
```
In net/unix/af_unix.c (ffffffff81b27126)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81b29206)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f216)
Location: include/linux/skbuff.h:2031
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b8ba47)
Location: include/linux/skbuff.h:2031
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bab69b)
Location: include/linux/skbuff.h:2031
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
In fs/io_uring.c (ffffffff8138eb64)
Location: include/linux/skbuff.h:2052
Inline: True
```
```
In drivers/net/tun.c (ffffffff8189c12d)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff818a9084)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
```
```
In net/core/sock.c (ffffffff819e5870)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb470)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81a080b5)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81a1328b)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff81a40715)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff81a4f15d)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81a68f74)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81a6dcb4)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:try_bulk_dequeue_skb_slow
```
```
In net/ipv4/ip_output.c (ffffffff81aa8a9c)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ab20bf)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81abd1fb)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81aca476)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8d9e)
Location: include/linux/skbuff.h:2052
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ae256f)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1f276)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c1ff)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/xfrm/espintcp.c (ffffffff81b30dbc)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_queue_out
```
```
In net/unix/af_unix.c (ffffffff81b35a28)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81b37b36)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81b3dc66)
Location: include/linux/skbuff.h:2052
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b9aeb6)
Location: include/linux/skbuff.h:2052
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bbb859)
Location: include/linux/skbuff.h:2052
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
In fs/io_uring.c (ffffffff8139b956)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - fs/io_uring.c:io_rsrc_file_put
  - fs/io_uring.c:io_rsrc_file_put
  - fs/io_uring.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff8187e694)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8188c4ea)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
```
```
In net/core/sock.c (ffffffff819cb980)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819d1980)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/dev.c (ffffffff819ee795)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff819fa82a)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff81a253c5)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff81a34183)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81a4c334)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81a5651d)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a93bb9)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81a9d34f)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81aa803c)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ab52f0)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3e0d)
Location: include/linux/skbuff.h:2068
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81acd48f)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0cef6)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19e5f)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/xfrm/espintcp.c (ffffffff81b1eaec)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_queue_out
```
```
In net/unix/af_unix.c (ffffffff81b23610)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81b257d4)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b121)
Location: include/linux/skbuff.h:2068
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81b5ed17)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff81b8a8a8)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81baf78b)
Location: include/linux/skbuff.h:2068
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
In fs/io_uring.c (ffffffff813e49a3)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - fs/io_uring.c:io_rsrc_file_put
  - fs/io_uring.c:io_rsrc_file_put
  - fs/io_uring.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff8190fea9)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8191f9ae)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
```
```
In net/core/sock.c (ffffffff81a7b036)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81a81574)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:msg_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81a9fa45)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81aad76f)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff81ada0e5)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff81ae9c83)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81b047e4)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81b0f2ae)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81b4eff9)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81b5921f)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81b64533)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81b722e0)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b8249d)
Location: include/linux/skbuff.h:2097
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b8be4f)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd00e6)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde47f)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/xfrm/espintcp.c (ffffffff81be373c)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_queue_out
```
```
In net/unix/af_unix.c (ffffffff81be7aa0)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81beaee1)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81bf123c)
Location: include/linux/skbuff.h:2097
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81c264b7)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff81c569c5)
Location: include/linux/skbuff.h:2097
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81c77d89)
Location: include/linux/skbuff.h:2097
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
In io_uring/io_uring.c (ffffffff816c8c08)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_rsrc_file_put
  - io_uring/io_uring.c:io_rsrc_file_put
  - io_uring/io_uring.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff81a63b88)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81a74aa1)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
```
```
In net/core/sock.c (ffffffff81bee659)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81bf5201)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81c11146)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81c22be3)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81c5b614)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff81c6c4e3)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81c8a07d)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81c96499)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81cdc959)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ce97c9)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81cf3349)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81d019f6)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d1299d)
Location: include/linux/skbuff.h:2448
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d18afe)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6630e)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81d75299)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/xfrm/espintcp.c (ffffffff81d7aa5c)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_queue_out
```
```
In net/unix/af_unix.c (ffffffff81d809e7)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81d83131)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81d89a39)
Location: include/linux/skbuff.h:2448
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81dc414b)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff81df5d79)
Location: include/linux/skbuff.h:2448
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81e1ce02)
Location: include/linux/skbuff.h:2448
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
In io_uring/rsrc.c (ffffffff817a03e8)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_file_put
  - io_uring/rsrc.c:io_rsrc_file_put
  - io_uring/rsrc.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff81bf2d68)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81c08d01)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
```
```
In net/core/sock.c (ffffffff81d9e119)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81da3721)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81dc0db6)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81dd81e2)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81e11924)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff81e23ee3)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81e44c5d)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81e52089)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81e9d3b9)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ead509)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81eb7979)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ec6b66)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed87dd)
Location: include/linux/skbuff.h:2306
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee19c1)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f3109e)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81f417b7)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue_net
```
```
In net/xfrm/espintcp.c (ffffffff81f479ec)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_queue_out
```
```
In net/unix/af_unix.c (ffffffff81f4e547)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81f507a1)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81f578f3)
Location: include/linux/skbuff.h:2306
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81f942ab)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff81fca304)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81ff4332)
Location: include/linux/skbuff.h:2306
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/fastopen.c (ffffffff8200ef9a)
Location: include/linux/skbuff.h:2306
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
In io_uring/rsrc.c (ffffffff817e13ed)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_file_scm_put
  - io_uring/rsrc.c:io_rsrc_file_scm_put
  - io_uring/rsrc.c:io_rsrc_file_scm_put
```
```
In drivers/net/tun.c (ffffffff81c49f48)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81c6e471)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
```
```
In net/core/sock.c (ffffffff81e0c98e)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81e12316)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81e309c8)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81e494ff)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81e85234)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff81e99423)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81e9fa5d)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81ead8f9)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81efa91d)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81f0bc19)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81f1604a)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81f2530f)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f378ed)
Location: include/linux/skbuff.h:2342
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f413c2)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f9184d)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1057)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue_net
```
```
In net/xfrm/espintcp.c (ffffffff81fa749c)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_queue_out
```
```
In net/unix/af_unix.c (ffffffff81faec7a)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81fb0111)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81fb73d2)
Location: include/linux/skbuff.h:2342
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81ff4c2b)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff8202b108)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff82070b42)
Location: include/linux/skbuff.h:2342
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/fastopen.c (ffffffff8208bb91)
Location: include/linux/skbuff.h:2342
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
In drivers/net/tun.c (ffffffff81cff8d8)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_rx_batched
```
```
In drivers/net/xen-netfront.c (ffffffff81d22ca0)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
```
```
In net/core/sock.c (ffffffff81ec9306)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81ecf4d6)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:skb_errqueue_purge
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81eecf4e)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81f081ef)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81f47224)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff81f5bb12)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81f622cd)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81f70399)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81fbe85b)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81fcfcc9)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81fda3e0)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9bc8)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffd9c7)
Location: include/linux/skbuff.h:2349
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82007012)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205f5ad)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff8206e377)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue_net
```
```
In net/xfrm/espintcp.c (ffffffff8207474c)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_queue_out
```
```
In net/unix/af_unix.c (ffffffff8207c19c)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff8207d771)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff82084a6c)
Location: include/linux/skbuff.h:2349
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff820c27fb)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff820fac0f)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff82144d52)
Location: include/linux/skbuff.h:2349
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/fastopen.c (ffffffff82161991)
Location: include/linux/skbuff.h:2349
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
In drivers/net/tun.c (ffff8000109e0e0c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffff800010a087b0)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffff800010bad094)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffff800010bb38bc)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffff800010bcfac0)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffff800010be3244)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffff800010c10a10)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffff800010c1b984)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffff800010c30c14)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffff800010c39568)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffff800010c6515c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffff800010c6ed3c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffff800010c7eb10)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffff800010c847cc)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93494)
Location: include/linux/skbuff.h:2008
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9c57c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdc008)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffff800010cea004)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffff800010cf345c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffff800010cf4978)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffff800010cf98d0)
Location: include/linux/skbuff.h:2008
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d5dc74)
Location: include/linux/skbuff.h:2008
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
In drivers/net/tun.c (c0ac51bc)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad0d2c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_find_ts
```
```
In net/core/sock.c (c0cca3f0)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c0ccdb90)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (c0ce4224)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (c0cfbc74)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (c0d28098)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (c0d327d0)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (c0d47a28)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (c0d4b9ac)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (c0d74d3c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (c0d7d85c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (c0d8db3c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (c0d93acc)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (c0da1c9c)
Location: include/linux/skbuff.h:2008
Inline: True
```
```
In net/ipv4/udp.c (c0da7720)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (c0de5828)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (c0df1ea0)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (c0df8ff0)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (c0dfb5fc)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (c0e0111c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
```
```
In net/packet/af_packet.c (c0e5c7cc)
Location: include/linux/skbuff.h:2008
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
In drivers/net/tun.c (c000000000aa1e40)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/sock.c (c000000000c824a8)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c000000000c86340)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (c000000000cac67c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (c000000000cc4d24)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (c000000000cfc720)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (c000000000d0ac1c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (c000000000d29998)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (c000000000d32270)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (c000000000d6951c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (c000000000d74e94)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (c000000000d88f60)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (c000000000d90504)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (c000000000da36f0)
Location: include/linux/skbuff.h:2008
Inline: True
```
```
In net/ipv4/udp.c (c000000000daea5c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (c000000000dfe000)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (c000000000e0d854)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (c000000000e1680c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (c000000000e1a8e0)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (c000000000e216b0)
Location: include/linux/skbuff.h:2008
Inline: True
```
```
In net/packet/af_packet.c (c000000000e968a0)
Location: include/linux/skbuff.h:2008
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
In drivers/net/tun.c (ffffffe00062a7a2)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/sock.c (ffffffe00073f070)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffe0007415fa)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffe000759c7c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffe0007693f4)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffe00078c74c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffe000794d0c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffe0007a6b36)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffe0007aa9c2)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffffffe0007cc9dc)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffe0007d3af2)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffe0007e0db4)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffe0007e61e4)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f2996)
Location: include/linux/skbuff.h:2008
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007fa5d8)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082b560)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffe000837bd4)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffe00083e532)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffe000840704)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffe0008455de)
Location: include/linux/skbuff.h:2008
Inline: True
```
```
In net/packet/af_packet.c (ffffffe000893a06)
Location: include/linux/skbuff.h:2008
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
In drivers/net/tun.c (ffffffff8178a3b1)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81792b89)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff818b3c8b)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818b7196)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff818d1322)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff818e2c25)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff81909f55)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff819147c3)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff819288e1)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff8192dd3b)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffffffff81954871)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8195c95f)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff8196bd28)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff81971a72)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197f76c)
Location: include/linux/skbuff.h:2008
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81987ebc)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bf90b)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff819caaec)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffff819d1c58)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff819d3a7b)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff819d9014)
Location: include/linux/skbuff.h:2008
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2fb01)
Location: include/linux/skbuff.h:2008
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
In drivers/net/tun.c (ffffffff81769d01)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/sock.c (ffffffff8186dbdb)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818710e6)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff8188b1be)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff8189ca65)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff818c3e05)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff818ce583)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff818e2691)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff818e783b)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffffffff8190e361)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8191644f)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81925818)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff8192b542)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8193922c)
Location: include/linux/skbuff.h:2008
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194197c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c6fb)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff819878dc)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffff8198ea18)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff8199083b)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81995dd4)
Location: include/linux/skbuff.h:2008
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819eccf1)
Location: include/linux/skbuff.h:2008
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
In drivers/net/tun.c (ffffffff817ba751)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817c2de9)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81904c8b)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81908196)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff81922322)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81933c55)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff8195af85)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff819657f3)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff81979a71)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff8197eecb)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffffffff819bf041)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819c712f)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819d64f8)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff819dc242)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e9f3c)
Location: include/linux/skbuff.h:2008
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f268c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2a38b)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81a3556c)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffff81a3c6d8)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81a3e4fb)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a43a94)
Location: include/linux/skbuff.h:2008
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a9b6b1)
Location: include/linux/skbuff.h:2008
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
In drivers/net/tun.c (ffffffff817d2be5)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817dd0a9)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81925d2b)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819291d6)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/dev.c (ffffffff8194336d)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/neighbour.c (ffffffff81954055)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/netpoll.c (ffffffff8197d1a5)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffffffff81987a33)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/gro_cells.c (ffffffff8199bf85)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff819a144b)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/ipv4/ip_output.c (ffffffff819c89c4)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819d0c7f)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819e0118)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff819e5ec2)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f3d6c)
Location: include/linux/skbuff.h:2008
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fc4da)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3591b)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81a40ecc)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/unix/af_unix.c (ffffffff81a4737d)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/unix/garbage.c (ffffffff81a49f5b)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a4f734)
Location: include/linux/skbuff.h:2008
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa5ea3)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
</details>
</li>
</ul>

## Differences

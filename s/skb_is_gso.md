# Function: <code>skb_is_gso</code>

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
In drivers/net/tun.c (ffffffff815ee348)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/virtio_net.c (ffffffff815f23f2)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff815faca5)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/dev.c (ffffffff81716a12)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff81740c28)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff817490c8)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffff8175a8c6)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8175d708)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/udp.c (ffffffff81786690)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a4a54)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc593)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/ipv6/ip6_output.c (ffffffff817c4e77)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/xfrm6_output.c (ffffffff817fd081)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/ip6_checksum.c (ffffffff818000e3)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/packet/af_packet.c (ffffffff81804636)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In drivers/net/tun.c (ffffffff8164eb07)
Location: include/linux/skbuff.h:3718
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81651d10)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff8165bc30)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81783a56)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff8179d780)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/sched/sch_generic.c (ffffffff817ada4d)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff817b608e)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffff817c6c7d)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817caf7e)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/udp.c (ffffffff817f3879)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff817f8987)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8180255f)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81812861)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81812c09)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/xfrm/xfrm_output.c (ffffffff818294b3)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/ipv6/ip6_output.c (ffffffff81833d69)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/xfrm6_output.c (ffffffff8186c9b1)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/ip6_checksum.c (ffffffff8187179c)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff8187297a)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff818786a7)
Location: include/linux/skbuff.h:3718
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff81680819)
Location: include/linux/skbuff.h:3770
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81689a0e)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff817b11c7)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff817cb745)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/sched/sch_generic.c (ffffffff817dd089)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff817e5a2b)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffff817f677e)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817fabc4)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp_offload.c (ffffffff8182160e)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81824669)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/af_inet.c (ffffffff81833506)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81843d61)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/xfrm/xfrm_output.c (ffffffff8185ae83)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/ipv6/ip6_output.c (ffffffff818657e0)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/xfrm6_output.c (ffffffff8189f7a1)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/ip6_checksum.c (ffffffff818a5cfc)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/packet/af_packet.c (ffffffff818acef9)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff81695c0c)
Location: include/linux/skbuff.h:3834
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8169f203)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff817d15a4)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff817eaf37)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/sched/sch_generic.c (ffffffff817fc6ca)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff8180555b)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffff81816b78)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8181af85)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp_offload.c (ffffffff818422f4)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81845507)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/af_inet.c (ffffffff8185487b)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818655f1)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_output.c (ffffffff818724f3)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_output.c (ffffffff8187ef7a)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff8187f651)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff818801b6)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81889feb)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff818c5d50)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/ip6_checksum.c (ffffffff818cc75c)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/packet/af_packet.c (ffffffff818d542a)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff81700759)
Location: include/linux/skbuff.h:4025
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8170a39a)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff8184b6b8)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff818665a7)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/sched/sch_generic.c (ffffffff8187a12a)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff8188426b)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffff81895d3e)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff818988bd)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp_offload.c (ffffffff818c1bc5)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff818c4e0b)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff818ca3e0)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff818d471f)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e5741)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff818e5a7c)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff818f2ee9)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_output.c (ffffffff819000a5)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff8190077f)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff819012d9)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff8190b1db)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff819490e2)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/ip6_checksum.c (ffffffff8195150c)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff8195277b)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81959eda)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff8173fd9d)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/xen-netfront.c (ffffffff81748a3f)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81895a03)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff818b49ad)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/sched/sch_generic.c (ffffffff818cc14f)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff818d7cd7)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffff818e9ffe)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff818ed5d8)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp_offload.c (ffffffff819178b1)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff8191aabc)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81920d8e)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8192adf3)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193bfe4)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff8193c3d5)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81949820)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81956b27)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff8195725b)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff8195819e)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81962566)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff819a2171)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/ip6_checksum.c (ffffffff819aaabb)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff819abd46)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff819af176)
Location: include/linux/skbuff.h:4035
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff81763dbb)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/xen-netfront.c (ffffffff8176cae3)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff818b76e4)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff818dc2a6)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/sched/sch_generic.c (ffffffff818f6b8f)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff819044c7)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffff8191741d)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8191a0d8)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/tcp_offload.c (ffffffff81945fe8)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff8194927c)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff8194f8fb)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8195a56e)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196bcf9)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff8196c0cd)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b4e0)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b75c)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff8198beb1)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff8198caf1)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81997572)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/udp.c (ffffffff819bb3ed)
Location: include/linux/skbuff.h:4198
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff819d8dce)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e15ab)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff819e28f8)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff819e5b40)
Location: include/linux/skbuff.h:4198
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff817a1b46)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/xen-netfront.c (ffffffff817aac35)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81903526)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff8192923d)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (ffffffff8194373e)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_generic.c (ffffffff8195631b)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81965857)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffff81979361)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8197c266)
Location: include/linux/skbuff.h:4305
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819aa61c)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819ad8d2)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff819b4135)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819bf0f1)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2a49)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff819d2e20)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e4a03)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6c81)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff819f7447)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff819f80e3)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81a0354e)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/udp.c (ffffffff81a29ffd)
Location: include/linux/skbuff.h:4305
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a47645)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a50377)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81a51596)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81a5556f)
Location: include/linux/skbuff.h:4305
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff817c2816)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/xen-netfront.c (ffffffff817ce678)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff819362d6)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff8195b91d)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (ffffffff81978739)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_generic.c (ffffffff8198c7bb)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff8199c2e7)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffff819afcfc)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819b2c16)
Location: include/linux/skbuff.h:4389
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819e12ec)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819e4582)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff819eae65)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819f5d31)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a095b9)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81a0998e)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1ba23)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d8f1)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81a2e097)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2ed33)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81a3a11e)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/udp.c (ffffffff81a60b1d)
Location: include/linux/skbuff.h:4389
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a7e1c5)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/seg6_local.c (ffffffff81a84b9a)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a86f97)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81a881b6)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81a8c63f)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff8188aa84)
Location: include/linux/skbuff.h:4429
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81899767)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81a0aef7)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a2ec73)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_4_to_6
  - net/core/filter.c:bpf_skb_proto_4_to_6
```
```
In net/core/lwt_bpf.c (ffffffff81a4d6df)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_generic.c (ffffffff81a64820)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81a75027)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffff81a99ba1)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a9ccb0)
Location: include/linux/skbuff.h:4429
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81ace92c)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81ad6b22)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81ad8ad8)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ae4221)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8dd0)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81afa0fe)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1f03d)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81b20fc3)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81b21824)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f87b)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/udp.c (ffffffff81b59bee)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b78e91)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_local.c (ffffffff81b7fc2a)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b82247)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81b83686)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81b879ec)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff81898c84)
Location: include/linux/skbuff.h:4458
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff818a7c97)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81a0c140)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a3020e)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_4_to_6
  - net/core/filter.c:bpf_skb_proto_4_to_6
```
```
In net/core/lwt_bpf.c (ffffffff81a533a6)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_generic.c (ffffffff81a6c960)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81a7df27)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffff81aa3af1)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81aa6b42)
Location: include/linux/skbuff.h:4458
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81ada94c)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81ae3102)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5002)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81af1151)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06b96)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81b078bf)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2d8fd)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81b2f997)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81b301f4)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e2cc)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/udp.c (ffffffff81b6824e)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b87e11)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_local.c (ffffffff81b8ef5a)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b91937)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92d46)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81b974cc)
Location: include/linux/skbuff.h:4458
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff8187b3b8)
Location: include/linux/skbuff.h:4522
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8188b586)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff819f22f3)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81a1228a)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (ffffffff81a38bd3)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_generic.c (ffffffff81a5517f)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81a66d77)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffff81a8ebeb)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a91b4f)
Location: include/linux/skbuff.h:4522
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac5980)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81aca385)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81ad021b)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81adc911)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af22bb)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81af305d)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1b95c)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81b1d69c)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1df30)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81b2cb1a)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/udp.c (ffffffff81b56525)
Location: include/linux/skbuff.h:4522
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b76adb)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_local.c (ffffffff81b7df9a)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b80b8a)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81e97)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81b864cb)
Location: include/linux/skbuff.h:4522
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff8190c768)
Location: include/linux/skbuff.h:4561
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8191e476)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81aa41c3)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81ac2f5a)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (ffffffff81aeeaaf)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_generic.c (ffffffff81b0e3af)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81b20237)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffff81b49e27)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81b4cf3f)
Location: include/linux/skbuff.h:4561
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81b84190)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81b88c65)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81b8ec3b)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81b9bceb)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb27cb)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81bb356d)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/xfrm/xfrm_output.c (ffffffff81be01e8)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81be24fd)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff81be2a20)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81bf2c6a)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/udp.c (ffffffff81c1cb95)
Location: include/linux/skbuff.h:4561
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c41543)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_local.c (ffffffff81c48e0a)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81c4cbaa)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4df17)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81c5288b)
Location: include/linux/skbuff.h:4561
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff81a60374)
Location: include/linux/skbuff.h:4983
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81a72946)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81c198d1)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81c3dc87)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gro.c (ffffffff81c54196)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/lwt_bpf.c (ffffffff81c71966)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_generic.c (ffffffff81c94830)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81ca8487)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffff81cd735a)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81cda6c8)
Location: include/linux/skbuff.h:4983
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81d1495f)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81d19fc0)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81d1f8dc)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81d2dab6)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45f99)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81d46d8f)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/xfrm/xfrm_output.c (ffffffff81d770ff)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81d795f3)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff81d79b7b)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81d8b7b7)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/udp.c (ffffffff81db9455)
Location: include/linux/skbuff.h:4983
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81ddfcde)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_local.c (ffffffff81de8513)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81decfed)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee620)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81df5897)
Location: include/linux/skbuff.h:4983
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff81bebb48)
Location: include/linux/skbuff.h:4879
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81c050b6)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81daaa5f)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff81dca90d)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81df1dd7)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gro.c (ffffffff81e09942)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/lwt_bpf.c (ffffffff81e29a56)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_generic.c (ffffffff81e502f0)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81e652a7)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffff81e9797b)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81e9aea8)
Location: include/linux/skbuff.h:4879
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81edb239)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81ee0c30)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81ee6acc)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ef59b6)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f379)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81f105df)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/xfrm/xfrm_output.c (ffffffff81f4397f)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81f46083)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff81f4697a)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81f597e3)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/udp.c (ffffffff81f894b5)
Location: include/linux/skbuff.h:4879
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb1ffe)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb4de)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81fc0ded)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc2240)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81fc970c)
Location: include/linux/skbuff.h:4879
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff81c43fe9)
Location: include/linux/skbuff.h:4842
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81c50bb1)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:xmit_skb
```
```
In drivers/net/xen-netfront.c (ffffffff81c6a7c5)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81e1a503)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff81e3b492)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81e63d67)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gro.c (ffffffff81e7c119)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/lwt_bpf.c (ffffffff81e9f097)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_generic.c (ffffffff81eaba93)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81ec11e7)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_input.c (ffffffff81ef3f96)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_forward.c (ffffffff81ef61be)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81ef98a8)
Location: include/linux/skbuff.h:4842
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81f3a23a)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81f40560)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81f4631e)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81f55369)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f069)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81f702cb)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3159)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81fa57f0)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa62ba)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81fb9497)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/udp.c (ffffffff81fe88f5)
Location: include/linux/skbuff.h:4842
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff82012718)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_local.c (ffffffff8201bb9e)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff82021d7d)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff820231c0)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff8202bbcc)
Location: include/linux/skbuff.h:4842
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff81cf98a9)
Location: include/linux/skbuff.h:4882
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81d06bf1)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:xmit_skb
```
```
In drivers/net/xen-netfront.c (ffffffff81d1f1a5)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81ed7ac3)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff81eedf77)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/core/dev.c:tc_run
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81f22f44)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gro.c (ffffffff81f3c469)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/lwt_bpf.c (ffffffff81f61807)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_generic.c (ffffffff81f6e533)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81f844e7)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_input.c (ffffffff81fb7f29)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_forward.c (ffffffff81fba157)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81fbd7c8)
Location: include/linux/skbuff.h:4882
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff8200032a)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff820061b0)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff8200c45e)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8201b5d9)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035799)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff820369fb)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/xfrm/xfrm_output.c (ffffffff820707d9)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff82072b40)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff820735bf)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff82086a3b)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/udp.c (ffffffff820b7445)
Location: include/linux/skbuff.h:4882
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff820e18e4)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/seg6_local.c (ffffffff820eab5e)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff820f0e9d)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff820f220b)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff820fb67d)
Location: include/linux/skbuff.h:4882
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffff8000109dd308)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ebb48)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_start_xmit
```
```
In drivers/net/xen-netfront.c (ffff800010a08ad0)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffff800010bd494c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffff800010bfcc50)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (ffff800010c1f3d8)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_generic.c (ffff800010c383cc)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffff800010c49588)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffff800010c6039c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffff800010c64108)
Location: include/linux/skbuff.h:4389
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffff800010c952f8)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffff800010c98fd8)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffff800010ca0a24)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffff800010cab95c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc295c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffff800010cc2c54)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7cb4)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_output.c (ffff800010cec688)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffff800010ced050)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffff800010cedb88)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffff800010cfb0cc)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/udp.c (ffff800010d26760)
Location: include/linux/skbuff.h:4389
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffff800010d495dc)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/seg6_local.c (ffff800010d50c48)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffff800010d536e0)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffff800010d54d28)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffff800010d57e04)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (c0ac5ad0)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acdee0)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_start_xmit
```
```
In net/core/dev.c (c0ceef14)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (c0d18078)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (c0d36f88)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_generic.c (c0d49fa8)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (c0d5a2d0)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (c0d6fce0)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c0d72f94)
Location: include/linux/skbuff.h:4389
Inline: True
```
```
In net/ipv4/tcp_offload.c (c0da3a3c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (c0da6f6c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (c0dadbdc)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (c0db8860)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (c0dce1ac)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (c0dce518)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (c0de17a0)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_output.c (c0df45b0)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (c0df4e2c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (c0df5c50)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (c0e01b3c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/udp.c (c0e29dbc)
Location: include/linux/skbuff.h:4389
Inline: True
```
```
In net/ipv6/xfrm6_output.c (c0e4a9e0)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/seg6_local.c (c0e51798)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (c0e53f98)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (c0e5533c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (c0e59d7c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (c000000000aa3990)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/core/dev.c (c000000000cb3a58)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (c000000000ce51b0)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (c000000000d1129c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_generic.c (c000000000d3131c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (c000000000d46d60)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (c000000000d63438)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c000000000d67030)
Location: include/linux/skbuff.h:4389
Inline: True
```
```
In net/ipv4/tcp_offload.c (c000000000da62d8)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (c000000000daa9b0)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (c000000000db3374)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (c000000000dc2340)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dde1d4)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (c000000000ddeba4)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (c000000000df7d34)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_output.c (c000000000e1088c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (c000000000e113f4)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (c000000000e12534)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (c000000000e22604)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/udp.c (c000000000e56450)
Location: include/linux/skbuff.h:4389
Inline: True
```
```
In net/ipv6/xfrm6_output.c (c000000000e7ec18)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/seg6_local.c (c000000000e88a4c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (c000000000e8be80)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (c000000000e8d950)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (c000000000e92f28)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffe000628532)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/core/dev.c (ffffffe00075e710)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffe00077f0d8)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (ffffffe000798ae0)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_generic.c (ffffffe0007a8fb2)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffe0007b6ba6)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffe0007c8620)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffe0007cb0e2)
Location: include/linux/skbuff.h:4389
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f4508)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffe0007f8a8e)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd0d6)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffe0008065ca)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817dc0)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffe0008180a8)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffe0008282c0)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_output.c (ffffffe000839d70)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffe00083a588)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b11c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffe000845bf6)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/udp.c (ffffffe000866f48)
Location: include/linux/skbuff.h:4389
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffe000882a76)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/seg6_local.c (ffffffe000888f96)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b3ee)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c634)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffe00088faaa)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff817872e6)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/xen-netfront.c (ffffffff81793298)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff818d62a6)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff818fb8ed)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (ffffffff819185a9)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_generic.c (ffffffff8192c62b)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff8193c157)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffff8194fb6c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81952a86)
Location: include/linux/skbuff.h:4389
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff8198115c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819843f2)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff8198acd5)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81995ad1)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a9359)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff819a972e)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb0b3)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_output.c (ffffffff819ccf81)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff819cd727)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce3c3)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff819d97ae)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/udp.c (ffffffff81a001ad)
Location: include/linux/skbuff.h:4389
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a1d855)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/seg6_local.c (ffffffff81a2422a)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a26627)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81a27846)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81a2bccf)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff81766c36)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/vxlan.c (ffffffff8176be06)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_build_skb
```
```
In net/core/dev.c (ffffffff818900e6)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff818b571d)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (ffffffff818d2359)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_generic.c (ffffffff818e612b)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff818f5c57)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffff8190965c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8190c576)
Location: include/linux/skbuff.h:4389
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff8193ac1c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff8193deb2)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81944795)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8194f591)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962e19)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff819631ee)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ip_tunnel.c (ffffffff81966cc8)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
```
```
In net/ipv4/xfrm4_output.c (ffffffff81977ea3)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81989d71)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff8198a517)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b1b3)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff8199656e)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/udp.c (ffffffff819bcf6d)
Location: include/linux/skbuff.h:4389
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff819da615)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/seg6_local.c (ffffffff819e0fea)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e33e7)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff819e4606)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff819e8ebf)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff817b7696)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/xen-netfront.c (ffffffff817c34f8)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff819272d6)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff8194c91d)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (ffffffff81969739)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_generic.c (ffffffff8197d7bb)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff8198d2e7)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199a92b)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_enqueue_packet
```
```
In net/ipv4/ip_forward.c (ffffffff819ba33c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819bd256)
Location: include/linux/skbuff.h:4389
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819eb92c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819eebc2)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff819f54a5)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81a00371)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13bf9)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81a13fce)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25b33)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81a37a01)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81a381a7)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81a38e43)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81a4422e)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/udp.c (ffffffff81a6ac2d)
Location: include/linux/skbuff.h:4389
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a882d5)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ecaa)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a921d7)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81a933f6)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81a9787f)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff817d1cfc)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/xen-netfront.c (ffffffff817dd7b8)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff8194893f)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff8196e2dd)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (ffffffff8198bb19)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_generic.c (ffffffff8199fd2b)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff819afb77)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_forward.c (ffffffff819c3c2c)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819c6b66)
Location: include/linux/skbuff.h:4389
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819f57dc)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819f8d32)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff819ff6a5)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81a0a3c1)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e5d9)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81a1e9be)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a30fd3)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81a433c1)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81a4420b)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44863)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81a4fed9)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/udp.c (ffffffff81a7723d)
Location: include/linux/skbuff.h:4389
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a94f25)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/seg6_local.c (ffffffff81a9ba1a)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9e287)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f546)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81aa419f)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
</details>
</li>
</ul>

## Differences

# Function: <code>skb_orphan</code>

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
In drivers/net/loopback.c (ffffffff815e985e)
Location: include/linux/skbuff.h:2211
Inline: True
```
```
In drivers/net/tun.c (ffffffff815ee909)
Location: include/linux/skbuff.h:2211
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/virtio_net.c (ffffffff815f24e6)
Location: include/linux/skbuff.h:2211
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In net/core/sock.c (ffffffff81702499)
Location: include/linux/skbuff.h:2211
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff817061a0)
Location: include/linux/skbuff.h:2211
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/datagram.c (ffffffff8170d038)
Location: include/linux/skbuff.h:2211
Inline: True
Inline callers:
  - net/core/datagram.c:skb_free_datagram_locked
```
```
In net/netlink/af_netlink.c (ffffffff8174bc20)
Location: include/linux/skbuff.h:2211
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_input.c (ffffffff817590ad)
Location: include/linux/skbuff.h:2211
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817597a3)
Location: include/linux/skbuff.h:2211
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_input.c (ffffffff8176cd19)
Location: include/linux/skbuff.h:2211
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81775ec0)
Location: include/linux/skbuff.h:2211
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81782ae1)
Location: include/linux/skbuff.h:2211
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/ip6_input.c (ffffffff817c8d31)
Location: include/linux/skbuff.h:2211
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f0bb8)
Location: include/linux/skbuff.h:2211
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/packet/af_packet.c (ffffffff81806fb3)
Location: include/linux/skbuff.h:2211
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/loopback.c (ffffffff81647fae)
Location: include/linux/skbuff.h:2346
Inline: True
```
```
In drivers/net/tun.c (ffffffff8164d4cc)
Location: include/linux/skbuff.h:2346
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/virtio_net.c (ffffffff81651e64)
Location: include/linux/skbuff.h:2346
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In net/core/sock.c (ffffffff81769a96)
Location: include/linux/skbuff.h:2346
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8176cce1)
Location: include/linux/skbuff.h:2346
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/datagram.c (ffffffff8177465e)
Location: include/linux/skbuff.h:2346
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_free_datagram_locked
```
```
In net/netlink/af_netlink.c (ffffffff817b8bf1)
Location: include/linux/skbuff.h:2346
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_input.c (ffffffff817c543e)
Location: include/linux/skbuff.h:2346
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817c5b83)
Location: include/linux/skbuff.h:2346
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_input.c (ffffffff817da615)
Location: include/linux/skbuff.h:2346
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff817e2e4c)
Location: include/linux/skbuff.h:2346
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efc7c)
Location: include/linux/skbuff.h:2346
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81835fb4)
Location: include/linux/skbuff.h:2346
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185f796)
Location: include/linux/skbuff.h:2346
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff8187a1fd)
Location: include/linux/skbuff.h:2346
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/loopback.c (ffffffff816790ce)
Location: include/linux/skbuff.h:2382
Inline: True
```
```
In drivers/net/tun.c (ffffffff8167f1f2)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff817969a6)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8179a161)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/datagram.c (ffffffff817a195e)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_free_datagram_locked
```
```
In net/netlink/af_netlink.c (ffffffff817e86a1)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_input.c (ffffffff817f4f4e)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817f5683)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_input.c (ffffffff81808fa7)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff818134fc)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8182068c)
Location: include/linux/skbuff.h:2382
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81867ad4)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818916de)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff818ab337)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/loopback.c (ffffffff8168d87c)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81694406)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff817b39af)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff817b9428)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/datagram.c (ffffffff817bfea7)
Location: include/linux/skbuff.h:2431
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81808672)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_input.c (ffffffff818153e8)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81815b22)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_input.c (ffffffff81829268)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff818336e9)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840b9c)
Location: include/linux/skbuff.h:2431
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff8188c27c)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b7d1d)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff818d45fb)
Location: include/linux/skbuff.h:2431
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
In kernel/bpf/sockmap.c (ffffffff811b0d61)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
```
```
In drivers/net/loopback.c (ffffffff816f73fc)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff816fe527)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff8182cc45)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81831bd6)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/datagram.c (ffffffff81839a57)
Location: include/linux/skbuff.h:2518
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818874ea)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_input.c (ffffffff818945b8)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81894cf1)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_input.c (ffffffff818ae2a2)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff818b2a5e)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c030c)
Location: include/linux/skbuff.h:2518
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff8190d56c)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193ab8b)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffffffff8194fcfc)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff8195905f)
Location: include/linux/skbuff.h:2518
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
In kernel/bpf/sockmap.c (ffffffff811cc764)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
```
```
In drivers/net/loopback.c (ffffffff81734591)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8173d6e9)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81876a35)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8187c090)
Location: include/linux/skbuff.h:2530
Inline: True
```
```
In net/core/datagram.c (ffffffff81884197)
Location: include/linux/skbuff.h:2530
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818dabd8)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_input.c (ffffffff818e87ca)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff818e8df6)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_input.c (ffffffff81903951)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff81907f57)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81915e5d)
Location: include/linux/skbuff.h:2530
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff819649ab)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994215)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffffffff819a8b9e)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff819b2dc0)
Location: include/linux/skbuff.h:2530
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
In drivers/net/loopback.c (ffffffff817576ed)
Location: include/linux/skbuff.h:2606
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff817610a7)
Location: include/linux/skbuff.h:2606
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81897205)
Location: include/linux/skbuff.h:2606
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8189c8f0)
Location: include/linux/skbuff.h:2606
Inline: True
```
```
In net/core/datagram.c (ffffffff818a4617)
Location: include/linux/skbuff.h:2606
Inline: True
```
```
In net/core/skmsg.c (ffffffff818e5e91)
Location: include/linux/skbuff.h:2606
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffffffff819074b8)
Location: include/linux/skbuff.h:2606
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_input.c (ffffffff81915275)
Location: include/linux/skbuff.h:2606
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81915fd6)
Location: include/linux/skbuff.h:2606
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_input.c (ffffffff81931b0e)
Location: include/linux/skbuff.h:2606
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff8193624a)
Location: include/linux/skbuff.h:2606
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81944604)
Location: include/linux/skbuff.h:2606
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81999320)
Location: include/linux/skbuff.h:2606
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cab37)
Location: include/linux/skbuff.h:2606
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffffffff819df6c8)
Location: include/linux/skbuff.h:2606
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff819e9d1e)
Location: include/linux/skbuff.h:2606
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
In drivers/net/loopback.c (ffffffff81793e9d)
Location: include/linux/skbuff.h:2692
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8179ed28)
Location: include/linux/skbuff.h:2692
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff818e1655)
Location: include/linux/skbuff.h:2692
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818e78f1)
Location: include/linux/skbuff.h:2692
Inline: True
```
```
In net/core/datagram.c (ffffffff818efd96)
Location: include/linux/skbuff.h:2692
Inline: True
```
```
In net/core/skmsg.c (ffffffff81935aa1)
Location: include/linux/skbuff.h:2692
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffffffff8196876f)
Location: include/linux/skbuff.h:2692
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_input.c (ffffffff819777a1)
Location: include/linux/skbuff.h:2692
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81978c30)
Location: include/linux/skbuff.h:2692
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp.c (ffffffff81989829)
Location: include/linux/skbuff.h:2692
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8199520b)
Location: include/linux/skbuff.h:2692
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff8199a603)
Location: include/linux/skbuff.h:2692
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a8bf4)
Location: include/linux/skbuff.h:2692
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a05221)
Location: include/linux/skbuff.h:2692
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39788)
Location: include/linux/skbuff.h:2692
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e25f)
Location: include/linux/skbuff.h:2692
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81a582f2)
Location: include/linux/skbuff.h:2692
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
In drivers/net/loopback.c (ffffffff817b79cd)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff817c3514)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81913845)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81919cd3)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/core/datagram.c (ffffffff81921db6)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/core/skmsg.c (ffffffff819688b1)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffffffff8199f20f)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_input.c (ffffffff819ae131)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819af5a0)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp.c (ffffffff819c0c9f)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819cbd5b)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff819d104f)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819df894)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a3be06)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70318)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffffffff81a84ebf)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81a90a87)
Location: include/linux/skbuff.h:2706
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
In drivers/net/loopback.c (ffffffff8187eb0d)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8188e7bf)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff819e5f05)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb6c6)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/datagram.c (ffffffff819f4e40)
Location: include/linux/skbuff.h:2729
Inline: True
```
```
In net/core/filter.c (ffffffff81a2d12e)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
```
```
In net/core/skmsg.c (ffffffff81a3d33e)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffffffff81a78f32)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
```
```
In net/ipv4/ip_input.c (ffffffff81a97fee)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81a99420)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp.c (ffffffff81aab9e0)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81ab1fd7)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff81abe0d3)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81accd36)
Location: include/linux/skbuff.h:2729
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b22689)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/ip6_input.c (ffffffff81b312ac)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b69f2b)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffffffff81b7ff3f)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81b8bcbe)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bab934)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81baf256)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
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
In drivers/net/loopback.c (ffffffff8188d08d)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8189d129)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff819e52d5)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb3e6)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/datagram.c (ffffffff819f4770)
Location: include/linux/skbuff.h:2755
Inline: True
```
```
In net/core/filter.c (ffffffff81a2eeb2)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
```
```
In net/core/skmsg.c (ffffffff81a3f5fb)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/netlink/af_netlink.c (ffffffff81a81762)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
```
```
In net/ipv4/ip_input.c (ffffffff81aa1f4e)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa3390)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp.c (ffffffff81ab6722)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81abcf9b)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff81ac99af)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8d36)
Location: include/linux/skbuff.h:2755
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b31089)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/ip6_input.c (ffffffff81b3fed1)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78a0b)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f3bf)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81b9b134)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bbd5c8)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff81bc151f)
Location: include/linux/skbuff.h:2755
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_discard_data
  - net/mptcp/subflow.c:get_mapping_status
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
In drivers/net/loopback.c (ffffffff8186f9cd)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8187f958)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff819cae35)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819d18f6)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/datagram.c (ffffffff819daa16)
Location: include/linux/skbuff.h:2771
Inline: True
```
```
In net/core/filter.c (ffffffff81a1645e)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
```
```
In net/core/skmsg.c (ffffffff81a4ea5a)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
```
In net/netlink/af_netlink.c (ffffffff81a6a86f)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
```
```
In net/ipv4/ip_input.c (ffffffff81a8ce79)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e500)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp.c (ffffffff81aa18a3)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81aa7de7)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff81ab485c)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3da5)
Location: include/linux/skbuff.h:2771
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b1edb9)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/ip6_input.c (ffffffff81b2dcf8)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66d15)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffffffff81b7e12f)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81b8ab1e)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bacde2)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff81bb2fc5)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
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
In drivers/net/loopback.c (ffffffff818fff6d)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81910ae1)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81a7a465)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81a814c6)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:napi_skb_free_stolen_head
```
```
In net/core/datagram.c (ffffffff81a8b096)
Location: include/linux/skbuff.h:2800
Inline: True
```
```
In net/core/dev.c (ffffffff81a96274)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
```
```
In net/core/filter.c (ffffffff81accd0c)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
```
```
In net/core/skmsg.c (ffffffff81b075c3)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
```
In net/netlink/af_netlink.c (ffffffff81b23e6f)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
```
```
In net/ipv4/ip_input.c (ffffffff81b47fc9)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81b496f0)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp.c (ffffffff81b5d834)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81b641de)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff81b7181c)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b82435)
Location: include/linux/skbuff.h:2800
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81be3d9f)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81bf3f8b)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e8d2)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffffffff81c4974f)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81c56c41)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81c79792)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff81c8166a)
Location: include/linux/skbuff.h:2800
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
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
In drivers/net/loopback.c (ffffffff81a519e2)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81a608b8)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81bede89)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81bf5196)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:napi_skb_free_stolen_head
```
```
In net/core/datagram.c (ffffffff81c0080b)
Location: include/linux/skbuff.h:3169
Inline: True
```
```
In net/core/filter.c (ffffffff81c499f8)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
```
```
In net/core/gro.c (ffffffff81c537fe)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/skmsg.c (ffffffff81c8cd31)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
```
In net/netlink/af_netlink.c (ffffffff81cad66a)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
```
```
In net/ipv4/ip_input.c (ffffffff81cd525f)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6ce0)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_input.c (ffffffff81cf307b)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff81d00f7f)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d12935)
Location: include/linux/skbuff.h:3169
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81d7ab7b)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/ip6_input.c (ffffffff81d8cc22)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcb520)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffffffff81de8f39)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81df6034)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81e1e2c3)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_set_owner_r
  - net/mptcp/protocol.c:mptcp_set_owner_r
```
```
In net/mctp/route.c (ffffffff81e3a0a9)
Location: include/linux/skbuff.h:3169
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_input
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
In drivers/net/loopback.c (ffffffff81bdac22)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81bece79)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81d9a759)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81da36b6)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:napi_skb_free_stolen_head
```
```
In net/core/datagram.c (ffffffff81dafb37)
Location: include/linux/skbuff.h:3063
Inline: True
```
```
In net/core/filter.c (ffffffff81dfec2c)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
```
```
In net/core/gro.c (ffffffff81e08ed5)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/skmsg.c (ffffffff81e47bae)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
```
In net/netlink/af_netlink.c (ffffffff81e6ac1a)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
```
```
In net/ipv4/ip_input.c (ffffffff81e9572f)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81e97270)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp.c (ffffffff81eacca3)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_read_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81eb76ab)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff81ec60df)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed8775)
Location: include/linux/skbuff.h:3063
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee3598)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_read_skb
```
```
In net/xfrm/espintcp.c (ffffffff81f47b4b)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/ip6_input.c (ffffffff81f5ae32)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9c60c)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffffffff81fbc669)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81fca59e)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81ff6d0f)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_set_owner_r
  - net/mptcp/protocol.c:mptcp_set_owner_r
```
```
In net/mptcp/fastopen.c (ffffffff8200ef1d)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
```
```
In net/mctp/route.c (ffffffff82013719)
Location: include/linux/skbuff.h:3063
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_input
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
In drivers/net/loopback.c (ffffffff81c316c6)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81c4537a)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/virtio_net.c (ffffffff81c50fcc)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In net/core/sock.c (ffffffff81e08fb9)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81e122a2)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:napi_skb_free_stolen_head
```
```
In net/core/datagram.c (ffffffff81e1fda7)
Location: include/linux/skbuff.h:3117
Inline: True
```
```
In net/core/filter.c (ffffffff81e701e7)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
```
```
In net/core/gro.c (ffffffff81e7b5f6)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/skmsg.c (ffffffff81ea332c)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
```
In net/netlink/af_netlink.c (ffffffff81ec708a)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
```
```
In net/ipv4/ip_input.c (ffffffff81ef3f37)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef5aa0)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp.c (ffffffff81f0b418)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_read_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81f15d8b)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff81f24824)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f37885)
Location: include/linux/skbuff.h:3117
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f42e1c)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_read_skb
```
```
In net/xfrm/espintcp.c (ffffffff81fa764b)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/ip6_input.c (ffffffff81fbabe2)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffd05c)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffffffff8201cf59)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff8202b3d2)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff820733ef)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_set_owner_r
  - net/mptcp/protocol.c:mptcp_set_owner_r
```
```
In net/mptcp/fastopen.c (ffffffff8208bb16)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
```
```
In net/mctp/route.c (ffffffff82090539)
Location: include/linux/skbuff.h:3117
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_input
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
In drivers/net/loopback.c (ffffffff81ce4546)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81cfaca8)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/virtio_net.c (ffffffff81d07009)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In net/core/sock.c (ffffffff81ec5a29)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81ecf462)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:napi_skb_free_stolen_head
```
```
In net/core/datagram.c (ffffffff81edd457)
Location: include/linux/skbuff.h:3124
Inline: True
```
```
In net/core/filter.c (ffffffff81f2a448)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
```
```
In net/core/gro.c (ffffffff81f3b886)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/skmsg.c (ffffffff81f6566e)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
```
In net/netlink/af_netlink.c (ffffffff81f8a334)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
```
```
In net/ipv4/ip_input.c (ffffffff81fb7eca)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9a50)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp.c (ffffffff81fce444)
Location: include/linux/skbuff.h:3124
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81fda162)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9009)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffd955)
Location: include/linux/skbuff.h:3124
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82008d7c)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_read_skb
```
```
In net/xfrm/espintcp.c (ffffffff820748fb)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/ip6_input.c (ffffffff82088012)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc171)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffffffff820ebf3c)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff820faebd)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff8214763f)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_set_owner_r
  - net/mptcp/protocol.c:mptcp_set_owner_r
```
```
In net/mptcp/fastopen.c (ffffffff82161916)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
```
```
In net/mctp/route.c (ffffffff82166a79)
Location: include/linux/skbuff.h:3124
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_input
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
In drivers/net/loopback.c (ffff8000109d01e4)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffff8000109deecc)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffff800010baaa8c)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffff800010bb3fd4)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/core/datagram.c (ffff800010bbc464)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/core/skmsg.c (ffff800010c0f3c8)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffff800010c4c4d8)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_input.c (ffff800010c5e158)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffff800010c5fd98)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp.c (ffff800010c710a8)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffff800010c7e9a4)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffff800010c83ccc)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93418)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv6/ip6_input.c (ffff800010cfd3a0)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38c50)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffff800010d50f64)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffff800010d5dea8)
Location: include/linux/skbuff.h:2706
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
In drivers/net/loopback.c (c0ab8450)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (c0ac2acc)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (c0cc9d38)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c0cd0bd4)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/core/datagram.c (c0cd89bc)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/core/skmsg.c (c0d268e8)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (c0d5d238)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_input.c (c0d6da8c)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (c0d6f568)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp.c (c0d804d8)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (c0d8d9c8)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (c0d92f48)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (c0da1c10)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv6/ip6_input.c (c0e04658)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/tcp_ipv6.c (c0e3affc)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (c0e51ad8)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (c0e5cc94)
Location: include/linux/skbuff.h:2706
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
In drivers/net/loopback.c (c000000000a8f140)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (c000000000aa0820)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (c000000000c823c8)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c000000000c866f4)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/datagram.c (c000000000c94824)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_free_datagram_locked
```
```
In net/core/skmsg.c (c000000000cf9f84)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (c000000000d4ae24)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_input.c (c000000000d60da0)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (c000000000d62b08)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp.c (c000000000d786b0)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (c000000000d88d6c)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (c000000000d8f688)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (c000000000da3668)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv6/ip6_input.c (c000000000e24e58)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6b63c)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (c000000000e88e6c)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (c000000000e96f7c)
Location: include/linux/skbuff.h:2706
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
In drivers/net/loopback.c (ffffffe00061cc7a)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffe00062812c)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffe00073ec0a)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffe00074409e)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/core/datagram.c (ffffffe00074b16e)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/core/skmsg.c (ffffffe00078af90)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffffffe0007b9876)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_input.c (ffffffe0007c6cc4)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c7ec2)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp.c (ffffffe0007d6a56)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffe0007e0c94)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffe0007e57ac)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f294c)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffe00084776a)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875e82)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffffffe00088921e)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffe000893ed8)
Location: include/linux/skbuff.h:2706
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
In drivers/net/loopback.c (ffffffff8177c4a5)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81787fa5)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff818b3845)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818b9cd3)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/core/datagram.c (ffffffff818c1db6)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/core/skmsg.c (ffffffff81908881)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffffffff8193f07f)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_input.c (ffffffff8194dfa1)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff8194f410)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp.c (ffffffff81960b0f)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8196bbcb)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff81970ebf)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197f704)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff819db496)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0f9a8)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffffffff81a2454f)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81a30117)
Location: include/linux/skbuff.h:2706
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
In drivers/net/loopback.c (ffffffff8175c255)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff817678f5)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff8186d795)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81873c23)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/core/datagram.c (ffffffff8187bcf6)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/core/skmsg.c (ffffffff818c2691)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffffffff818f8b7f)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_input.c (ffffffff81907a91)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81908f00)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp.c (ffffffff8191a5ff)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819256bb)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff8192a98f)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819391c4)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81998256)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cc768)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffffffff819e130f)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff819ed307)
Location: include/linux/skbuff.h:2706
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
In drivers/net/loopback.c (ffffffff817ac84d)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff817b8394)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81904845)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8190acd3)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/core/datagram.c (ffffffff81912db6)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/core/skmsg.c (ffffffff819598b1)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffffffff8199020f)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_input.c (ffffffff819b8771)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9be0)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp.c (ffffffff819cb2df)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819d639b)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff819db68f)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e9ed4)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a45f16)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7a428)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffffffff81a8efcf)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a91269)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather
```
```
In net/packet/af_packet.c (ffffffff81a9bcc7)
Location: include/linux/skbuff.h:2706
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
In drivers/net/loopback.c (ffffffff817c67dd)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff817d0699)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff819258e5)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8192bdd3)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/core/datagram.c (ffffffff81933f36)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/core/skmsg.c (ffffffff8197bac2)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffffffff819b2ade)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_input.c (ffffffff819c1fd1)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819c3620)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp.c (ffffffff819d4e6f)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819dffbb)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff819e530f)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f3d04)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a51c07)
Location: include/linux/skbuff.h:2706
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a86c68)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bd4f)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81aa649b)
Location: include/linux/skbuff.h:2706
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
</details>
</li>
</ul>

## Differences

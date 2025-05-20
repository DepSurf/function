# Function: <code>skb_shared</code>

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
In net/core/skbuff.c (ffffffff817088f9)
Location: include/linux/skbuff.h:1292
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/datagram.c (ffffffff8170cada)
Location: include/linux/skbuff.h:1292
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/core/datagram.c:__skb_checksum_complete_head
  - net/core/datagram.c:__skb_checksum_complete
```
```
In net/netlink/af_netlink.c (ffffffff8174b075)
Location: include/linux/skbuff.h:1292
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_input.c (ffffffff81758ea9)
Location: include/linux/skbuff.h:1292
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff8175a4e6)
Location: include/linux/skbuff.h:1292
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8175cc10)
Location: include/linux/skbuff.h:1292
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/arp.c (ffffffff8178d216)
Location: include/linux/skbuff.h:1292
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff817c76a7)
Location: include/linux/skbuff.h:1292
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff817c8ad3)
Location: include/linux/skbuff.h:1292
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/packet/af_packet.c (ffffffff81806888)
Location: include/linux/skbuff.h:1292
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/8021q/vlan_core.c (ffffffff8180959f)
Location: include/linux/skbuff.h:1292
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8176f2c8)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/datagram.c (ffffffff81774e83)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/core/sock_reuseport.c (ffffffff817a0027)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (ffffffff817b8b9b)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff817c5249)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817c6945)
Location: include/linux/skbuff.h:1393
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817c9a01)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/arp.c (ffffffff817fa7d6)
Location: include/linux/skbuff.h:1393
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff818345a4)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81835d43)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/packet/af_packet.c (ffffffff81877997)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff8187b0af)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8179c7b8)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/datagram.c (ffffffff817a2183)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/core/sock_reuseport.c (ffffffff817ce9f7)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (ffffffff817e864b)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff817f4d59)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817f6445)
Location: include/linux/skbuff.h:1408
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817f9989)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/arp.c (ffffffff8182b6a6)
Location: include/linux/skbuff.h:1408
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81866004)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81867863)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/packet/af_packet.c (ffffffff818ab1a7)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff818af96f)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff817bd73d)
Location: include/linux/skbuff.h:1401
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/datagram.c (ffffffff817bf9e3)
Location: include/linux/skbuff.h:1401
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffff817edeb3)
Location: include/linux/skbuff.h:1401
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (ffffffff81808604)
Location: include/linux/skbuff.h:1401
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff818151ea)
Location: include/linux/skbuff.h:1401
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81816869)
Location: include/linux/skbuff.h:1401
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81819d03)
Location: include/linux/skbuff.h:1401
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/arp.c (ffffffff8184cab6)
Location: include/linux/skbuff.h:1401
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8188a791)
Location: include/linux/skbuff.h:1401
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff8188bff2)
Location: include/linux/skbuff.h:1401
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/packet/af_packet.c (ffffffff818d4019)
Location: include/linux/skbuff.h:1401
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff818d6167)
Location: include/linux/skbuff.h:1401
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81835b56)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff81839593)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffff8186a0f3)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (ffffffff81887473)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff818943ba)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81895a09)
Location: include/linux/skbuff.h:1483
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8189833c)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/arp.c (ffffffff818cc776)
Location: include/linux/skbuff.h:1483
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8190b996)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff8190d2e2)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/packet/af_packet.c (ffffffff81958a69)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff8195bd07)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8187ff86)
Location: include/linux/skbuff.h:1494
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff81883cc1)
Location: include/linux/skbuff.h:1494
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffff818b9dd6)
Location: include/linux/skbuff.h:1494
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (ffffffff818dab0a)
Location: include/linux/skbuff.h:1494
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff818e85d6)
Location: include/linux/skbuff.h:1494
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff818e9c18)
Location: include/linux/skbuff.h:1494
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff818ec65a)
Location: include/linux/skbuff.h:1494
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/arp.c (ffffffff81922c0f)
Location: include/linux/skbuff.h:1494
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8196307d)
Location: include/linux/skbuff.h:1494
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff819646e3)
Location: include/linux/skbuff.h:1494
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/packet/af_packet.c (ffffffff819b2b32)
Location: include/linux/skbuff.h:1494
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff819b550b)
Location: include/linux/skbuff.h:1494
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff818a0bd0)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff818a49b1)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffff818e0b4d)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (ffffffff819073e9)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff81915116)
Location: include/linux/skbuff.h:1563
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81916e35)
Location: include/linux/skbuff.h:1563
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819197ee)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/arp.c (ffffffff81951a0f)
Location: include/linux/skbuff.h:1563
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81998068)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81999092)
Location: include/linux/skbuff.h:1563
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e9a9c)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff819ec7db)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff818eb5e9)
Location: include/linux/skbuff.h:1653
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff818f0142)
Location: include/linux/skbuff.h:1653
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffff8192f1ec)
Location: include/linux/skbuff.h:1653
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (ffffffff819686a1)
Location: include/linux/skbuff.h:1653
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff81977626)
Location: include/linux/skbuff.h:1653
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81978e15)
Location: include/linux/skbuff.h:1653
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8197b9b1)
Location: include/linux/skbuff.h:1653
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/arp.c (ffffffff819b62da)
Location: include/linux/skbuff.h:1653
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a04035)
Location: include/linux/skbuff.h:1653
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81a04f94)
Location: include/linux/skbuff.h:1653
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81a486b0)
Location: include/linux/skbuff.h:1653
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/packet/af_packet.c (ffffffff81a57ce0)
Location: include/linux/skbuff.h:1653
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81a5b97a)
Location: include/linux/skbuff.h:1653
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8191d749)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff81922122)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffff8196145c)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (ffffffff8199f141)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff819adfb6)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819af785)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819b20b7)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp.c (ffffffff819e639f)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffff819ecffa)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a3ac1d)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81a3bb64)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81a7f271)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/packet/af_packet.c (ffffffff81a902bf)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81a925aa)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff819f1f1c)
Location: include/linux/skbuff.h:1674
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff819f5b72)
Location: include/linux/skbuff.h:1674
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffff81a34ab5)
Location: include/linux/skbuff.h:1674
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/netlink/af_netlink.c (ffffffff81a78e4c)
Location: include/linux/skbuff.h:1674
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff81a97e5a)
Location: include/linux/skbuff.h:1674
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81a9960f)
Location: include/linux/skbuff.h:1674
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81a9c950)
Location: include/linux/skbuff.h:1674
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp.c (ffffffff81ad2ecf)
Location: include/linux/skbuff.h:1674
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffff81adaf68)
Location: include/linux/skbuff.h:1674
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81adc9dd)
Location: include/linux/skbuff.h:1674
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_output.c (ffffffff81b30212)
Location: include/linux/skbuff.h:1674
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81b30fe7)
Location: include/linux/skbuff.h:1674
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/netfilter.c (ffffffff81b79f1d)
Location: include/linux/skbuff.h:1674
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b826b9)
Location: include/linux/skbuff.h:1674
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/packet/af_packet.c (ffffffff81b8b87d)
Location: include/linux/skbuff.h:1674
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81b8da5a)
Location: include/linux/skbuff.h:1674
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff819f1f3c)
Location: include/linux/skbuff.h:1695
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff819f5632)
Location: include/linux/skbuff.h:1695
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffff81a36df5)
Location: include/linux/skbuff.h:1695
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/netlink/af_netlink.c (ffffffff81a8167c)
Location: include/linux/skbuff.h:1695
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff81aa1dba)
Location: include/linux/skbuff.h:1695
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa357f)
Location: include/linux/skbuff.h:1695
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81aa67e8)
Location: include/linux/skbuff.h:1695
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp.c (ffffffff81adf30f)
Location: include/linux/skbuff.h:1695
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffff81ae7a28)
Location: include/linux/skbuff.h:1695
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ae971c)
Location: include/linux/skbuff.h:1695
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ecb9)
Location: include/linux/skbuff.h:1695
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81b3fc17)
Location: include/linux/skbuff.h:1695
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/netfilter.c (ffffffff81b88e6d)
Location: include/linux/skbuff.h:1695
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b91d34)
Location: include/linux/skbuff.h:1695
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/packet/af_packet.c (ffffffff81b9acf9)
Location: include/linux/skbuff.h:1695
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81b9d710)
Location: include/linux/skbuff.h:1695
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff819d80c0)
Location: include/linux/skbuff.h:1711
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff819db7d5)
Location: include/linux/skbuff.h:1711
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffff81a1de99)
Location: include/linux/skbuff.h:1711
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/netlink/af_netlink.c (ffffffff81a6a76d)
Location: include/linux/skbuff.h:1711
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff81a8ccea)
Location: include/linux/skbuff.h:1711
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e6ef)
Location: include/linux/skbuff.h:1711
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81a918d1)
Location: include/linux/skbuff.h:1711
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp.c (ffffffff81aca21f)
Location: include/linux/skbuff.h:1711
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffff81ad2ce8)
Location: include/linux/skbuff.h:1711
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ad4ddc)
Location: include/linux/skbuff.h:1711
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_output.c (ffffffff81b2ba59)
Location: include/linux/skbuff.h:1711
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b2da47)
Location: include/linux/skbuff.h:1711
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/netfilter.c (ffffffff81b77c98)
Location: include/linux/skbuff.h:1711
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b80f88)
Location: include/linux/skbuff.h:1711
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/packet/af_packet.c (ffffffff81b8a700)
Location: include/linux/skbuff.h:1711
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81b8c81c)
Location: include/linux/skbuff.h:1711
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81a87f10)
Location: include/linux/skbuff.h:1740
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff81a8ba25)
Location: include/linux/skbuff.h:1740
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffff81ad1929)
Location: include/linux/skbuff.h:1740
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/netlink/af_netlink.c (ffffffff81b23d6d)
Location: include/linux/skbuff.h:1740
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff81b47e22)
Location: include/linux/skbuff.h:1740
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81b498df)
Location: include/linux/skbuff.h:1740
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81b4cca4)
Location: include/linux/skbuff.h:1740
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp.c (ffffffff81b88aff)
Location: include/linux/skbuff.h:1740
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffff81b91938)
Location: include/linux/skbuff.h:1740
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81b93c8c)
Location: include/linux/skbuff.h:1740
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_output.c (ffffffff81bf1baf)
Location: include/linux/skbuff.h:1740
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81bf3c9b)
Location: include/linux/skbuff.h:1740
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/netfilter.c (ffffffff81c427b8)
Location: include/linux/skbuff.h:1740
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/ip6_icmp.c (ffffffff81c4cfa8)
Location: include/linux/skbuff.h:1740
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/packet/af_packet.c (ffffffff81c56810)
Location: include/linux/skbuff.h:1740
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81c58bdc)
Location: include/linux/skbuff.h:1740
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81bfd332)
Location: include/linux/skbuff.h:2091
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff81c012a4)
Location: include/linux/skbuff.h:2091
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffff81c4f5c6)
Location: include/linux/skbuff.h:2091
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (ffffffff81cad590)
Location: include/linux/skbuff.h:2091
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff81cd5092)
Location: include/linux/skbuff.h:2091
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6f0a)
Location: include/linux/skbuff.h:2091
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/ip_output.c (ffffffff81cda3f9)
Location: include/linux/skbuff.h:2091
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp.c (ffffffff81d1a457)
Location: include/linux/skbuff.h:2091
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffff81d22e1c)
Location: include/linux/skbuff.h:2091
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv4/icmp.c (ffffffff81d24b84)
Location: include/linux/skbuff.h:2091
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a5ef)
Location: include/linux/skbuff.h:2091
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81d8c9be)
Location: include/linux/skbuff.h:2091
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/netfilter.c (ffffffff81de1289)
Location: include/linux/skbuff.h:2091
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/ip6_icmp.c (ffffffff81ded460)
Location: include/linux/skbuff.h:2091
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/packet/af_packet.c (ffffffff81df5b96)
Location: include/linux/skbuff.h:2091
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81dfa2e7)
Location: include/linux/skbuff.h:2091
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81dac377)
Location: include/linux/skbuff.h:1949
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff81db05e4)
Location: include/linux/skbuff.h:1949
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffff81e04558)
Location: include/linux/skbuff.h:1949
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (ffffffff81e6ab40)
Location: include/linux/skbuff.h:1949
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff81e95562)
Location: include/linux/skbuff.h:1949
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81e974aa)
Location: include/linux/skbuff.h:1949
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/ip_output.c (ffffffff81e9abb9)
Location: include/linux/skbuff.h:1949
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp.c (ffffffff81ee1147)
Location: include/linux/skbuff.h:1949
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffff81eea31c)
Location: include/linux/skbuff.h:1949
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv4/icmp.c (ffffffff81eec374)
Location: include/linux/skbuff.h:1949
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_output.c (ffffffff81f5857f)
Location: include/linux/skbuff.h:1949
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81f5abce)
Location: include/linux/skbuff.h:1949
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/netfilter.c (ffffffff81fb36e9)
Location: include/linux/skbuff.h:1949
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/ip6_icmp.c (ffffffff81fc1280)
Location: include/linux/skbuff.h:1949
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/packet/af_packet.c (ffffffff81fca116)
Location: include/linux/skbuff.h:1949
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81fcea07)
Location: include/linux/skbuff.h:1949
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81e1c1ea)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff81e20a98)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffff81e76da8)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (ffffffff81ec6fb0)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff81ef3d62)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef5cda)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/ip_output.c (ffffffff81ef955c)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp.c (ffffffff81f40b97)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffff81f49c4c)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv4/icmp.c (ffffffff81f4c164)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_output.c (ffffffff81fb81ac)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81fba97e)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/netfilter.c (ffffffff82013f0c)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/ip6_icmp.c (ffffffff82022200)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/packet/af_packet.c (ffffffff8202ae1a)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff8204a347)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81ed98e7)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff81ede968)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffff81f36d68)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (ffffffff81f8a258)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff81fb7cf2)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9c8a)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/ip_output.c (ffffffff81fbd479)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp.c (ffffffff820067e7)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffff8200fd6c)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv4/icmp.c (ffffffff82012274)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_output.c (ffffffff8208579b)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff82087dae)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/netfilter.c (ffffffff820e3063)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/ip6_icmp.c (ffffffff820f1320)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/packet/af_packet.c (ffffffff820fa91b)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff8211c7b7)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffff800010bb8130)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffff800010bbcbdc)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffff800010c04cd8)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (ffff800010c4c454)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffff800010c5e008)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffff800010c5ffd8)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv4/ip_output.c (ffff800010c63e14)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp.c (ffff800010c9afb0)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffff800010ca2a78)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv6/ip6_output.c (ffff800010cfbcdc)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffff800010cfd130)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv6/netfilter.c (ffff800010d4a504)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/packet/af_packet.c (ffff800010d5dae4)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffff800010d60324)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (c0cd4cd4)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (c0cd8d98)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (c0d1e1a0)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (c0d5d174)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (c0d6d8f0)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (c0d6f7c0)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv4/ip_output.c (c0d723a4)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/arp.c (c0daf8dc)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv6/ip6_output.c (c0e02d6c)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (c0e04298)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/netfilter.c (c0e4bb24)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/packet/af_packet.c (c0e5c634)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (c0e5fe28)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (c000000000c90048)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (c000000000c95c60)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (c000000000ceee98)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (c000000000d4ae00)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (c000000000d60c2c)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (c000000000d62db8)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv4/ip_output.c (c000000000d66054)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp.c (c000000000dacf80)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (c000000000db61d8)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv6/ip6_output.c (c000000000e234e8)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (c000000000e24be0)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/netfilter.c (c000000000e805b4)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/packet/af_packet.c (c000000000e966d4)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (c000000000e9b340)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffe000747a12)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffe00074b41e)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffe00078393c)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (ffffffe0007b9766)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffe0007c6bbc)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c808e)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffe0007ca68c)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp.c (ffffffe0007f88de)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffe0007fea1e)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffe00084664a)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffe0008474ea)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/netfilter.c (ffffffe0008839f2)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/packet/af_packet.c (ffffffe0008938a2)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffe00089579c)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff818bd749)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff818c2122)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffff8190142c)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (ffffffff8193efb1)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff8194de26)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff8194f5f5)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81951f27)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp.c (ffffffff8198620f)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffff8198cdb6)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819da2ad)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff819db1f4)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81a1e901)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/packet/af_packet.c (ffffffff81a2f94f)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81a31c3a)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81877689)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff8187c062)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffff818bb25c)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (ffffffff818f8ab1)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff81907916)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819090e5)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8190ba17)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp.c (ffffffff8193fccf)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffff81946876)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8199706d)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81997fb4)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff819db6c1)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/packet/af_packet.c (ffffffff819ecb3f)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff819eee2a)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8190e749)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff81913122)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffff8195245c)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (ffffffff81990141)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff819b85f6)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9dc5)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819bc6f7)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp.c (ffffffff819f09df)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffff819f763a)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a44d2d)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81a45c74)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81a89381)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/packet/af_packet.c (ffffffff81a9b4ff)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81a9d7ea)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8192f879)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff819342a2)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/sock_reuseport.c (ffffffff81973ea7)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netlink/af_netlink.c (ffffffff819b2a10)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
```
```
In net/ipv4/ip_input.c (ffffffff819c1e56)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819c3805)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819c6007)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp.c (ffffffff819fbfff)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffff81a0185f)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a509ed)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81a5194c)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81a95fe1)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/packet/af_packet.c (ffffffff81aa5cff)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81aa99ea)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
</ul>

## Differences

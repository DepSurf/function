# Function: <code>skb_checksum_start_offset</code>

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
In drivers/net/tun.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/core/dev.c (ffffffff81718cee)
Location: include/linux/skbuff.h:2078
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/ipv6/ip6_checksum.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/ipv6/mcast_snoop.c (0)
Location: include/linux/skbuff.h:2078
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/skbuff.h:2078
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
In drivers/net/tun.c (ffffffff8164e8fa)
Location: include/linux/skbuff.h:2208
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81651d82)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:start_xmit
```
```
In net/core/skbuff.c (ffffffff81771ece)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/dev.c (ffffffff8178074b)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/core/dev.c:__skb_csum_offload_chk
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8179da04)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff817e0066)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eb948)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff817f1133)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff817f76d0)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/udp_offload.c (ffffffff817f8f20)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff817fc988)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81806203)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff818130cb)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff818359c7)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff818530ae)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff8185396e)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff818570fc)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818604be)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81866e7a)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (ffffffff818719d3)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81872c44)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818739bf)
Location: include/linux/skbuff.h:2208
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818787ce)
Location: include/linux/skbuff.h:2208
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
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816805fc)
Location: include/linux/skbuff.h:2225
Inline: True
```
```
In net/core/skbuff.c (ffffffff8179efc6)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/dev.c (ffffffff817adeee)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff817cb50e)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff81810437)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c2b8)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81821ec3)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff818285db)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/udp_offload.c (ffffffff81829df0)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff8182d8ed)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81837294)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff818445db)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff818674f7)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff81884dae)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff8188567e)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81888efc)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8189244e)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81895027)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff8189957a)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a44bd)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_checksum.c (ffffffff818a5f33)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818a7264)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a803f)
Location: include/linux/skbuff.h:2225
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818ad020)
Location: include/linux/skbuff.h:2225
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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (0)
Location: include/linux/skbuff.h:2274
Inline: True
```
```
In net/core/skbuff.c (ffffffff817bc720)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/dev.c (ffffffff817caa7e)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff817eace5)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff8183035f)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183cbf3)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81842b62)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff818499dd)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_set_dev_scratch
```
```
In net/ipv4/udp_offload.c (ffffffff8184af61)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff8184ed93)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81858534)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff81865e67)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff8188bc86)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff818aa593)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff818aba50)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff818af5c0)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8bda)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818bb39f)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff818bf661)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818cabe2)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_checksum.c (ffffffff818cc906)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818cdcf0)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ce84c)
Location: include/linux/skbuff.h:2274
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d4878)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (0)
Location: include/linux/skbuff.h:2361
Inline: True
```
```
In net/core/skbuff.c (ffffffff81836df0)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/dev.c (ffffffff818460ee)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81867795)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff818af946)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc2f9)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff818c24c2)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff818c952c)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_set_dev_scratch
```
```
In net/ipv4/udp_offload.c (ffffffff818cabc1)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff818ceb19)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff818d8404)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff818e5f99)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff8190cf71)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff8192d0a3)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff8192e610)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819322d6)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193ba95)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193e3b5)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81942731)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e315)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff8194f963)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff819516b9)
Location: include/linux/skbuff.h:2361
Inline: True
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81952af0)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819536fc)
Location: include/linux/skbuff.h:2361
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819592e4)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In drivers/net/tun.c (ffffffff817401e0)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/core/skbuff.c (ffffffff81880f3a)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/dev.c (ffffffff8188f59e)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818b57f8)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff81905218)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8191201a)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff8191810a)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff8191f83b)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_set_dev_scratch
```
```
In net/ipv4/udp_offload.c (ffffffff81920afb)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81924ee6)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff8192ed72)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff8193c7c3)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff8196435c)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff819869a6)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff819875a2)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff8198ada5)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8199501e)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819972ed)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff8199b591)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a72c1)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff819a8919)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff819aad42)
Location: include/linux/skbuff.h:2373
Inline: True
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819ac095)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad10b)
Location: include/linux/skbuff.h:2373
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819af266)
Location: include/linux/skbuff.h:2373
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
In drivers/net/tun.c (ffffffff81764213)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/core/skbuff.c (ffffffff818a1dce)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/dev.c (ffffffff818aedbb)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818d72d8)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff81933415)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819407e3)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff8194685b)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff8194e4d3)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_set_dev_scratch
```
```
In net/ipv4/udp_offload.c (ffffffff8194fea3)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81953ce7)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff8195e1c9)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff8196c4a4)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff81999c89)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819bd2b2)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff819bdbaf)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c16fd)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb901)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cdbcc)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff819d1f69)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dde18)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff819df450)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e186c)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e2c76)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3ab8)
Location: include/linux/skbuff.h:2451
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e5c2a)
Location: include/linux/skbuff.h:2451
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
In drivers/net/tun.c (ffffffff817a1f0b)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/core/skbuff.c (ffffffff818eca4c)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/dev.c (ffffffff818fbd8b)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81924e37)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff81996d14)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4d25)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff819aaebe)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff819b2c9c)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_set_dev_scratch
```
```
In net/ipv4/udp_offload.c (ffffffff819b475a)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff819b85f2)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff819c356d)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff819d3208)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff81a05c60)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a2bd4a)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a2c695)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a304c7)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a330)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c223)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a40d5a)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4ca12)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e034)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a5062b)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a519d8)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a52826)
Location: include/linux/skbuff.h:2537
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a5568c)
Location: include/linux/skbuff.h:2537
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
In drivers/net/tun.c (ffffffff817c2bdb)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/core/skbuff.c (ffffffff8191eb78)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/dev.c (ffffffff8192e32b)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81957267)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff819cd894)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dba25)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1b8e)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff819e9a3f)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff819eb48a)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff819ef2f2)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff819fa10d)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff81a09d78)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c7cc)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a628ad)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a631d5)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a67017)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70ed1)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a72ea3)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a779da)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a835e2)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a84c61)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a8724b)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a885d8)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a89406)
Location: include/linux/skbuff.h:2551
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a8c75c)
Location: include/linux/skbuff.h:2551
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
In drivers/net/tun.c (ffffffff8188ac18)
Location: include/linux/skbuff.h:2574
Inline: True
```
```
In net/core/skbuff.c (ffffffff819f13f3)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/dev.c (ffffffff81a07d81)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a2f875)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff81ab99ba)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8b0f)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81acf1db)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81ad7a03)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ad916e)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81add244)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81ae8ac8)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff81afa540)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff81b31e15)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b5b170)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b5c125)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5fa29)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a762)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d329)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b71c72)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e385)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81b7fc9a)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b823ed)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b83b4e)
Location: include/linux/skbuff.h:2574
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b84870)
Location: include/linux/skbuff.h:2574
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b87b2c)
Location: include/linux/skbuff.h:2574
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
In drivers/net/tun.c (ffffffff81898e24)
Location: include/linux/skbuff.h:2600
Inline: True
```
```
In net/core/skbuff.c (ffffffff819f138a)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff81a09465)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a31b85)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff81ac4dc2)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4aaf)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81adb1e1)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81ae4053)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5b85)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81ae9f94)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81af59cd)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff81b07ce9)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff81b40a15)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b69981)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b6a815)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b6e1c9)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b791b4)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b7bdd1)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b809a6)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d39c)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81b8efca)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b91ae1)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b93200)
Location: include/linux/skbuff.h:2600
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b941d0)
Location: include/linux/skbuff.h:2600
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b9760c)
Location: include/linux/skbuff.h:2600
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
In drivers/net/tun.c (ffffffff8187b550)
Location: include/linux/skbuff.h:2616
Inline: True
```
```
In net/core/skbuff.c (ffffffff819d6633)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff819efdd1)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81a189f9)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff81aafeae)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abfb63)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac6234)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81acf24a)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0e75)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81ad56fb)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81ae1134)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff81af34f5)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e2af)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b57c8d)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b58db5)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5c5bb)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67cee)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a8bc)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f5c4)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c24c)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81b7e00a)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b80d30)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b8229b)
Location: include/linux/skbuff.h:2616
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b832de)
Location: include/linux/skbuff.h:2616
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b86615)
Location: include/linux/skbuff.h:2616
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
In drivers/net/tun.c (ffffffff8190c900)
Location: include/linux/skbuff.h:2645
Inline: True
```
```
In net/core/skbuff.c (ffffffff81a86c83)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff81aa120a)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81ac9ee9)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff81b6ccdd)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d6d6)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81b84a44)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81b8dc76)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_read_sock
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f892)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81b945f2)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81ba07d4)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff81bb3a05)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff81bf45a5)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81c1f244)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81c2036d)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81c23d0a)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f93d)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81c3271c)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81c37681)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c4714c)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81c48e7a)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4bff7)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff81c4cd50)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e34b)
Location: include/linux/skbuff.h:2645
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f3ae)
Location: include/linux/skbuff.h:2645
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c529d5)
Location: include/linux/skbuff.h:2645
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
In drivers/net/tun.c (ffffffff81a6053f)
Location: include/linux/skbuff.h:3014
Inline: True
```
```
In net/core/skbuff.c (ffffffff81bfc3d7)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff81c190b2)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81c46a4c)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff81cfc174)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d68e)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81d152a2)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81d1ed9c)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_read_sock
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81d20b92)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81d25e9e)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81d32cc9)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff81d4722a)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d2d2)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81dbbad1)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81dbd0d4)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81dc0c3b)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dccdb9)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81dcff0b)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81dd5216)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de64b7)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81de858a)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81debd12)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff81ded290)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81deebf2)
Location: include/linux/skbuff.h:3014
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81defdf9)
Location: include/linux/skbuff.h:3014
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df59b4)
Location: include/linux/skbuff.h:3014
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
In drivers/net/tun.c (ffffffff81bebbeb)
Location: include/linux/skbuff.h:2908
Inline: True
```
```
In net/core/skbuff.c (ffffffff81dab2a7)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff81dca088)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81dfaf44)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff81ec0cf4)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed3043)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81edb482)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81ee5e9d)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7e0c)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81eed6f6)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81efaf59)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff81f10273)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b38c)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81f8bbc4)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81f8d0f4)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81f91317)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9dec6)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81fa1265)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81fa691f)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb919d)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb537)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbf96c)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff81fc10a0)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2c42)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc3f09)
Location: include/linux/skbuff.h:2908
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc985f)
Location: include/linux/skbuff.h:2908
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
In drivers/net/tun.c (ffffffff81c44090)
Location: include/linux/skbuff.h:2962
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81c50c16)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:xmit_skb
```
```
In net/core/skbuff.c (ffffffff81e1ada7)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff81e3abff)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81e6c145)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff81f1f264)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31d44)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81f3a542)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81f4569a)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81f47695)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81f4d0b9)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81f5a9e8)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff81f6ff63)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb156)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81fec342)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81fed8c4)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81ff1c2c)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe93a)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff82001b67)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff82007170)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820198fd)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff8201bbf7)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820208fc)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff82022033)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff82023bd1)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff82024f29)
Location: include/linux/skbuff.h:2962
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202be40)
Location: include/linux/skbuff.h:2962
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In drivers/net/netkit.c (ffffffff81ce546c)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_xmit
```
```
In drivers/net/tun.c (ffffffff81cf9950)
Location: include/linux/skbuff.h:2969
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81d06c56)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:xmit_skb
```
```
In net/core/skbuff.c (ffffffff81ed8447)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff81ef8fa3)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81f2ba35)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff81fe391f)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7d8b)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff82000632)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff8200b7d5)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8200d7d5)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff820131c9)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff82020f28)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff82036693)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff82088566)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff820b9f55)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff820bb4d4)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff820bf82b)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd66f)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff820d096a)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff820d5fd0)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e88cd)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff820eabb7)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820efa2c)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff820f1153)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff820f2d31)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f4209)
Location: include/linux/skbuff.h:2969
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fb8f1)
Location: include/linux/skbuff.h:2969
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In drivers/net/tun.c (ffff8000109dd738)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/core/skbuff.c (ffff800010bb9314)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/dev.c (ffff800010bc9918)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffff800010c0098c)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffff800010c80204)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ea78)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffff800010c95ba4)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffff800010c9f3c8)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffff800010ca0fe4)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffff800010ca4f5c)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffff800010cb1944)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffff800010cc3114)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffff800010cfda24)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffff800010d27900)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffff800010d28508)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffff800010d2ce9c)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39080)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffff800010d3b984)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffff800010d41034)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f328)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffff800010d50cd8)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffff800010d53894)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffff800010d55178)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffff800010d56284)
Location: include/linux/skbuff.h:2551
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d57f00)
Location: include/linux/skbuff.h:2551
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
In drivers/net/tun.c (c0ac5f2c)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/core/skbuff.c (c0cd5dc8)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/dev.c (c0ce7b50)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (c0d125a0)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (c0d8f574)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (c0d9da08)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (c0da42e8)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (c0dac580)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/udp_offload.c (c0dad530)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (c0db1860)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (c0dbd52c)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (c0dce930)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (c0e0510c)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (c0e2c4ac)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2d5bc)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c0e30b9c)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c0e3bc5c)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (c0e3df1c)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (c0e43a48)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (c0e50084)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (c0e51828)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (c0e54184)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (c0e55720)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (c0e567f8)
Location: include/linux/skbuff.h:2551
Inline: True
```
```
In net/packet/af_packet.c (c0e59e90)
Location: include/linux/skbuff.h:2551
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
In drivers/net/tun.c (c000000000aa3f78)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/core/skbuff.c (c000000000c91910)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/dev.c (c000000000ca75e0)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (c000000000ce3b34)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (c000000000d8af64)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d680)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (c000000000da6f10)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (c000000000db17c0)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (c000000000db3f20)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (c000000000db8d20)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (c000000000dc8790)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (c000000000dde810)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (c000000000e25bf0)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (c000000000e58920)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (c000000000e59890)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c000000000e5e860)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c660)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (c000000000e6f254)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (c000000000e758d0)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86d00)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (c000000000e88b80)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (c000000000e8c260)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (c000000000e8dee0)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f370)
Location: include/linux/skbuff.h:2551
Inline: True
```
```
In net/packet/af_packet.c (c000000000e93078)
Location: include/linux/skbuff.h:2551
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
In drivers/net/tun.c (ffffffe00062890e)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/core/skbuff.c (ffffffe0007488bc)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/dev.c (ffffffe000756fbc)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffe00077a6ac)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffe0007e2404)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eee8c)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f4d8c)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffe0007fb976)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd600)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffe000800952)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffe00080a2e0)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffe000818508)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffe000847ee6)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffe000869286)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffe000869d84)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffe00086cfbe)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000876484)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffe000878278)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffe00087c796)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000887e48)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffe000889018)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b560)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffe00088c9b8)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088daa6)
Location: include/linux/skbuff.h:2551
Inline: True
```
```
In net/packet/af_packet.c (ffffffe00088fb78)
Location: include/linux/skbuff.h:2551
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
In drivers/net/tun.c (ffffffff817876ab)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/core/skbuff.c (ffffffff818beb78)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/dev.c (ffffffff818ce32b)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818f7237)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff8196d704)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b895)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff819819fe)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff819898af)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8198b2fa)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff8198f092)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81999ead)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff819a9b18)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff819dbe5c)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a01f3d)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a02865)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a066a7)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10561)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a12533)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a1706a)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a22c72)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a242f1)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a268db)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a27c68)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28a96)
Location: include/linux/skbuff.h:2551
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2bdec)
Location: include/linux/skbuff.h:2551
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
In drivers/net/tun.c (ffffffff81766ffb)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/vxlan.c (ffffffff8176bf36)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_build_skb
  - drivers/net/vxlan.c:vxlan_build_skb
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/core/skbuff.c (ffffffff81878ab8)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/dev.c (ffffffff8188844b)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818b1067)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff819271f4)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81935355)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff8193b4be)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff8194336f)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81944dba)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81948b52)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff8195396d)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff819635d8)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967ed8)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81998c1c)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819becfd)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff819bf625)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c3467)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd321)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cf2f3)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff819d3e2a)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dfa32)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff819e10b1)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e369b)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e4a28)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5c86)
Location: include/linux/skbuff.h:2551
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e8fdc)
Location: include/linux/skbuff.h:2551
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
In drivers/net/tun.c (ffffffff817b7a5b)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/core/skbuff.c (ffffffff8190fb78)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/dev.c (ffffffff8191f32b)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81948267)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff81999f0a)
Location: include/linux/skbuff.h:2551
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819d7ed4)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e6065)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff819ec1ce)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff819f407f)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff819f5aca)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff819f9932)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81a0474d)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff81a143b8)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff81a468dc)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a6c9bd)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a6d2e5)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a71127)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7afe1)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a7cfb3)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a81aea)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d6f2)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ed71)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9248b)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a93818)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a94646)
Location: include/linux/skbuff.h:2551
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a9799c)
Location: include/linux/skbuff.h:2551
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
In drivers/net/tun.c (ffffffff817d2133)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In net/core/skbuff.c (ffffffff81930ca8)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/dev.c (ffffffff8194108b)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81969b77)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_input.c (ffffffff819e1b0d)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819efd25)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff819f607e)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff819fe23f)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff819ffcca)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81a03c22)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81a0eccd)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff81a1edba)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff81a5260c)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a78ff5)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a79905)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a7d737)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87821)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a89803)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a8e3ea)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a3e2)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bae1)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9e53b)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9f968)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa07a6)
Location: include/linux/skbuff.h:2551
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa42bc)
Location: include/linux/skbuff.h:2551
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
</details>
</li>
</ul>

## Differences

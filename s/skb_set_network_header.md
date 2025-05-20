# Function: <code>skb_set_network_header</code>

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
In net/core/skbuff.c (ffffffff81709b5f)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff8171b367)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/ip_output.c (ffffffff8175db01)
Location: include/linux/skbuff.h:2023
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff8178aeaa)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff8178f1f1)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81793cfb)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff817a51cb)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff817a7334)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff817c6396)
Location: include/linux/skbuff.h:2023
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff817e8854)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81800cc0)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/packet/af_packet.c (ffffffff8180811f)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
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
In net/core/skbuff.c (ffffffff81771ebf)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81783bf4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/ip_output.c (ffffffff817c8f9c)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff817f8780)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff817fc851)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff8180145f)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81812bdf)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81815024)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81833773)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81857071)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81872450)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/packet/af_packet.c (ffffffff81879b61)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
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
In net/core/skbuff.c (ffffffff8179efb7)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff817b118d)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/ip_output.c (ffffffff817f8b34)
Location: include/linux/skbuff.h:2170
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81829631)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff8182d7b4)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff8183226f)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff818440ed)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff818467e4)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81865209)
Location: include/linux/skbuff.h:2170
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81888e71)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6a40)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/packet/af_packet.c (ffffffff818ae262)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
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
In net/core/skbuff.c (ffffffff817bc6fc)
Location: include/linux/skbuff.h:2209
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff817d156a)
Location: include/linux/skbuff.h:2209
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/ip_output.c (ffffffff81818eb5)
Location: include/linux/skbuff.h:2209
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff8184a63f)
Location: include/linux/skbuff.h:2209
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff8184ed0c)
Location: include/linux/skbuff.h:2209
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81854d44)
Location: include/linux/skbuff.h:2209
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81865a3f)
Location: include/linux/skbuff.h:2209
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81869511)
Location: include/linux/skbuff.h:2209
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81888393)
Location: include/linux/skbuff.h:2209
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff818af557)
Location: include/linux/skbuff.h:2209
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd4b7)
Location: include/linux/skbuff.h:2209
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/packet/af_packet.c (ffffffff818d4bca)
Location: include/linux/skbuff.h:2209
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
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
In net/core/skbuff.c (ffffffff81836dcc)
Location: include/linux/skbuff.h:2296
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff8184b67e)
Location: include/linux/skbuff.h:2296
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/ip_output.c (ffffffff81898fec)
Location: include/linux/skbuff.h:2296
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff818ca2e4)
Location: include/linux/skbuff.h:2296
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff818cea92)
Location: include/linux/skbuff.h:2296
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff818d4be4)
Location: include/linux/skbuff.h:2296
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff818e5ba4)
Location: include/linux/skbuff.h:2296
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff818e9b61)
Location: include/linux/skbuff.h:2296
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff8190a901)
Location: include/linux/skbuff.h:2296
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff8193226d)
Location: include/linux/skbuff.h:2296
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff819522a7)
Location: include/linux/skbuff.h:2296
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/packet/af_packet.c (ffffffff81959649)
Location: include/linux/skbuff.h:2296
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
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
In net/core/skbuff.c (ffffffff81880f0d)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff818959d5)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/ip_output.c (ffffffff818ed169)
Location: include/linux/skbuff.h:2307
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81920610)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81924e60)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff8192b154)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8193c3ac)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81940234)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81961d3b)
Location: include/linux/skbuff.h:2307
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff8198abb3)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff819ab817)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (ffffffff818a1da4)
Location: include/linux/skbuff.h:2385
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff818b76b9)
Location: include/linux/skbuff.h:2385
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/ip_output.c (ffffffff8191aa74)
Location: include/linux/skbuff.h:2385
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194db7d)
Location: include/linux/skbuff.h:2385
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff8194f446)
Location: include/linux/skbuff.h:2385
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81953c72)
Location: include/linux/skbuff.h:2385
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81958dce)
Location: include/linux/skbuff.h:2385
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8196c0a4)
Location: include/linux/skbuff.h:2385
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff819700b4)
Location: include/linux/skbuff.h:2385
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81996741)
Location: include/linux/skbuff.h:2385
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bc5bf)
Location: include/linux/skbuff.h:2385
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff819c1481)
Location: include/linux/skbuff.h:2385
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff819e2330)
Location: include/linux/skbuff.h:2385
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (ffffffff818ec9d5)
Location: include/linux/skbuff.h:2473
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff819034ef)
Location: include/linux/skbuff.h:2473
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff8192813d)
Location: include/linux/skbuff.h:2473
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/ip_output.c (ffffffff8197cc93)
Location: include/linux/skbuff.h:2473
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b2396)
Location: include/linux/skbuff.h:2473
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819b3c7c)
Location: include/linux/skbuff.h:2473
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff819b856c)
Location: include/linux/skbuff.h:2473
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff819bd880)
Location: include/linux/skbuff.h:2473
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819d2df4)
Location: include/linux/skbuff.h:2473
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff819d9970)
Location: include/linux/skbuff.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff819f5e04)
Location: include/linux/skbuff.h:2473
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a02c5e)
Location: include/linux/skbuff.h:2473
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a2b0ed)
Location: include/linux/skbuff.h:2473
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a3025c)
Location: include/linux/skbuff.h:2473
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81a50ff3)
Location: include/linux/skbuff.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (ffffffff8191eb06)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff8193629f)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff8195a76d)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/ip_output.c (ffffffff819b3633)
Location: include/linux/skbuff.h:2487
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e9136)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819ea9ac)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff819ef26c)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff819f4490)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a09962)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a107d0)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2ca84)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a39833)
Location: include/linux/skbuff.h:2487
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a61c4d)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a66dac)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87c13)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (ffffffff819f1399)
Location: include/linux/skbuff.h:2510
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81a0aebe)
Location: include/linux/skbuff.h:2510
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff81a2c30c)
Location: include/linux/skbuff.h:2510
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/ipv4/ip_output.c (ffffffff81a9d6cf)
Location: include/linux/skbuff.h:2510
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/udp.c (ffffffff81ad3c4d)
Location: include/linux/skbuff.h:2510
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err_encap
```
```
In net/ipv4/udp_offload.c (ffffffff81ad87d2)
Location: include/linux/skbuff.h:2510
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81add1b6)
Location: include/linux/skbuff.h:2510
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81ae2d51)
Location: include/linux/skbuff.h:2510
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81afa0d2)
Location: include/linux/skbuff.h:2510
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81b02203)
Location: include/linux/skbuff.h:2510
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1f65c)
Location: include/linux/skbuff.h:2510
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f0ab)
Location: include/linux/skbuff.h:2510
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b5a409)
Location: include/linux/skbuff.h:2510
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err_encap
```
```
In net/ipv6/icmp.c (ffffffff81b5f831)
Location: include/linux/skbuff.h:2510
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81b830c3)
Location: include/linux/skbuff.h:2510
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (ffffffff819f1329)
Location: include/linux/skbuff.h:2531
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81a0c107)
Location: include/linux/skbuff.h:2531
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff81a2d88c)
Location: include/linux/skbuff.h:2531
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/ipv4/ip_output.c (ffffffff81aa759f)
Location: include/linux/skbuff.h:2531
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/udp.c (ffffffff81adfd5d)
Location: include/linux/skbuff.h:2531
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err_encap
```
```
In net/ipv4/udp_offload.c (ffffffff81ae4d05)
Location: include/linux/skbuff.h:2531
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81ae9f17)
Location: include/linux/skbuff.h:2531
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81aefc1e)
Location: include/linux/skbuff.h:2531
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81b07896)
Location: include/linux/skbuff.h:2531
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81b105a3)
Location: include/linux/skbuff.h:2531
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2df2c)
Location: include/linux/skbuff.h:2531
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
```
```
In net/ipv6/ip6_output.c (ffffffff81b3db08)
Location: include/linux/skbuff.h:2531
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b68b09)
Location: include/linux/skbuff.h:2531
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err_encap
```
```
In net/ipv6/icmp.c (ffffffff81b6dfe2)
Location: include/linux/skbuff.h:2531
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81b9276c)
Location: include/linux/skbuff.h:2531
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (ffffffff819d65d2)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff819f22ba)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff81a1511c)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/selftests.c (ffffffff81a3618f)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a92786)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/udp.c (ffffffff81ace9a5)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81acff22)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81ad566a)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81adb367)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81af3033)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81afe1b3)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c066)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81b2afc6)
Location: include/linux/skbuff.h:2547
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b5733d)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81b5c3ab)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81b818c2)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (ffffffff81a86c22)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81aa418a)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff81ac66cc)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/selftests.c (ffffffff81aebe24)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/ip_output.c (ffffffff81b4db8a)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/udp.c (ffffffff81b8d372)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e942)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81b9449c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81b9a717)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81bb3543)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81bbf443)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81be09f2)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm4_prepare_output
```
```
In net/ipv6/ip6_output.c (ffffffff81bf10ec)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81c1e91b)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81c23ae0)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4d902)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (ffffffff81bfc36d)
Location: include/linux/skbuff.h:2945
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/filter.c (ffffffff81c41f5a)
Location: include/linux/skbuff.h:2945
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/gro.c (ffffffff81c54168)
Location: include/linux/skbuff.h:2945
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/selftests.c (ffffffff81c6e7be)
Location: include/linux/skbuff.h:2945
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/ip_output.c (ffffffff81cdb403)
Location: include/linux/skbuff.h:2945
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/udp.c (ffffffff81d1e503)
Location: include/linux/skbuff.h:2945
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81d2009f)
Location: include/linux/skbuff.h:2945
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81d25d22)
Location: include/linux/skbuff.h:2945
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81d2cac4)
Location: include/linux/skbuff.h:2945
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81d46d65)
Location: include/linux/skbuff.h:2945
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81d541d4)
Location: include/linux/skbuff.h:2945
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81d777ed)
Location: include/linux/skbuff.h:2945
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81d89927)
Location: include/linux/skbuff.h:2945
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81dbb15c)
Location: include/linux/skbuff.h:2945
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81dc0a05)
Location: include/linux/skbuff.h:2945
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81dedfe2)
Location: include/linux/skbuff.h:2945
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/packet/af_packet.c (ffffffff81df36c7)
Location: include/linux/skbuff.h:2945
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
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
In net/core/skbuff.c (ffffffff81dab23d)
Location: include/linux/skbuff.h:2837
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/filter.c (ffffffff81df949b)
Location: include/linux/skbuff.h:2837
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/gro.c (ffffffff81e098f0)
Location: include/linux/skbuff.h:2837
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/selftests.c (ffffffff81e264ee)
Location: include/linux/skbuff.h:2837
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/ip_output.c (ffffffff81e9bcb3)
Location: include/linux/skbuff.h:2837
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/udp.c (ffffffff81ee55a3)
Location: include/linux/skbuff.h:2837
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81ee729c)
Location: include/linux/skbuff.h:2837
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81eed4a8)
Location: include/linux/skbuff.h:2837
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81ef438d)
Location: include/linux/skbuff.h:2837
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f105b5)
Location: include/linux/skbuff.h:2837
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f1e3b4)
Location: include/linux/skbuff.h:2837
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81f4407d)
Location: include/linux/skbuff.h:2837
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81f577d8)
Location: include/linux/skbuff.h:2837
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81f8b231)
Location: include/linux/skbuff.h:2837
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81f91194)
Location: include/linux/skbuff.h:2837
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc2590)
Location: include/linux/skbuff.h:2837
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/packet/af_packet.c (ffffffff81fc8497)
Location: include/linux/skbuff.h:2837
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
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
In net/core/skbuff.c (ffffffff81e1ad3d)
Location: include/linux/skbuff.h:2891
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/filter.c (ffffffff81e6ae64)
Location: include/linux/skbuff.h:2891
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/gro.c (ffffffff81e7c0c7)
Location: include/linux/skbuff.h:2891
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/selftests.c (ffffffff81e9ba8e)
Location: include/linux/skbuff.h:2891
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/ip_output.c (ffffffff81efa792)
Location: include/linux/skbuff.h:2891
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/udp.c (ffffffff81f44dcb)
Location: include/linux/skbuff.h:2891
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81f46b3e)
Location: include/linux/skbuff.h:2891
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81f4ce68)
Location: include/linux/skbuff.h:2891
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81f53c84)
Location: include/linux/skbuff.h:2891
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f702a1)
Location: include/linux/skbuff.h:2891
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f7dea4)
Location: include/linux/skbuff.h:2891
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3894)
Location: include/linux/skbuff.h:2891
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81fb72bf)
Location: include/linux/skbuff.h:2891
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81feb8eb)
Location: include/linux/skbuff.h:2891
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81ff1a57)
Location: include/linux/skbuff.h:2891
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff82023510)
Location: include/linux/skbuff.h:2891
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/packet/af_packet.c (ffffffff82028fb7)
Location: include/linux/skbuff.h:2891
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
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
In net/core/skbuff.c (ffffffff81ed83dd)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/filter.c (ffffffff81f29df4)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/gro.c (ffffffff81f3c417)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/selftests.c (ffffffff81f5e1ee)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/ip_output.c (ffffffff81fbe6cf)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/udp.c (ffffffff8200ae1d)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff8200cc7e)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff82012f78)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff8201a044)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff820369d1)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff820446f6)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff82070bc4)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff82084955)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv6/udp.c (ffffffff820b95b6)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff820bf656)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff820f2600)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/packet/af_packet.c (ffffffff820f89f7)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
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
In net/core/skbuff.c (ffff800010bb92cc)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffff800010bd4914)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffff800010bfbe58)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/ip_output.c (ffff800010c62fe8)
Location: include/linux/skbuff.h:2487
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9ea4c)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffff800010ca0680)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffff800010ca50a8)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffff800010caa424)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffff800010cc2d38)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffff800010ccb440)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffff800010ceb708)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffff800010cf97b4)
Location: include/linux/skbuff.h:2487
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d26c88)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffff800010d2cd14)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffff800010d547dc)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (c0cd5d94)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (c0ceeedc)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (c0d16e54)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/ip_output.c (c0d73a2c)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/udp.c (c0dabb34)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (c0dad780)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (c0db19b4)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (c0db6c1c)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (c0dce504)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (c0dd592c)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (c0df35d0)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (c0e00ff0)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
```
```
In net/ipv6/udp.c (c0e2be58)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (c0e30d70)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (c0e54da8)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (c000000000c91884)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (c000000000cb3a18)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (c000000000ce7368)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/ip_output.c (c000000000d67d2c)
Location: include/linux/skbuff.h:2487
Inline: True
```
```
In net/ipv4/udp.c (c000000000db1204)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (c000000000db2e8c)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (c000000000db8dfc)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (c000000000dc04dc)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (c000000000ddeb8c)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (c000000000de80c4)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (c000000000e0f5d4)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (c000000000e2155c)
Location: include/linux/skbuff.h:2487
Inline: True
```
```
In net/ipv6/udp.c (c000000000e579d0)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (c000000000e5e800)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (c000000000e8d2ec)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (ffffffe000748888)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffe00075e6f8)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffe00077e88c)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/ip_output.c (ffffffe0007cb928)
Location: include/linux/skbuff.h:2487
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007fb576)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffe0007fcd3c)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffe0008009de)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffe00080525e)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffe000818188)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffe00081e76c)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffe00083907c)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffe0008454e4)
Location: include/linux/skbuff.h:2487
Inline: True
```
```
In net/ipv6/udp.c (ffffffe000868d2a)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffe00086cf6c)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c148)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (ffffffff818beb06)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff818d626f)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff818fa73d)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/ip_output.c (ffffffff819534a3)
Location: include/linux/skbuff.h:2487
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81988fa6)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff8198a81c)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff8198f00c)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81994230)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819a9702)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff819b01e0)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc114)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff819d8ec3)
Location: include/linux/skbuff.h:2487
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a012dd)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a0643c)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81a272a3)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (ffffffff81878a46)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff818900af)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff818b456d)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/ip_output.c (ffffffff8190cf93)
Location: include/linux/skbuff.h:2487
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81942a66)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819442dc)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81948acc)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff8194dcf0)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819631c2)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8196c810)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81988f04)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81995c83)
Location: include/linux/skbuff.h:2487
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819be09d)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff819c31fc)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff819e4063)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (ffffffff8190fb06)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff8192729f)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff8194b76d)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/ip_output.c (ffffffff819bdc73)
Location: include/linux/skbuff.h:2487
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f3776)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819f4fec)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff819f98ac)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff819fead0)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a13fa2)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a1aa80)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81a36b94)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a43943)
Location: include/linux/skbuff.h:2487
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a6bd5d)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a70ebc)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81a92e53)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (ffffffff81930c36)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81948908)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff8196d07d)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/ip_output.c (ffffffff819c7583)
Location: include/linux/skbuff.h:2487
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fd936)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819ff1f3)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81a03b9c)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81a0a8c1)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a1e992)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a258e0)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42524)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a4f5e3)
Location: include/linux/skbuff.h:2487
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a7836d)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a7d4cc)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9efad)
Location: include/linux/skbuff.h:2487
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
</ul>

## Differences

# Function: <code>skb_set_transport_header</code>

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
In drivers/net/tun.c (ffffffff815eec50)
Location: include/linux/skbuff.h:2006
Inline: True
```
```
In net/core/skbuff.c (ffffffff81705a7a)
Location: include/linux/skbuff.h:2006
Inline: True
```
```
In net/core/dev.c (ffffffff8171c736)
Location: include/linux/skbuff.h:2006
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff8178b02d)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81793d1d)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81797ec0)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/mcast.c (ffffffff817ea1be)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6_offload.c (ffffffff81800cd8)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818027b8)
Location: include/linux/skbuff.h:2006
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8181739f)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff8164d840)
Location: include/linux/skbuff.h:2136
Inline: True
```
```
In net/core/skbuff.c (ffffffff8176c74a)
Location: include/linux/skbuff.h:2136
Inline: True
```
```
In net/core/dev.c (ffffffff8178511e)
Location: include/linux/skbuff.h:2136
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/udp_offload.c (ffffffff817f8973)
Location: include/linux/skbuff.h:2136
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8180147d)
Location: include/linux/skbuff.h:2136
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81805864)
Location: include/linux/skbuff.h:2136
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff81812be3)
Location: include/linux/skbuff.h:2136
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/mcast.c (ffffffff818583f0)
Location: include/linux/skbuff.h:2136
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6_offload.c (ffffffff81872468)
Location: include/linux/skbuff.h:2136
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81873ab7)
Location: include/linux/skbuff.h:2136
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81879f82)
Location: include/linux/skbuff.h:2136
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff8167f55c)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/skbuff.c (ffffffff8179991a)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/dev.c (ffffffff817b272e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81829857)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8183228d)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81836cb4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff81844105)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/mcast.c (ffffffff8188a7f0)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a410c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6a58)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a8137)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818ae76c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff8169478c)
Location: include/linux/skbuff.h:2192
Inline: True
```
```
In net/core/skbuff.c (ffffffff817b876a)
Location: include/linux/skbuff.h:2192
Inline: True
```
```
In net/core/dev.c (ffffffff817cff00)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8184a888)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81854d62)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81857d11)
Location: include/linux/skbuff.h:2192
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff81865a29)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/mcast.c (ffffffff818b1874)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca707)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd4ce)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ce977)
Location: include/linux/skbuff.h:2192
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d5099)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff816fe7fc)
Location: include/linux/skbuff.h:2279
Inline: True
```
```
In net/core/skbuff.c (ffffffff818310fa)
Location: include/linux/skbuff.h:2279
Inline: True
```
```
In net/core/dev.c (ffffffff81849850)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/udp_offload.c (ffffffff818ca509)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff818d4c02)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff818d74d1)
Location: include/linux/skbuff.h:2279
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff818e5b6a)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/mcast.c (ffffffff81933bf4)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e436)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff8194f400)
Location: include/linux/skbuff.h:2279
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff819522be)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81953827)
Location: include/linux/skbuff.h:2279
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81959b22)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff8173f1e2)
Location: include/linux/skbuff.h:2290
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff8187b50c)
Location: include/linux/skbuff.h:2290
Inline: True
```
```
In net/core/dev.c (ffffffff8189392f)
Location: include/linux/skbuff.h:2290
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff818b221f)
Location: include/linux/skbuff.h:2290
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/ipv4/route.c (ffffffff818e6b8a)
Location: include/linux/skbuff.h:2290
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffff81920855)
Location: include/linux/skbuff.h:2290
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8192b154)
Location: include/linux/skbuff.h:2290
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff8192de21)
Location: include/linux/skbuff.h:2290
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff8193c3b4)
Location: include/linux/skbuff.h:2290
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/mcast.c (ffffffff8198c780)
Location: include/linux/skbuff.h:2290
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7727)
Location: include/linux/skbuff.h:2290
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff819a90d0)
Location: include/linux/skbuff.h:2290
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff819ab83c)
Location: include/linux/skbuff.h:2290
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad249)
Location: include/linux/skbuff.h:2290
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819b0897)
Location: include/linux/skbuff.h:2290
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff817639fb)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff8189c34e)
Location: include/linux/skbuff.h:2368
Inline: True
```
```
In net/core/dev.c (ffffffff818b4351)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff818d6d89)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/ipv4/route.c (ffffffff81913a55)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp.c (ffffffff8194dae9)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff8194f683)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81958dce)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff8195d6e2)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff8196c0ac)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff819bc498)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff819c2ffd)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de294)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff819df9bd)
Location: include/linux/skbuff.h:2368
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff819e2358)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3bf0)
Location: include/linux/skbuff.h:2368
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e8269)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff817a1789)
Location: include/linux/skbuff.h:2456
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff818e6bcf)
Location: include/linux/skbuff.h:2456
Inline: True
```
```
In net/core/dev.c (ffffffff81900c51)
Location: include/linux/skbuff.h:2456
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81924604)
Location: include/linux/skbuff.h:2456
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/route.c (ffffffff81976105)
Location: include/linux/skbuff.h:2456
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp.c (ffffffff819b2306)
Location: include/linux/skbuff.h:2456
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819b3eb9)
Location: include/linux/skbuff.h:2456
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819bd88b)
Location: include/linux/skbuff.h:2456
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff819c2356)
Location: include/linux/skbuff.h:2456
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff819d2dfc)
Location: include/linux/skbuff.h:2456
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff81a2afcc)
Location: include/linux/skbuff.h:2456
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81a31e43)
Location: include/linux/skbuff.h:2456
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4cdf4)
Location: include/linux/skbuff.h:2456
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e5e5)
Location: include/linux/skbuff.h:2456
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81a51012)
Location: include/linux/skbuff.h:2456
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a529e0)
Location: include/linux/skbuff.h:2456
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a54dac)
Location: include/linux/skbuff.h:2456
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff817c6749)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81918d5f)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/core/dev.c (ffffffff81932f81)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81956914)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/route.c (ffffffff819acb15)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp.c (ffffffff819e90a6)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819eabe9)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819f449b)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff819f8ef6)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff81a0996a)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff81a61b2c)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81a68993)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a839c4)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81a853a3)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87c32)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a895c0)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a8b99c)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff8188e037)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff819e9e4f)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_partial_csum_set
```
```
In net/core/dev.c (ffffffff81a07daa)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81a2f586)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/ipv4/route.c (ffffffff81a92362)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/udp.c (ffffffff81ad3b95)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err_encap
  - net/ipv4/udp.c:__udp4_lib_err_encap
```
```
In net/ipv4/udp_offload.c (ffffffff81ad87e6)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ae2d5c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81ae68ed)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_iphdr
```
```
In net/ipv4/gre_offload.c (ffffffff81afa0da)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff81b5a317)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err_encap
  - net/ipv6/udp.c:__udp6_lib_err_encap
```
```
In net/ipv6/mcast.c (ffffffff81b60cb8)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/exthdrs.c (ffffffff81b6cdc3)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e7a4)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81b80570)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/ip6_offload.c (ffffffff81b830e2)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b84b70)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b85ddf)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
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
In drivers/net/tun.c (ffffffff8189c553)
Location: include/linux/skbuff.h:2514
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff819e9bef)
Location: include/linux/skbuff.h:2514
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_partial_csum_set
```
```
In net/core/dev.c (ffffffff81a0948e)
Location: include/linux/skbuff.h:2514
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81a31896)
Location: include/linux/skbuff.h:2514
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/ipv4/route.c (ffffffff81a9c202)
Location: include/linux/skbuff.h:2514
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/udp.c (ffffffff81adfca5)
Location: include/linux/skbuff.h:2514
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err_encap
  - net/ipv4/udp.c:__udp4_lib_err_encap
```
```
In net/ipv4/udp_offload.c (ffffffff81ae4d19)
Location: include/linux/skbuff.h:2514
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81aefc29)
Location: include/linux/skbuff.h:2514
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81af37bd)
Location: include/linux/skbuff.h:2514
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_iphdr
```
```
In net/ipv4/gre_offload.c (ffffffff81b0789d)
Location: include/linux/skbuff.h:2514
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff81b68a17)
Location: include/linux/skbuff.h:2514
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err_encap
  - net/ipv6/udp.c:__udp6_lib_err_encap
```
```
In net/ipv6/mcast.c (ffffffff81b6f428)
Location: include/linux/skbuff.h:2514
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/exthdrs.c (ffffffff81b7b84f)
Location: include/linux/skbuff.h:2514
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d7b4)
Location: include/linux/skbuff.h:2514
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81b8fdf0)
Location: include/linux/skbuff.h:2514
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/ip6_offload.c (ffffffff81b9278e)
Location: include/linux/skbuff.h:2514
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b944d0)
Location: include/linux/skbuff.h:2514
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b963af)
Location: include/linux/skbuff.h:2514
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
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
In drivers/net/tun.c (ffffffff8187eab7)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff819cfd2f)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_partial_csum_set
```
```
In net/core/dev.c (ffffffff819efdfa)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81a186f6)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/selftests.c (ffffffff81a361aa)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (ffffffff81a871f2)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/udp.c (ffffffff81ace94a)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81acff36)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81adb372)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81adf332)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff81af303a)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff81b572e7)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81b5d439)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a317)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c664)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81b7eddd)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/ip6_offload.c (ffffffff81b818e1)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b83652)
Location: include/linux/skbuff.h:2530
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b8530f)
Location: include/linux/skbuff.h:2530
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
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
In drivers/net/tun.c (ffffffff819102a2)
Location: include/linux/skbuff.h:2559
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81a7f75f)
Location: include/linux/skbuff.h:2559
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_partial_csum_set
```
```
In net/core/dev.c (ffffffff81aa1233)
Location: include/linux/skbuff.h:2559
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81ac9be6)
Location: include/linux/skbuff.h:2559
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/selftests.c (ffffffff81aebe3f)
Location: include/linux/skbuff.h:2559
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (ffffffff81b419b2)
Location: include/linux/skbuff.h:2559
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/udp.c (ffffffff81b8d317)
Location: include/linux/skbuff.h:2559
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e956)
Location: include/linux/skbuff.h:2559
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81b9a722)
Location: include/linux/skbuff.h:2559
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81b9e812)
Location: include/linux/skbuff.h:2559
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff81bb354a)
Location: include/linux/skbuff.h:2559
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff81c1e8c5)
Location: include/linux/skbuff.h:2559
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81c24ba6)
Location: include/linux/skbuff.h:2559
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81c32177)
Location: include/linux/skbuff.h:2559
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47560)
Location: include/linux/skbuff.h:2559
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a57d)
Location: include/linux/skbuff.h:2559
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4bef0)
Location: include/linux/skbuff.h:2559
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4d921)
Location: include/linux/skbuff.h:2559
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f722)
Location: include/linux/skbuff.h:2559
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c5161f)
Location: include/linux/skbuff.h:2559
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
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
In drivers/net/tun.c (ffffffff81a63d7d)
Location: include/linux/skbuff.h:2928
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81bf3b9f)
Location: include/linux/skbuff.h:2928
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_partial_csum_set
```
```
In net/core/dev.c (ffffffff81c190de)
Location: include/linux/skbuff.h:2928
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81c4671d)
Location: include/linux/skbuff.h:2928
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/selftests.c (ffffffff81c6e7d1)
Location: include/linux/skbuff.h:2928
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (ffffffff81cd342f)
Location: include/linux/skbuff.h:2928
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp.c (ffffffff81d1e4b9)
Location: include/linux/skbuff.h:2928
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81d200a9)
Location: include/linux/skbuff.h:2928
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81d2cacf)
Location: include/linux/skbuff.h:2928
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81d30b78)
Location: include/linux/skbuff.h:2928
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff81d46d6c)
Location: include/linux/skbuff.h:2928
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff81dbb110)
Location: include/linux/skbuff.h:2928
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81dc1e52)
Location: include/linux/skbuff.h:2928
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81dcf975)
Location: include/linux/skbuff.h:2928
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6920)
Location: include/linux/skbuff.h:2928
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81de9e5a)
Location: include/linux/skbuff.h:2928
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81debea4)
Location: include/linux/skbuff.h:2928
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee001)
Location: include/linux/skbuff.h:2928
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81df0172)
Location: include/linux/skbuff.h:2928
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df3729)
Location: include/linux/skbuff.h:2928
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
In drivers/net/tun.c (ffffffff81bf2ef9)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81da18bf)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_partial_csum_set
```
```
In net/core/dev.c (ffffffff81dca0b4)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81dfac1d)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/selftests.c (ffffffff81e26501)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (ffffffff81e9361f)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp.c (ffffffff81ee5559)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81ee72a6)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ef4398)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81ef8c88)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff81f105bc)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff81f8b1e5)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81f92eb2)
Location: include/linux/skbuff.h:2820
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81fa0cf9)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9732)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81fbd5ba)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfb04)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc25c0)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc42a2)
Location: include/linux/skbuff.h:2820
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc84f9)
Location: include/linux/skbuff.h:2820
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
In drivers/net/tun.c (ffffffff81c4a0e4)
Location: include/linux/skbuff.h:2874
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81c4e14e)
Location: include/linux/skbuff.h:2874
Inline: True
```
```
In net/core/dev.c (ffffffff81e3ac2b)
Location: include/linux/skbuff.h:2874
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81e6be1d)
Location: include/linux/skbuff.h:2874
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/selftests.c (ffffffff81e9baa1)
Location: include/linux/skbuff.h:2874
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (ffffffff81ef1dc4)
Location: include/linux/skbuff.h:2874
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp.c (ffffffff81f44d2f)
Location: include/linux/skbuff.h:2874
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81f46b48)
Location: include/linux/skbuff.h:2874
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81f53c8f)
Location: include/linux/skbuff.h:2874
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81f586f8)
Location: include/linux/skbuff.h:2874
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff81f702a8)
Location: include/linux/skbuff.h:2874
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff81feb8a7)
Location: include/linux/skbuff.h:2874
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81ff311a)
Location: include/linux/skbuff.h:2874
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff820016a0)
Location: include/linux/skbuff.h:2874
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019e81)
Location: include/linux/skbuff.h:2874
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff8201e35a)
Location: include/linux/skbuff.h:2874
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020a94)
Location: include/linux/skbuff.h:2874
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff82023540)
Location: include/linux/skbuff.h:2874
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff820252c2)
Location: include/linux/skbuff.h:2874
Inline: True
```
```
In net/packet/af_packet.c (ffffffff82029019)
Location: include/linux/skbuff.h:2874
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
In drivers/net/tun.c (ffffffff81cffa70)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81d041b3)
Location: include/linux/skbuff.h:2881
Inline: True
```
```
In net/core/dev.c (ffffffff81ef8fde)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81f2b70d)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/selftests.c (ffffffff81f5e201)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (ffffffff81fb5f14)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp.c (ffffffff8200ad81)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff8200cc88)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8201a04f)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff8201ebb8)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff820369d8)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff82052d8c)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:__xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff820b9572)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff820c0dc7)
Location: include/linux/skbuff.h:2881
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff820d04e0)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e0f97)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:__xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8e51)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff820ed33a)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820efbc4)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff820f2679)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f45a2)
Location: include/linux/skbuff.h:2881
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820f8a59)
Location: include/linux/skbuff.h:2881
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
In drivers/net/tun.c (ffff8000109e16d8)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffff800010bb1e34)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/core/dev.c (ffff800010bd0f60)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffff800010bf8208)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/route.c (ffff800010c5cc34)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp.c (ffff800010c9e9dc)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffff800010ca0680)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffff800010caa43c)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffff800010cae6b8)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffff800010cc2d38)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffff800010d26b90)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffff800010d2e0d8)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f754)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffff800010d51400)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/ip6_offload.c (ffff800010d547f8)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffff800010d563f8)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d5a3f0)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (c0ac69a0)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (c0ccf79c)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/core/dev.c (c0cebb60)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (c0d11ca0)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/route.c (c0d6c38c)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp.c (c0dabb14)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (c0dada2c)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (c0db6c24)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (c0dbc9d0)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (c0dce504)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (c0e2bd70)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (c0e329e0)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/seg6_iptunnel.c (c0e504b4)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (c0e51e8c)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/ip6_offload.c (c0e54dc8)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (c0e569e8)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/packet/af_packet.c (c0e58f14)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_parse_headers
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
In drivers/net/tun.c (c000000000aa3630)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (c000000000c896f8)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/core/dev.c (c000000000caf100)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (c000000000cdec68)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/route.c (c000000000d5f200)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp.c (c000000000db1180)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (c000000000db2ea0)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (c000000000dc04e4)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (c000000000dc6ab0)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (c000000000ddeb9c)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (c000000000e578dc)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (c000000000e61c58)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86da0)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (c000000000e894d0)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/ip6_offload.c (c000000000e8d310)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f628)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/packet/af_packet.c (c000000000e947fc)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_parse_headers
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
In drivers/net/tun.c (ffffffe00062b1e8)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffe00074440a)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/core/dev.c (ffffffe00075b56c)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffe000779ecc)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/route.c (ffffffe0007c5a5e)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp.c (ffffffe0007fb562)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffe0007fcd44)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffe0008052a8)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffe000809a4e)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffe000818190)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffe000868c76)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffe00086eb36)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000887f38)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffe00088963e)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c160)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088dc74)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/packet/af_packet.c (ffffffe00089024e)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_parse_headers
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
In drivers/net/tun.c (ffffffff8178b229)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff818b8d5f)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/core/dev.c (ffffffff818d2f81)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff818f68e4)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/route.c (ffffffff8194c985)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp.c (ffffffff81988f16)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff8198aa59)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8199423b)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81998c96)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff819a970a)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff81a011bc)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81a08023)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a23054)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81a24a33)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/ip6_offload.c (ffffffff81a272c2)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28c50)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2b02c)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff8176ab79)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81872caf)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/core/dev.c (ffffffff8188ce11)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff818b0714)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/route.c (ffffffff81906475)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp.c (ffffffff819429d6)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81944519)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8194dcfb)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81952756)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff819631ca)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff819bdf7c)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff819c4de3)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dfe14)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff819e17f3)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/ip6_offload.c (ffffffff819e4082)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5e40)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e821c)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff817bb5c9)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81909d5f)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/core/dev.c (ffffffff81923f81)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81947914)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/route.c (ffffffff819b7155)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp.c (ffffffff819f36e6)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819f5229)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819feadb)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81a03536)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff81a13faa)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff81a6bc3c)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81a72aa3)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8dad4)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f4b3)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a9123d)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather
```
```
In net/ipv6/ip6_offload.c (ffffffff81a92e72)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a94800)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a96bdc)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff817d4604)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff8192ae5f)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/core/dev.c (ffffffff819453f1)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81969224)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/route.c (ffffffff819c09d5)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp.c (ffffffff819fd8a6)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819ff415)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81a0a8cf)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81a0da86)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff81a1e99a)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff81a7824c)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81a7f123)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a7d4)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81a9c233)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9efb6)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa0960)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa3856)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
</ul>

## Differences

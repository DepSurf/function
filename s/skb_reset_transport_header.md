# Function: <code>skb_reset_transport_header</code>

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
In drivers/net/tun.c (ffffffff815eec6d)
Location: include/linux/skbuff.h:2001
Inline: True
```
```
In net/core/skbuff.c (ffffffff8170a132)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff8171a5eb)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/netpoll.c (ffffffff817393bb)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff8174c535)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_output.c (ffffffff8175cd63)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff817619b6)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_output.c (ffffffff81774cc9)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8178b26d)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81794a6c)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:2001
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff817a5279)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff817a74d2)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff817b00e3)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff817c7984)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ndisc.c (ffffffff817de893)
Location: include/linux/skbuff.h:2001
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/skbuff.h:2001
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff817ee65a)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817eef62)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff817f4b02)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
```
```
In net/ipv6/ip6mr.c (ffffffff817f8575)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_get_route
```
```
In net/ipv6/ip6_offload.c (ffffffff81800ebb)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff818027b8)
Location: include/linux/skbuff.h:2001
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81807dbf)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
Location: include/linux/skbuff.h:2131
Inline: True
```
```
In net/core/skbuff.c (ffffffff817718ef)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81782af2)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/netpoll.c (ffffffff817a5672)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff817b8249)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_output.c (ffffffff817c9b43)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cde29)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff817e1c45)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/udp_offload.c (ffffffff817f8b20)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81802416)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81805864)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff81812d3b)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff818151c3)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff8181d013)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81834a9e)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ndisc.c (ffffffff8184c7b3)
Location: include/linux/skbuff.h:2131
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/skbuff.h:2131
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff8185ce96)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185d84d)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff81863e64)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff8186b3dd)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/ip6_offload.c (ffffffff8187269b)
Location: include/linux/skbuff.h:2131
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff81873ab7)
Location: include/linux/skbuff.h:2131
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81879f82)
Location: include/linux/skbuff.h:2131
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
Location: include/linux/skbuff.h:2148
Inline: True
```
```
In net/core/skbuff.c (ffffffff8179ea1f)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff817b03d6)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/netpoll.c (ffffffff817d40e2)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff817e7d29)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_output.c (ffffffff817f9ac4)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fdb89)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff8181214d)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/udp_offload.c (ffffffff818299fd)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff818333a1)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81836cb4)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff8184424d)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81846983)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff8184e8d3)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81866536)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ndisc.c (ffffffff8187e683)
Location: include/linux/skbuff.h:2148
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/skbuff.h:2148
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff8188edf4)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8188f897)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff81894f9a)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/datagram.c (ffffffff81896514)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff8189e23d)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a410c)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6c9b)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a8137)
Location: include/linux/skbuff.h:2148
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818ae76c)
Location: include/linux/skbuff.h:2148
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
Location: include/linux/skbuff.h:2187
Inline: True
```
```
In net/core/skbuff.c (ffffffff817bda0f)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff817ce72c)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/netpoll.c (ffffffff817f342a)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff81807a38)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_output.c (ffffffff81819f03)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181dfc1)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff818324c8)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8184a98d)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8185470e)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81857d11)
Location: include/linux/skbuff.h:2187
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff81865af1)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff818697b5)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff818723a3)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff8188acf7)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ndisc.c (ffffffff818a46c3)
Location: include/linux/skbuff.h:2187
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/skbuff.h:2187
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff818b529a)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b5f23)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff818bb2dc)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/datagram.c (ffffffff818bca9a)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff818c4801)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca707)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd6b8)
Location: include/linux/skbuff.h:2187
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ce977)
Location: include/linux/skbuff.h:2187
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d5099)
Location: include/linux/skbuff.h:2187
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
Location: include/linux/skbuff.h:2274
Inline: True
```
```
In net/core/skbuff.c (ffffffff8183705f)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81847fb3)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/netpoll.c (ffffffff8186e81a)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff818865a8)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_output.c (ffffffff81898541)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189ced1)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff818b161f)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/udp_offload.c (ffffffff818ca633)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff818d45ae)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff818d74d1)
Location: include/linux/skbuff.h:2274
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff818e5c27)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff818e9e02)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2d83)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff8190beee)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ndisc.c (ffffffff81927073)
Location: include/linux/skbuff.h:2274
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/skbuff.h:2274
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81938010)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81938cbd)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff8193e2f2)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/datagram.c (ffffffff8193fbba)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff81947aa1)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e436)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff8194f916)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff819524aa)
Location: include/linux/skbuff.h:2274
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff81953827)
Location: include/linux/skbuff.h:2274
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81959b22)
Location: include/linux/skbuff.h:2274
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
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81881568)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81891ffb)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/filter.c (ffffffff818b221f)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff818bf9ae)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff818d9eb1)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/route.c (ffffffff818e6b8a)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff818ec779)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f13b0)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff81906e44)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8192098f)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8192ac90)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8192de21)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff8193c4c4)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8194051d)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff819496ed)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff819632e0)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ndisc.c (ffffffff8197f443)
Location: include/linux/skbuff.h:2285
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff8198c780)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/reassembly.c (ffffffff819911d9)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81992536)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff81997229)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/datagram.c (ffffffff819989f6)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff819a0b22)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7727)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff819a88e9)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff819aba44)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad249)
Location: include/linux/skbuff.h:2285
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819b0897)
Location: include/linux/skbuff.h:2285
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
Location: include/linux/skbuff.h:2363
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
In net/core/skbuff.c (ffffffff818a2089)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff818b5e5b)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/filter.c (ffffffff818d7274)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff818e87ce)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff819069ae)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/route.c (ffffffff81913a55)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81919901)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191ef07)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff81934ff1)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (ffffffff8194db66)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff8194f7bd)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8195a411)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8195d6e2)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff8196c1ba)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81970394)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b3ab)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/ip6_output.c (ffffffff819982ab)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ndisc.c (ffffffff819b5a13)
Location: include/linux/skbuff.h:2363
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bc59b)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff819c2ffd)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/reassembly.c (ffffffff819c791b)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c8c76)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff819cdb0e)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/datagram.c (ffffffff819cf34d)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff819d772e)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffffffff819d8c3d)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de294)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff819df420)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff819e25e6)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3bf0)
Location: include/linux/skbuff.h:2363
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e8269)
Location: include/linux/skbuff.h:2363
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
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff818ecd3e)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81901dfd)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/filter.c (ffffffff81924d84)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff81937fe0)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff81967c4e)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/route.c (ffffffff81976105)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8197b1b9)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
```
In net/ipv4/ip_sockglue.c (ffffffff8198184d)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff81998f97)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (ffffffff819b2373)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819b4003)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819bef8f)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff819c2356)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff819d2f05)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff819d9c2b)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e48eb)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4a9a)
Location: include/linux/skbuff.h:2451
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff819f849b)
Location: include/linux/skbuff.h:2451
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a0122e)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
```
In net/ipv6/ndisc.c (ffffffff81a244f3)
Location: include/linux/skbuff.h:2451
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a2b0cd)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81a31e43)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/reassembly.c (ffffffff81a35cfb)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3760f)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c12c)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81a3e09c)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff81a467c2)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a474b0)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4cdf4)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81a4dfbc)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81a512ad)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a529e0)
Location: include/linux/skbuff.h:2451
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a54dac)
Location: include/linux/skbuff.h:2451
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
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff8191ee5e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff8193403d)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/filter.c (ffffffff819571b4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff8196aea0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff8199e6ee)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/route.c (ffffffff819acb15)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff819b1b29)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b808d)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff819cfab7)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (ffffffff819e9113)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819ead33)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819f5bcf)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff819f8ef6)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff81a09a79)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a10a83)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b8b5)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b74a)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f0fb)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a37e0e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
```
In net/ipv6/ndisc.c (ffffffff81a5af73)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a61c2d)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81a68993)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/reassembly.c (ffffffff81a6c81b)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6e139)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff81a72dac)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81a74d0c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff81a7d3b2)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a7e060)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a839c4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81a853a3)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87ecd)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a895c0)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a8b99c)
Location: include/linux/skbuff.h:2465
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
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff819f1fca)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81a08a32)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/filter.c (ffffffff81a2f811)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff81a3ec07)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff81a7830e)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/route.c (ffffffff81a9685e)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a9c3b7)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa29b2)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff81abc33f)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (ffffffff81ad3c31)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err_encap
```
```
In net/ipv4/udp_offload.c (ffffffff81ad891b)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ae40bf)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81ae68ed)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_iphdr
```
```
In net/ipv4/gre_offload.c (ffffffff81afa1ed)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81b023a1)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c99b)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e29e)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/xfrm/espintcp.c (ffffffff81b22785)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/ipv6/ip6_output.c (ffffffff81b2de13)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
```
In net/ipv6/ndisc.c (ffffffff81b538f3)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/udp.c (ffffffff81b5a3de)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err_encap
```
```
In net/ipv6/mcast.c (ffffffff81b60cb8)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/reassembly.c (ffffffff81b65a1b)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67e43)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d29d)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81b6ef5c)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff81b77d5b)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78d34)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e7a4)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81b80570)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81b83378)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b84b70)
Location: include/linux/skbuff.h:2488
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b85ddf)
Location: include/linux/skbuff.h:2488
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
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff819f1ff4)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81a09fdc)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/filter.c (ffffffff81a31b21)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff81a419a7)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff81a8112a)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/route.c (ffffffff81aa0909)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/ip_output.c (ffffffff81aa6217)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aaccc2)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff81ac7bbd)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (ffffffff81adfd41)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err_encap
```
```
In net/ipv4/udp_offload.c (ffffffff81ae4e28)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81af0fef)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81af37bd)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_iphdr
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06942)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81b0798f)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81b10748)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1accb)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2cb6e)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/xfrm/espintcp.c (ffffffff81b31445)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/ipv6/ip6_output.c (ffffffff81b3c863)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
```
In net/ipv6/ndisc.c (ffffffff81b61e83)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/udp.c (ffffffff81b68ade)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err_encap
```
```
In net/ipv6/mcast.c (ffffffff81b6f428)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/reassembly.c (ffffffff81b7417b)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b76670)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff81b7bd45)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81b7da8c)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff81b86cdb)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87cb4)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d7b4)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81b8fdf0)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92a28)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b944d0)
Location: include/linux/skbuff.h:2509
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b963af)
Location: include/linux/skbuff.h:2509
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
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff819d82ea)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff819f096d)
Location: include/linux/skbuff.h:2525
Inline: True
```
```
In net/core/filter.c (ffffffff81a18995)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff81a26467)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81a361aa)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netlink/af_netlink.c (ffffffff81a698a3)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/route.c (ffffffff81a8b839)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a913d2)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a97f12)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff81ab2c1d)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (ffffffff81ace9a5)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81ad002a)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81adc7af)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81adf332)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af2055)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81af3184)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81afe358)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b08988)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a7a9)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/xfrm/espintcp.c (ffffffff81b1f252)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b29ccb)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
```
In net/ipv6/ndisc.c (ffffffff81b500f3)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/udp.c (ffffffff81b5733d)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81b5d439)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/reassembly.c (ffffffff81b62bdb)
Location: include/linux/skbuff.h:2525
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b64f98)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a815)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81b6c67c)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff81b759a2)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b76971)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c664)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81b7eddd)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81b80)
Location: include/linux/skbuff.h:2525
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b83652)
Location: include/linux/skbuff.h:2525
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b8530f)
Location: include/linux/skbuff.h:2525
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
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81a8813a)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81aa22cd)
Location: include/linux/skbuff.h:2554
Inline: True
```
```
In net/core/filter.c (ffffffff81ac9e85)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff81adb1de)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81aebe3f)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netlink/af_netlink.c (ffffffff81b22e53)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/route.c (ffffffff81b467a1)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/ip_output.c (ffffffff81b4c782)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b533a2)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff81b6fb11)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (ffffffff81b8d372)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81b8ea4a)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81b9bb8f)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81b9e812)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2565)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81bb3694)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81bbf612)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb842)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdedc9)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/xfrm/espintcp.c (ffffffff81be3e3e)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81bef89b)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
```
In net/ipv6/ndisc.c (ffffffff81c17453)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/udp.c (ffffffff81c1e91b)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81c24ba6)
Location: include/linux/skbuff.h:2554
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81c2a676)
Location: include/linux/skbuff.h:2554
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d1d8)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff81c32675)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81c34550)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff81c403c8)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c413ab)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47560)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a57d)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4bef0)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4dbc7)
Location: include/linux/skbuff.h:2554
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f722)
Location: include/linux/skbuff.h:2554
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c5161f)
Location: include/linux/skbuff.h:2554
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
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81bfd5be)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81c1a5ee)
Location: include/linux/skbuff.h:2923
Inline: True
```
```
In net/core/filter.c (ffffffff81c469d6)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff81c5c6ee)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81c6e7d1)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (ffffffff81cd342f)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81cd9e49)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdfa97)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff81cff19f)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (ffffffff81d1e4ef)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81d20213)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81d2d95d)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81d30b78)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45cef)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81d46ecb)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81d543b4)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d612f0)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81d76622)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/espintcp.c (ffffffff81d7adfa)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81d8840a)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
```
In net/ipv6/ndisc.c (ffffffff81db32b3)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/udp.c (ffffffff81dbb148)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81dc1e52)
Location: include/linux/skbuff.h:2923
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81dc7b23)
Location: include/linux/skbuff.h:2923
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dca5ea)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff81dcfe6a)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81dd1e4e)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff81ddea03)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddfb25)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6920)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81de9e5a)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81debea4)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee2a0)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff81df0172)
Location: include/linux/skbuff.h:2923
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df3729)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
```
In net/mctp/route.c (ffffffff81e3aaa0)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_local_output
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
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81dac5a8)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81dcb69b)
Location: include/linux/skbuff.h:2815
Inline: True
```
```
In net/core/filter.c (ffffffff81dfaeed)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff81e12dde)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81e26501)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (ffffffff81e9361f)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81e9a5e9)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9fe37)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff81ec41ff)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (ffffffff81ee558f)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7410)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ef585d)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81ef8c88)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f0b6)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81f1071b)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f1e589)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2bbf0)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42d84)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/espintcp.c (ffffffff81f47f55)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/ipv6/ip6_output.c (ffffffff81f563ca)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
```
In net/ipv6/ndisc.c (ffffffff81f828b3)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/udp.c (ffffffff81f8b21d)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81f92eb2)
Location: include/linux/skbuff.h:2815
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81f98893)
Location: include/linux/skbuff.h:2815
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9b624)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff81fa11ed)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81fa329e)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff81fb0c01)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1e15)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9732)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81fbd5ba)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfb04)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc280d)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc42a2)
Location: include/linux/skbuff.h:2815
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc84f9)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
```
In net/mctp/route.c (ffffffff82014070)
Location: include/linux/skbuff.h:2815
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_local_output
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
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81c4e14e)
Location: include/linux/skbuff.h:2869
Inline: True
```
```
In net/core/skbuff.c (ffffffff81e1bd28)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81e3c22b)
Location: include/linux/skbuff.h:2869
Inline: True
```
```
In net/core/filter.c (ffffffff81e6c0ee)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff81e86707)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81e9baa1)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (ffffffff81ef1dc4)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81ef8f69)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efe687)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff81f22504)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (ffffffff81f44dac)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81f46cb2)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81f55213)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81f586f8)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6edb9)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81f70407)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f7e073)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b630)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa2562)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/espintcp.c (ffffffff81fa7a55)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/ipv6/ip6_output.c (ffffffff81fb5daa)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
```
In net/ipv6/ndisc.c (ffffffff81fe2bc3)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/udp.c (ffffffff81feb8d7)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81ff311a)
Location: include/linux/skbuff.h:2869
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81ff9273)
Location: include/linux/skbuff.h:2869
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffba43)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff82001a95)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff82003b54)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff820112be)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffffffff82012523)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019e81)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff8201e35a)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020a94)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff8202378b)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff820252c2)
Location: include/linux/skbuff.h:2869
Inline: True
```
```
In net/packet/af_packet.c (ffffffff82029019)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
```
In net/mctp/route.c (ffffffff82090ef0)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_local_output
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
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81d041b3)
Location: include/linux/skbuff.h:2876
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ed92e8)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81efa746)
Location: include/linux/skbuff.h:2876
Inline: True
```
```
In net/core/filter.c (ffffffff81f2b9de)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff81f48714)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81f5e201)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (ffffffff81fb5f14)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81fbce89)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc28aa)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff81fe7119)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (ffffffff8200adfe)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff8200cdf2)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8201b483)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8201ebb8)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff820354d9)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff82036b37)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff820448b0)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff82052d33)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:__xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:__xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f8a4)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/espintcp.c (ffffffff82074d15)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/ipv6/ip6_output.c (ffffffff8208347a)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
```
In net/ipv6/ndisc.c (ffffffff820b0ae0)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/udp.c (ffffffff820b95a2)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff820c0dc7)
Location: include/linux/skbuff.h:2876
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff820c6ef3)
Location: include/linux/skbuff.h:2876
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ca177)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff820d0898)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff820d2904)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff820e024e)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e0f3e)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:__xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:__xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8e51)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff820ed33a)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820efbc4)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff820f2679)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f45a2)
Location: include/linux/skbuff.h:2876
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820f8a59)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
```
In net/mctp/route.c (ffffffff82167410)
Location: include/linux/skbuff.h:2876
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_local_output
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
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffff800010bb9664)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffff800010bd23b0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/filter.c (ffff800010c00948)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffff800010c11510)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffff800010c4d414)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/route.c (ffff800010c5cc34)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffff800010c62738)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
```
In net/ipv4/ip_sockglue.c (ffff800010c6943c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffff800010c82cbc)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (ffff800010c9ea2c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffff800010ca082c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffff800010cab840)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffff800010cae6b8)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffff800010cc2d70)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffff800010ccb688)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd7b70)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffff800010cea1dc)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffff800010cede94)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/ipv6/ip6_output.c (ffff800010cf85f0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
```
In net/ipv6/ndisc.c (ffff800010d20348)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d26c6c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffff800010d2e0d8)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/reassembly.c (ffff800010d35210)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37b38)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffff800010d3b8d0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffff800010d3d6f4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffff800010d48078)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffff800010d49400)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f754)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffff800010d51400)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffff800010d54a64)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffff800010d563f8)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d5a3f0)
Location: include/linux/skbuff.h:2465
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
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (c0cd60e0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (c0cecf6c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/filter.c (c0d125c4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (c0d293c4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (c0d5c574)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/route.c (c0d6c38c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (c0d71d20)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
```
In net/ipv4/ip_sockglue.c (c0d78624)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (c0d916d4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (c0dabb14)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (c0dadaf4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (c0db872c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (c0dbc9d0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (c0dce5f0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (c0dd5b90)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (c0de1678)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (c0df2170)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/xfrm/xfrm_device.c (c0df60c8)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/ipv6/ip6_output.c (c0dffd08)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
```
In net/ipv6/ndisc.c (c0e24f30)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/ipv6/udp.c (c0e2be34)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (c0e329e0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/reassembly.c (c0e371a4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (c0e38774)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (c0e3dfbc)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (c0e408ec)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (c0e49a98)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (c0e4a7d8)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (c0e504b4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (c0e51e8c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (c0e5506c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (c0e569e8)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/packet/af_packet.c (c0e58f14)
Location: include/linux/skbuff.h:2465
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
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (c000000000c91c18)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (c000000000cb09dc)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/filter.c (c000000000ce3a14)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (c000000000cfe1f4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (c000000000d49fac)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/route.c (c000000000d5f200)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (c000000000d65824)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
```
In net/ipv4/ip_sockglue.c (c000000000d6e024)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (c000000000d8db4c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (c000000000db11e0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (c000000000db30f4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (c000000000dc21d0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (c000000000dc6ab0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (c000000000ddece4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (c000000000de8398)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (c000000000df7b30)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (c000000000e0db90)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/xfrm/xfrm_device.c (c000000000e12af0)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/ipv6/ip6_output.c (c000000000e205d0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
```
In net/ipv6/ndisc.c (c000000000e4eb68)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/ipv6/udp.c (c000000000e579b0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (c000000000e61c58)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/reassembly.c (c000000000e66fc0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (c000000000e69028)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (c000000000e6f144)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (c000000000e71a90)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (c000000000e7d55c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e9cc)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86da0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (c000000000e894d0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (c000000000e8d5e0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f628)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/packet/af_packet.c (c000000000e947fc)
Location: include/linux/skbuff.h:2465
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
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffe000748b88)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffe00075c898)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/filter.c (ffffffe00077a61c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffe00078d6dc)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffe0007b91cc)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/route.c (ffffffe0007c5a5e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffe0007ca05e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf34e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffe0007e44a4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (ffffffe0007fb562)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffe0007fcf44)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffe0008064a4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffe000809a4e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffe000818226)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffe00081e95e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffe0008281bc)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffe000837e34)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b4b2)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffe00084432e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
```
In net/ipv6/ndisc.c (ffffffe000862644)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/ipv6/udp.c (ffffffe000868d12)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffe00086eb36)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/reassembly.c (ffffffe0008725d4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000873ebe)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffe0008781c0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffe000879e6a)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffe000881ba2)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffffffe0008828e2)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000887f38)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffe00088963e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c3d6)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088dc74)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/packet/af_packet.c (ffffffe00089024e)
Location: include/linux/skbuff.h:2465
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
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff818bee5e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff818d403d)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/filter.c (ffffffff818f7184)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff8190ae70)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff8193e55e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/route.c (ffffffff8194c985)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81951999)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
```
In net/ipv4/ip_sockglue.c (ffffffff81957efd)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff8196f927)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (ffffffff81988f83)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff8198aba3)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8199596f)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81998c96)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff819a9819)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff819b0493)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff819baf45)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff819cadda)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce78b)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819d749e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
```
In net/ipv6/ndisc.c (ffffffff819fa603)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a012bd)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81a08023)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/reassembly.c (ffffffff81a0beab)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0d7c9)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff81a1243c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81a1439c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff81a1ca42)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a1d6f0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a23054)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81a24a33)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81a2755d)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28c50)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2b02c)
Location: include/linux/skbuff.h:2465
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
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/vxlan.c (ffffffff8177382c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - drivers/net/vxlan.c:neigh_reduce
```
```
In net/core/skbuff.c (ffffffff81878d9e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff8188decd)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/filter.c (ffffffff818b0fb4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff818c4c0b)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff818f805e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/route.c (ffffffff81906475)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8190b489)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
```
In net/ipv4/ip_sockglue.c (ffffffff819119ed)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff819293f7)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (ffffffff81942a43)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81944663)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8194f42f)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81952756)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff819632d9)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8196cac3)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/udp_tunnel.c (ffffffff81971e9a)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp_tunnel.c:udp_tunnel_xmit_skb
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977d35)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81987bca)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b56b)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8199425e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
```
In net/ipv6/ndisc.c (ffffffff819b73c3)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819be07d)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff819c4de3)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/reassembly.c (ffffffff819c8c6b)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca589)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff819cf1fc)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff819d115c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff819d9802)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffffffff819da4b0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dfe14)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff819e17f3)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff819e431d)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/ip6_udp_tunnel.c (ffffffff819e5a34)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_udp_tunnel.c:udp_tunnel6_xmit_skb
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5e40)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e821c)
Location: include/linux/skbuff.h:2465
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
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff8190fe5e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff8192503d)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/filter.c (ffffffff819481b4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff8195bea0)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff8198f6ee)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/route.c (ffffffff819b7155)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff819bc169)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c26cd)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff819da0f7)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (ffffffff819f3753)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819f5373)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81a0020f)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81a03536)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff81a140b9)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a1ad33)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a259c5)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81a3585a)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81a3920b)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a41f1e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
```
In net/ipv6/ndisc.c (ffffffff81a65083)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a6bd3d)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81a72aa3)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/reassembly.c (ffffffff81a7692b)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a78249)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff81a7cebc)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81a7ee1c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff81a874c2)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a88170)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8dad4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f4b3)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a9123d)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9310d)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a94800)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a96bdc)
Location: include/linux/skbuff.h:2465
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
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81930f8e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff8194651d)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/filter.c (ffffffff81969ac4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff8197e280)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff819b1fce)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/route.c (ffffffff819c09d5)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff819c5a79)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cc0cd)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_output.c (ffffffff819e3d6c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/udp.c (ffffffff819fd913)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819ff56e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81a0a25f)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81a0da86)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/gre_offload.c (ffffffff81a1eaa9)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a25b9e)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30e55)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81a411c5)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44c3b)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a4dbae)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
```
In net/ipv6/ndisc.c (ffffffff81a715b3)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a7834d)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/mcast.c (ffffffff81a7f123)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/reassembly.c (ffffffff81a8305b)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a849b9)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff81a8970c)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81a8b6dc)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff81a94098)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a94da1)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a7d4)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81a9c233)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f2af)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa0960)
Location: include/linux/skbuff.h:2465
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa3856)
Location: include/linux/skbuff.h:2465
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
</ul>

## Differences

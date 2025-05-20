# Function: <code>skb_reset_network_header</code>

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
In drivers/net/tun.c (ffffffff815ef15e)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff815fb996)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8170a116)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81715205)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81739477)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff8174b2ac)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv4/route.c (ffffffff817572ac)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8175cd9c)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff81761a5f)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff817850fc)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2018
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8178bb03)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff8178f1f1)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81793cfb)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8179622c)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a47fe)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2018
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff817a74ba)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_get_route
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817aef95)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff817c4d12)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff817dea6a)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff817e614e)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff817e8854)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff817ea102)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/datagram.c (ffffffff817f4bc1)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
```
```
In net/ipv6/ip6mr.c (ffffffff817f8519)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_get_route
```
```
In net/ipv6/ip6_offload.c (ffffffff81800cc0)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81807543)
Location: include/linux/skbuff.h:2018
Inline: True
Inline callers:
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
In drivers/net/tun.c (ffffffff8164dc92)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8165bbfc)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81771ebf)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81783bf4)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/netpoll.c (ffffffff817a572b)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff817b7de6)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv4/route.c (ffffffff817c354c)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff817cb0bf)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cdd8f)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff817f26d9)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2148
Inline: True
```
```
In net/ipv4/arp.c (ffffffff817f9144)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff817fc851)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff8180145f)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8180485f)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818124c0)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2148
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818187b5)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181be84)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81835129)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff8184c9a2)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff818545c1)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff81857071)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff818581f4)
Location: include/linux/skbuff.h:2148
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81863dbe)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffffffff8186b3fb)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff818700e7)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/ip6_offload.c (ffffffff81872450)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81879b61)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff8188c414)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (ffffffff8167f97f)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff816899da)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8179efb7)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff817b118d)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/netpoll.c (ffffffff817d419b)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff817e78c6)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv4/route.c (ffffffff817f2b3f)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff817fad14)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fdaef)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff81823583)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2165
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8182a014)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff8182d7b4)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff8183226f)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81835834)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818439c4)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2165
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8184a015)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184d744)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81866c63)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff8187e863)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff818862e7)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff81888e71)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff8188a5f4)
Location: include/linux/skbuff.h:2165
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81894f86)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/datagram.c (ffffffff8189646e)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffffffff8189e25b)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff818a3057)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a41ad)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6a40)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff818ae262)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff818c05c3)
Location: include/linux/skbuff.h:2165
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (ffffffff81694bb1)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8169f1d3)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff817bc6fc)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff817d156a)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/netpoll.c (ffffffff817f34e4)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff818075d3)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff8180c9eb)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff8181343a)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8181b112)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181df30)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff81844225)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2204
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8184b24a)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff8184ed0c)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81854d44)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81856d68)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81865223)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2204
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8186da66)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81871258)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff8188b32f)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff818a48fe)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff818aca53)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff818af557)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff818b0666)
Location: include/linux/skbuff.h:2204
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff818bb2d5)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/datagram.c (ffffffff818bca02)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffffffff818c481c)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff818c9627)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca7f4)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd4b7)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff818d4bff)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff818e6f35)
Location: include/linux/skbuff.h:2204
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (ffffffff816fed81)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8170a36a)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81836dcc)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff8184b67e)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/netpoll.c (ffffffff8186e8d4)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff8188611a)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff8188b9d2)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81892a8a)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8189a0b2)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189ce40)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff818c3b89)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2291
Inline: True
```
```
In net/ipv4/arp.c (ffffffff818caeba)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff818cea92)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff818d4be4)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff818d6c18)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e5383)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2291
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818ee3a6)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f1c48)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff8190c54f)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff819272da)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff8192f2b0)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff8193226d)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81933306)
Location: include/linux/skbuff.h:2291
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff8193e2eb)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/datagram.c (ffffffff8193fb22)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffffffff81947abc)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff8194ccc7)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e1ed)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8194f90e)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff819522a7)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff8195967e)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff8196c3e5)
Location: include/linux/skbuff.h:2291
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (ffffffff8173ed9a)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81748a1a)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81880f0d)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff818959d5)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/netpoll.c (ffffffff818bfa60)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff818d99ca)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff818df403)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff818e6b50)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff818ee505)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f131f)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff819197aa)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2302
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819213c4)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff81924e60)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff8192b154)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8192d558)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193bc51)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2302
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81943f8e)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8194856e)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff819639c9)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff8197f6a4)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81987c8b)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff8198abb3)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff8198bed7)
Location: include/linux/skbuff.h:2302
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81997214)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/datagram.c (ffffffff8199895e)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffffffff819a0b3c)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff819a60aa)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a717c)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819a88e1)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff819ab817)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff819b03c6)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff819c5e86)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (ffffffff8176381e)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8176cabe)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff818a1da4)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff818b76b9)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff818d726b)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/netpoll.c (ffffffff818e8880)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff8190641d)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff8190bf10)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81913a16)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8191bcc9)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191ee7f)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff81948088)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8194dae9)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2380
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819501d4)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff81953c72)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81958dce)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8195c9f8)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196baad)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2380
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819740de)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8197a248)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff8199896b)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff819b5c9b)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819bc498)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff819be5b5)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff819c1481)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff819c27e7)
Location: include/linux/skbuff.h:2380
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff819cdaf9)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/datagram.c (ffffffff819cf2be)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffffffff819d7748)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff819dca57)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819ddcd6)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819df418)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff819e2330)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff819e7bdd)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff819fd5b4)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (ffffffff817a152e)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817aac10)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff818ec787)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff819034ef)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff81924d7b)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (ffffffff81938092)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81943686)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netlink/af_netlink.c (ffffffff8196773c)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff8196d6da)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff819760d5)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8197dfb6)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff819817a8)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff819ac337)
Location: include/linux/skbuff.h:2468
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b2306)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2468
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819b4a94)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff819b856c)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff819bd880)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff819c16f9)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d27ce)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2468
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819ddbb0)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e3d80)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4b6c)
Location: include/linux/skbuff.h:2468
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819f5e04)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a047cf)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81a24779)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a2afcc)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81a2d002)
Location: include/linux/skbuff.h:2468
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a3025c)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81a314d7)
Location: include/linux/skbuff.h:2468
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c123)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81a3e00d)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffffffff81a467e0)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff81a4b491)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4c856)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a4dfa8)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81a50ff3)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81a54763)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81a6c81c)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (ffffffff817c64ee)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817ce653)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8191e8b7)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff8193629f)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff819571ab)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (ffffffff8196af52)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff8197866c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netlink/af_netlink.c (ffffffff8199e1cc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff819a4145)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff819acae5)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff819b4962)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b7fe8)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff819e2dcb)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e90a6)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819eb7c4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff819ef26c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff819f4490)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff819f8299)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a091ce)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a14cf7)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a1ad70)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b81c)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2ca84)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b3bf)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81a5b1f9)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a61b2c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81a63b3b)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffffffff81a66dac)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81a68027)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a72da3)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81a74c7d)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffffffff81a7d3d0)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff81a82061)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83426)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a84b84)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87c13)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81a8b353)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81aa31dc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (ffffffff8188db12)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81899834)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff819f1137)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81a0aebe)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff81a2f808)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/netpoll.c (ffffffff81a3ecb9)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81a4d622)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netlink/af_netlink.c (ffffffff81a76e0f)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap_skb
```
```
In net/bpf/test_run.c (ffffffff81a7ec8a)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81a96848)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a9eb2a)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa2908)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff81ad06a3)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81ad3b86)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err_encap
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2505
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81ad98a4)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff81add1b6)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81ae2d51)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81ae5303)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8c5e)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2505
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b05c77)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0bdc8)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d6af)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1f65c)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_beet_encap_add
```
```
In net/ipv6/ip6_output.c (ffffffff81b30992)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81b53df8)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b5a317)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err_encap
```
```
In net/ipv6/raw.c (ffffffff81b5c5cb)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffffffff81b5f831)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81b603f7)
Location: include/linux/skbuff.h:2505
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d295)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81b6eecd)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffffffff81b77d79)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff81b7d174)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e23c)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7fc14)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81b830c3)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81b87175)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81b9e576)
Location: include/linux/skbuff.h:2505
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_alloc_command
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
In drivers/net/tun.c (ffffffff8189c052)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff818a7d64)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff819f10c7)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81a0c107)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff81a31b18)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/netpoll.c (ffffffff81a41a59)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81a532e9)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netlink/af_netlink.c (ffffffff81a7fb8f)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap_skb
```
```
In net/bpf/test_run.c (ffffffff81a885cd)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81aa08f3)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/ip_output.c (ffffffff81aa8a70)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aacc18)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff81adc6b3)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81adfc96)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err_encap
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2526
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81ae62f4)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff81ae9f17)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81aefc1e)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81af21ce)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b068a8)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2526
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b13ea7)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b1a158)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2bed1)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2df2c)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_beet_encap_add
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f5c2)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81b623ed)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b68a17)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err_encap
```
```
In net/ipv6/raw.c (ffffffff81b6ae0b)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffffffff81b6dfe2)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81b6eb67)
Location: include/linux/skbuff.h:2526
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b7bd3d)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81b7d9fd)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffffffff81b86cf9)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff81b8c224)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d24e)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b8ef44)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81b9276c)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81b96ccf)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81badf76)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_alloc_command
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
In drivers/net/tun.c (ffffffff8187e5b9)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8188b559)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff819d6398)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff819f22ba)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff81a1898c)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/netpoll.c (ffffffff81a2651c)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (0)
Location: include/linux/skbuff.h:2542
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a38b12)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netlink/af_netlink.c (ffffffff81a68b6c)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81a7182d)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81a8b823)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a93b8d)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a97e68)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff81ac76fe)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81ace94a)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2542
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81ad15d4)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff81ad566a)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81adb367)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81add9c0)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af1fbb)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2542
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b01ced)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b07dfd)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19b3f)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1b63e)
Location: include/linux/skbuff.h:2542
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d45c)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81b5073d)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b572dc)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81b59113)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffffffff81b5c3ab)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81b5cf77)
Location: include/linux/skbuff.h:2542
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a80d)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81b6c5ed)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffffffff81b759c0)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff81b7b0a7)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c103)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7df84)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81b818c2)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81b85cd1)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81b9d77c)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (ffffffff8190fdc6)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8191e449)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81a869d8)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81aa418a)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff81ac9e7c)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/netpoll.c (ffffffff81adb297)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (0)
Location: include/linux/skbuff.h:2571
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81aee9f2)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netlink/af_netlink.c (ffffffff81b22103)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81b2af4c)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81b4678b)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/ip_output.c (ffffffff81b4efcd)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b532f8)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff81b85f47)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81b8d317)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2571
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81b90204)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff81b9449c)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81b9a717)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81b9ce5b)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb24cb)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2571
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bc3aed)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bcacfd)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdde0f)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0747)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm4_prepare_output
```
```
In net/ipv6/ip6_output.c (ffffffff81bf362d)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81c17ae5)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81c1e8ba)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81c206ec)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffffffff81c23ae0)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81c249cb)
Location: include/linux/skbuff.h:2571
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81c3266d)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81c344c1)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81c38201)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_icmp_srh
```
```
In net/ipv6/ip6mr.c (ffffffff81c403e6)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff81c45d67)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47003)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81c48df4)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4be76)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4d902)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81c52077)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81c6ad0f)
Location: include/linux/skbuff.h:2571
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (ffffffff81a63afc)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81a72919)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81bfc114)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81c19eb3)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff81c469cf)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/gro.c (ffffffff81c54168)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/netpoll.c (ffffffff81c5c79c)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (0)
Location: include/linux/skbuff.h:2940
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81c718ae)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netlink/af_netlink.c (ffffffff81cab7c6)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81cb5157)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81cd33eb)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81cdc92d)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdfa09)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff81d168ad)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81d1e4b9)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2940
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81d21614)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff81d25d22)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81d2cac4)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81d2ef2b)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45c92)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2940
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d58ab5)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d606bf)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81d74f72)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81d768d1)
Location: include/linux/skbuff.h:2940
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c203)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81db38c4)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81dbb109)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81dbd487)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffffffff81dc0a05)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81dc1c4b)
Location: include/linux/skbuff.h:2940
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81dcfe5f)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81dd1dbf)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81dd5e31)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_icmp_srh
```
```
In net/ipv6/ip6mr.c (ffffffff81ddea14)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff81de4f28)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6334)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81de84fd)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81debe52)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff81dedfe2)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81df40ba)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_parse_headers
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81e0e46c)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/mctp/route.c (ffffffff81e3aab8)
Location: include/linux/skbuff.h:2940
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_do_fragment_route
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
In drivers/net/tun.c (ffffffff81bf2cdc)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81c05089)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81daafd4)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81dcaf33)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff81dfaee6)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/gro.c (ffffffff81e098f0)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/netpoll.c (ffffffff81e12e8c)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (0)
Location: include/linux/skbuff.h:2832
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81e2999e)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netlink/af_netlink.c (ffffffff81e685d9)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81e736b5)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81e935db)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81e9d38d)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9fda9)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff81edd05d)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81ee5559)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2832
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81ee8a24)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff81eed4a8)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81ef438d)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81ef6f8b)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f059)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2832
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f22ebd)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f2ae5f)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81f421af)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81f4313b)
Location: include/linux/skbuff.h:2832
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a1c3)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81f83264)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81f8b1de)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81f8d9c7)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffffffff81f91194)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81f9259b)
Location: include/linux/skbuff.h:2832
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81fa11e5)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81fa320f)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81fa7641)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_icmp_srh
```
```
In net/ipv6/ip6mr.c (ffffffff81fb0c0d)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff81fb76b8)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9034)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb4c8)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfab2)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc2590)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81fc8ead)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_parse_headers
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81fe48ac)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/mctp/route.c (ffffffff82014088)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_do_fragment_route
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
In drivers/net/tun.c (ffffffff81c49eb1)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81c6a799)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81e1aaef)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81e3babd)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff81e6c0e7)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/gro.c (ffffffff81e7c0c7)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/netpoll.c (ffffffff81e867b6)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (0)
Location: include/linux/skbuff.h:2886
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81e9efdf)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netlink/af_netlink.c (ffffffff81ec4449)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81ed0c13)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_nf
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81ef1d80)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81efa792)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efe5f9)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff81f3c2ad)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81f44d2f)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2886
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81f483e4)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff81f4ce68)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81f53c84)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81f56a08)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6ed58)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2886
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f829fd)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f8ab31)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1997)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa295b)
Location: include/linux/skbuff.h:2886
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81fb9e76)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81fe3566)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81feb8a0)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81fee1a3)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffffffff81ff1a57)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81ff2f07)
Location: include/linux/skbuff.h:2886
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff82001a8d)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff82003ac5)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff82007ea1)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_icmp_srh
```
```
In net/ipv6/ip6mr.c (ffffffff820112c3)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff82017e04)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019794)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8201d156)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020a42)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff82023510)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff8202983c)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_parse_headers
```
```
In net/ncsi/ncsi-cmd.c (ffffffff82060bbc)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/mctp/route.c (ffffffff82090f08)
Location: include/linux/skbuff.h:2886
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_do_fragment_route
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
In drivers/net/tun.c (ffffffff81cff841)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81d1f179)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81ed818f)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81ef9ffd)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff81f2b9d7)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/gro.c (ffffffff81f3c417)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/netpoll.c (ffffffff81f487c3)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (0)
Location: include/linux/skbuff.h:2893
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81f6174f)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netlink/af_netlink.c (ffffffff81f87809)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81f94573)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_nf
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81fb5ed0)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81fbe6cf)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc281c)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff820023d7)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff8200ad81)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2893
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8200e541)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff82012f78)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff8201a044)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8201cea9)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035478)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2893
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8204907d)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82052241)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff8206ecb7)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff8206fc5b)
Location: include/linux/skbuff.h:2893
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff82087331)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff820b1482)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff820b956b)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff820bbd7d)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffffffff820bf656)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff820c0bb7)
Location: include/linux/skbuff.h:2893
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff820d0890)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff820d2875)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff820d6dc1)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_icmp_srh
```
```
In net/ipv6/ip6mr.c (ffffffff820e0253)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff820e6dd4)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8764)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff820ec136)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820efb72)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff820f2600)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff820f9318)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_parse_headers
```
```
In net/ncsi/ncsi-cmd.c (ffffffff82133ad9)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/mctp/route.c (ffffffff82167428)
Location: include/linux/skbuff.h:2893
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_do_fragment_route
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
In drivers/net/tun.c (ffff8000109e15fc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffff800010a08ab4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffff800010bb90a8)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffff800010bd4914)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffff800010c00928)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (ffff800010c115a8)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffff800010c1f304)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netlink/af_netlink.c (ffff800010c4b6cc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffff800010c5358c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffff800010c5cc18)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffff800010c65138)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffff800010c693d4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffff800010c97bbc)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9e9dc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/arp.c (ffff800010ca1350)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffff800010ca50a8)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffff800010caa424)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffff800010cafea8)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc24f4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010cd0048)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd6e18)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffff800010cea2b4)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffff800010ceb708)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffff800010cfc4ec)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffff800010d20a04)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffff800010d26b80)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffff800010d29c10)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffff800010d2cd14)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffff800010d2ff58)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/exthdrs.c (ffff800010d3b8b8)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffff800010d3d680)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffff800010d48088)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffff800010d4d6ec)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f224)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffff800010d50c34)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffff800010d547dc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffff800010d59ea8)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffff800010d74ca4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (c0ac672c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (c0cd5b40)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (c0ceeedc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (c0d125b4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (c0d29454)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (c0d36eac)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netlink/af_netlink.c (c0d5c148)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/bpf/test_run.c (c0d62eec)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (c0d6c368)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (c0d74d0c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (c0d785ac)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (c0da59b4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (c0dabcb4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/arp.c (c0dae22c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (c0db19b4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (c0db6c1c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (c0dbb868)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (c0dcdddc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/ipmr.c (c0dda5f4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (c0de0b58)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (c0df247c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/xfrm/xfrm_output.c (c0df35d0)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (c0e038e4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (c0e25098)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c0e2bd70)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (c0e2d9a8)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (c0e30d70)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (c0e32714)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv6/exthdrs.c (c0e3dfa0)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (c0e40868)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (c0e49aa4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (c0e4edcc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (c0e4ff7c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c0e51788)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (c0e54da8)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (c0e5891c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (c0e71768)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (c000000000aa3350)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (c000000000c91554)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (c000000000cb3a18)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (c000000000ce39fc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (c000000000cfe294)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (c000000000d111a4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netlink/af_netlink.c (c000000000d49910)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/bpf/test_run.c (c000000000d52c58)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (c000000000d5f1d8)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (c000000000d694f4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (c000000000d6df90)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (c000000000da8b10)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/udp.c (c000000000db1180)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/arp.c (c000000000db441c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (c000000000db8dfc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (c000000000dc04dc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (c000000000dc5ddc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dddc18)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000dee2e4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (c000000000df6af8)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (c000000000e0ddac)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/xfrm/xfrm_output.c (c000000000e0f6f0)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (c000000000e24010)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (c000000000e4ee58)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c000000000e578c8)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (c000000000e5aa1c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (c000000000e5e800)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (c000000000e60b80)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv6/exthdrs.c (c000000000e6f134)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (c000000000e719f8)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (c000000000e7d56c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (c000000000e846a4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86a84)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c000000000e88a3c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (c000000000e8d2ec)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (c000000000e9411c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (c000000000eb45d4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (ffffffe00062b120)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffe0007486a0)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffe00075e6f8)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffe00077a602)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (ffffffe00078d77a)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffe000798a72)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netlink/af_netlink.c (ffffffe0007b8dc4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffe0007bde5c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffe0007c5a34)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffe0007cc9ba)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf2f2)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffe0007f6018)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007fb5ca)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/arp.c (ffffffe0007fd8dc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffe0008009de)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffe00080525e)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffe000808f86)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817960)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe000822010)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffe00082770c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffe000837eca)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffe00083907c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffe000846d9a)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffe000862a4e)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffe000868c72)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffe00086a43a)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffffffe00086cf6c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffe00086f6ce)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/exthdrs.c (ffffffe0008781ae)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffe000879dec)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffffffe000881bc0)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffe000886908)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000887d44)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffe000888f96)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c148)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffe00088fda2)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffe0008a4ca2)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (ffffffff8178afce)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81793273)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff818be8b7)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff818d626f)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff818f717b)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (ffffffff8190af22)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff819184dc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netlink/af_netlink.c (ffffffff8193e03c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81943fb5)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff8194c955)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff819547d2)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81957e58)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff81982c3b)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81988f16)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8198b627)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff8198f00c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81994230)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81998039)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8f6e)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819b4380)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819ba400)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff819caeac)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc114)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff819daa4f)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff819fa889)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a011bc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81a031cb)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffffffff81a0643c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81a076b7)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a12433)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81a1430d)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffffffff81a1ca60)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff81a216f1)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a22ab6)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a24214)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81a272a3)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81a2a9e3)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81a4256c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (ffffffff8176a91e)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/vxlan.c (ffffffff81773757)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/core/skbuff.c (ffffffff818787f7)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff818900af)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff818b0fab)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (ffffffff818c4cbd)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff818d228c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netlink/af_netlink.c (ffffffff818f7b3c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff818fdaa5)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81906445)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8190e2c2)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81911948)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff8193c6fb)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819429d6)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819450e7)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff81948acc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff8194dcf0)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81951af9)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962a2e)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967c8f)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/ipv4/ipmr.c (ffffffff819709b0)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819771f0)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81987c9c)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81988f04)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff8199780f)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff819b7649)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819bdf7c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff819bff8b)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffffffff819c31fc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff819c4477)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff819cf1f3)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff819d10cd)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffffffff819d9820)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff819de4b1)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819df876)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819e0fd4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff819e4063)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/ip6_udp_tunnel.c (ffffffff819e5ab3)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_udp_tunnel.c:udp_tunnel6_xmit_skb
```
```
In net/packet/af_packet.c (ffffffff819e7bd3)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff819ff15c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (ffffffff817bb36e)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817c34d3)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8190f8b7)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff8192729f)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff819481ab)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (ffffffff8195bf52)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff8196966c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netlink/af_netlink.c (ffffffff8198f1cc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81995145)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff819b7125)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff819befa2)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c2628)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff819ed40b)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f36e6)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819f5e04)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff819f98ac)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff819fead0)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81a028d9)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1380e)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1ec20)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a24e80)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81a3592c)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a36b94)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a454cf)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81a65309)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a6bc3c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81a6dc4b)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffffffff81a70ebc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81a72137)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a7ceb3)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81a7ed8d)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffffffff81a874e0)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff81a8c171)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d536)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ec94)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81a92e53)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81a96593)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81aae41c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (ffffffff817d43a9)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817dd793)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff819309e7)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81948908)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff81969abb)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (ffffffff8197e332)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff8198ba4c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netlink/af_netlink.c (ffffffff819b1ab4)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff819b7cc5)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff819c09a5)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff819c8925)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cc028)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/raw.c (ffffffff819f72eb)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fd8a6)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81a00004)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffff81a03b9c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81a0a8c1)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81a0ce09)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e1de)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a2a0db)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a302f0)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41297)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42524)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a5119f)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81a71876)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a7824c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81a7a26b)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffffffff81a7d4cc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81a7e767)
Location: include/linux/skbuff.h:2482
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a89703)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/datagram.c (ffffffff81a8b64d)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffffffff81a940b6)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/calipso.c (ffffffff81a99071)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a226)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a9ba04)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9efad)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81aa320d)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81aba7cc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
</details>
</li>
</ul>

## Differences

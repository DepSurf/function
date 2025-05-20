# Function: <code>pskb_may_pull_reason</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
enum skb_drop_reason pskb_may_pull_reason(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c4aad4)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81c4e134)
Location: include/linux/skbuff.h:2668
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c6406d)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/skbuff.c (ffffffff81e1b056)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff81e3a9a3)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81e6c08b)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_generic_pop
```
```
In net/core/sock_reuseport.c (ffffffff81e76ddc)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/gro.c (ffffffff81e7c386)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81eaa489)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff81eea5a5)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
```
```
In net/ipv4/route.c (ffffffff81eec557)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81ef3dc0)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef5d27)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f317c8)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81f3a316)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81f45761)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81f4778c)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81f49c91)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv4/icmp.c (ffffffff81f4ce34)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
```
```
In net/ipv4/af_inet.c (ffffffff81f53ce0)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81f58645)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f2ce)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81f6fe92)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f7c99d)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b563)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f93be6)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa152e)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6919)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff81fa7b9d)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81fb9882)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb2ee)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/ndisc.c (ffffffff81fe4539)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff81fec454)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff81ff1a23)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81ff4cd6)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
Direct callers:
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81ff9a39)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81fff1f4)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff820021e2)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff8200726a)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/seg6.c (ffffffff82007da4)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6.c:seg6_get_srh
```
```
In net/ipv6/ip6mr.c (ffffffff8200d448)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff82012461)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff8201e424)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff820237de)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff82023cab)
Location: include/linux/skbuff.h:2668
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff82025028)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff82028fa4)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
```
In net/strparser/strparser.c (ffffffff82049115)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff820497e1)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
```
In net/mctp/route.c (ffffffff82090edd)
Location: include/linux/skbuff.h:2668
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
```
**Symbols:**

```
ffffffff81ff2730-ffffffff81ff2798: pskb_may_pull_reason (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
enum skb_drop_reason pskb_may_pull_reason(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/netkit.c (ffffffff81ce51ef)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_xmit
```
```
In drivers/net/tun.c (ffffffff81d00438)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81d04199)
Location: include/linux/skbuff.h:2675
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1aa8d)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/skbuff.c (ffffffff81ed8616)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff81ef8d28)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81f2b97b)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_generic_pop
```
```
In net/core/sock_reuseport.c (ffffffff81f36d9c)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/gro.c (ffffffff81f3c6d6)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81f6cf39)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff81fae355)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
```
```
In net/ipv4/route.c (ffffffff81fb05a7)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81fb7d50)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9cd7)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff79bf)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff82000406)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff8200b8b1)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff8200d8cc)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff8200fdb1)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv4/icmp.c (ffffffff82012f44)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
```
```
In net/ipv4/af_inet.c (ffffffff8201a0a0)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8201eb05)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff820359fe)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff820365c2)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8204309d)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff82052e95)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_gro_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:__xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff8206e84e)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
```
```
In net/xfrm/xfrm_device.c (ffffffff82073c09)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff82074e5d)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff82086dc7)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff820886fe)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/ndisc.c (ffffffff820b2439)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff820ba064)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff820bf622)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff820c28a6)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
Direct callers:
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff820c76a9)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cdf04)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff820d0fe2)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff820d60ca)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/seg6.c (ffffffff820d6cc4)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6.c:seg6_get_srh
```
```
In net/ipv6/ip6mr.c (ffffffff820dc415)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e1647)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_gro_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:__xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff820ed554)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff820f2932)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff820f2e0b)
Location: include/linux/skbuff.h:2675
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f4308)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff820f89e4)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
```
In net/strparser/strparser.c (ffffffff8211b495)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff8211bb51)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
```
In net/mctp/route.c (ffffffff821673fd)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
```
**Symbols:**

```
ffffffff820c0390-ffffffff820c03f8: pskb_may_pull_reason (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

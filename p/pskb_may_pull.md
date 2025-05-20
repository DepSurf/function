# Function: <code>pskb_may_pull</code>

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
In drivers/net/ppp/ppp_generic.c (ffffffff815f648f)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/skbuff.c (ffffffff81709978)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff8171b6f9)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff81734374)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff8174012b)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_input.c (ffffffff81758edc)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff8175a534)
Location: include/linux/skbuff.h:1851
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177e24e)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81783242)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81789fe4)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/udp_offload.c (ffffffff8178ae5c)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff8178d267)
Location: include/linux/skbuff.h:1851
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8178eda2)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81793d42)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81797dea)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a4b2d)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff817a4e7a)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff817a8430)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_policy.c (ffffffff817af891)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_input.c (ffffffff817affe9)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff817bb89f)
Location: include/linux/skbuff.h:1851
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff817c6e64)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff817c85d7)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff817e4970)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff817e843b)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff817ecdcf)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_report
```
```
In net/ipv6/reassembly.c (ffffffff817edd66)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f048e)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff817f34dc)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
```
```
In net/ipv6/ip6mr.c (ffffffff817f8cc8)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff817fc4e1)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/ip6_offload.c (ffffffff81800b89)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818014ca)
Location: include/linux/skbuff.h:1851
Inline: True
```
```
In net/ipv6/udp_offload.c (ffffffff818016ba)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff8180271d)
Location: include/linux/skbuff.h:1851
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
In drivers/net/ppp/ppp_generic.c (ffffffff81656912)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/skbuff.c (ffffffff8177183f)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81783f7e)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:__skb_csum_offload_chk
```
```
In net/core/filter.c (ffffffff8179d6ec)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/tso.c (ffffffff8179fe2b)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff817acea6)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_input.c (ffffffff817c527c)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817c698d)
Location: include/linux/skbuff.h:1952
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eb7f4)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff817f0eb2)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff817f7f3d)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff817f8ee6)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff817fa82e)
Location: include/linux/skbuff.h:1952
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff817fc82a)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (ffffffff8180150e)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8180578e)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818128a4)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81812ecb)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81815b10)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8181c7cd)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_input.c (ffffffff8181cf19)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff818287cf)
Location: include/linux/skbuff.h:1952
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81833f39)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81835a3a)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff81852890)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff8185704a)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff8185bd3c)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff8185c5a6)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860364)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81862b13)
Location: include/linux/skbuff.h:1952
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
In net/ipv6/udp_offload.c (ffffffff81866e4f)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff818684b8)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8186bded)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/ip6_offload.c (ffffffff818725f5)
Location: include/linux/skbuff.h:1952
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81872cfa)
Location: include/linux/skbuff.h:1952
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81873a37)
Location: include/linux/skbuff.h:1952
Inline: True
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
In drivers/net/ppp/ppp_generic.c (ffffffff816845f2)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In net/core/skbuff.c (ffffffff8179e96f)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff817b158e)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff817cc14c)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/tso.c (ffffffff817ce7f8)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff817dc4f6)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_input.c (ffffffff817f4d8c)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817f648d)
Location: include/linux/skbuff.h:1967
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c164)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81821c42)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81828ddd)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81829db6)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff8182b6fe)
Location: include/linux/skbuff.h:1967
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8182d78d)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (ffffffff8183231e)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81836bde)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81843da4)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff818443db)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff818472c0)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8184e05f)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_input.c (ffffffff8184e7d9)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a1af)
Location: include/linux/skbuff.h:1967
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81865999)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8186756a)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff81884590)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff81888e4a)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff8188dc3c)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff8188e4b6)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818922f4)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81895123)
Location: include/linux/skbuff.h:1967
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
In net/ipv6/udp_offload.c (ffffffff8189954f)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff8189b308)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8189ec2e)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6be5)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818a731a)
Location: include/linux/skbuff.h:1967
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a80b7)
Location: include/linux/skbuff.h:1967
Inline: True
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
In drivers/net/ppp/ppp_generic.c (ffffffff816999ae)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In net/core/skbuff.c (ffffffff817bd95f)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff817d1a3a)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff817eb073)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_generic_pop
```
```
In net/core/tso.c (ffffffff817edca9)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff817fbb90)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_input.c (ffffffff81815220)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff818168af)
Location: include/linux/skbuff.h:2006
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183c934)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff8184296d)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff8184a0b0)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff8184b02d)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff8184cb02)
Location: include/linux/skbuff.h:2006
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8184ece5)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (ffffffff81854bde)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff818583ed)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81865634)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81865cf0)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81868cb0)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81871c1b)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_input.c (ffffffff818722a9)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff8187e01f)
Location: include/linux/skbuff.h:2006
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81889dab)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8188bcfd)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff818aa1c0)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff818af530)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff818b42ed)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff818b4b05)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8953)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818bb4a3)
Location: include/linux/skbuff.h:2006
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
In net/ipv6/udp_offload.c (ffffffff818bf7ae)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff818c10a8)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff818c516c)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd71b)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818cdd6a)
Location: include/linux/skbuff.h:2006
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ce8f7)
Location: include/linux/skbuff.h:2006
Inline: True
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
In drivers/net/ppp/ppp_generic.c (ffffffff81704146)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In net/core/skbuff.c (ffffffff81836fa9)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff8184bc87)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81866eb3)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_generic_pop
```
```
In net/core/tso.c (ffffffff81869ede)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff8187954a)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_input.c (ffffffff818943ea)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81895a42)
Location: include/linux/skbuff.h:2093
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc07f)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff818c22c5)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff818c9c57)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff818cac8d)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff818cc7bc)
Location: include/linux/skbuff.h:2093
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff818cea65)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (ffffffff818d4a78)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff818d82b6)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e577e)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff818e5e1c)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff818e91ea)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_policy.c (ffffffff818f25d1)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2c89)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff818fef49)
Location: include/linux/skbuff.h:2093
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8190af93)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8190cfd5)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff8192cc28)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff81932240)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81937054)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81937869)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193b7ff)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193e4b5)
Location: include/linux/skbuff.h:2093
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
In net/ipv6/udp_offload.c (ffffffff8194287e)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff819442d2)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81948436)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/seg6_local.c (ffffffff8194f9e0)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff8195250d)
Location: include/linux/skbuff.h:2093
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81952b7a)
Location: include/linux/skbuff.h:2093
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81953797)
Location: include/linux/skbuff.h:2093
Inline: True
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
In drivers/net/ppp/ppp_generic.c (ffffffff81742b7a)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In net/core/skbuff.c (ffffffff81881444)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81896011)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff818b5d8d)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
```
```
In net/core/tso.c (ffffffff818b9bc8)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff818caf44)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_input.c (ffffffff818e8707)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff818e9c68)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff818ef222)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911a93)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81917f12)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff8191fd19)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81920c0e)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81922c5b)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81924e39)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (ffffffff8192b193)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8192dd60)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193c021)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff8193c680)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8193fcf0)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81948f18)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_input.c (ffffffff819495ce)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81955a09)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81962853)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff819643e3)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff81985336)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff8198ab8c)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff8198fd9c)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff819906d6)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994a8f)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819973f8)
Location: include/linux/skbuff.h:2104
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
In net/ipv6/datagram.c (ffffffff81998e96)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffffffff8199b676)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff8199cd98)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a1588)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/seg6_local.c (ffffffff819a9250)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff819aba85)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819ac126)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad1d3)
Location: include/linux/skbuff.h:2104
Inline: True
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
In drivers/net/ppp/ppp_generic.c (ffffffff817673d9)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In net/core/skbuff.c (ffffffff818a1f74)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff818b7e40)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff818dae27)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
```
```
In net/core/tso.c (ffffffff818e0979)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff818f60e1)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_input.c (ffffffff8191512e)
Location: include/linux/skbuff.h:2182
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81916e7f)
Location: include/linux/skbuff.h:2182
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940273)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff8194665b)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff8194e983)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff8194fe7a)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81951a5b)
Location: include/linux/skbuff.h:2182
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81953c51)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (ffffffff81958e15)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8195d62a)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196bd36)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff8196c388)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8196f58d)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8197abe5)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b298)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a4e9)
Location: include/linux/skbuff.h:2182
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8199784c)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81999daf)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819bbab0)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c1460)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff819c6639)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff819c6e00)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb38f)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cdcd2)
Location: include/linux/skbuff.h:2182
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
In net/ipv6/udp_offload.c (ffffffff819d1f40)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff819d45bc)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d81c1)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/seg6_local.c (ffffffff819dfb40)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff819e2625)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e2d03)
Location: include/linux/skbuff.h:2182
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3b7d)
Location: include/linux/skbuff.h:2182
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff819ec0b6)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pskb_may_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817a4be0)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/skbuff.c (ffffffff818ecbe4)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81903ccd)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81927bd7)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
```
```
In net/core/tso.c (ffffffff8192f008)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff81955752)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/route.c (ffffffff81971c35)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (ffffffff8197763e)
Location: include/linux/skbuff.h:2270
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81978e62)
Location: include/linux/skbuff.h:2270
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4796)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff819aacbd)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819b316c)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff819b4729)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff819b6327)
Location: include/linux/skbuff.h:2270
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819b8545)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (ffffffff819bd8e0)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff819c229a)
Location: include/linux/skbuff.h:2270
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
In net/ipv4/ip_tunnel_core.c (ffffffff819d2a86)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff819d319e)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff819d8ccd)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e47c8)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e8932)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4740)
Location: include/linux/skbuff.h:2270
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a038a6)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a05d05)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a2a6f0)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a30235)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81a3544c)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a360f1)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39dd2)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c8e2)
Location: include/linux/skbuff.h:2270
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
In net/ipv6/udp_offload.c (ffffffff81a40d29)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a43438)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e720)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81a512e8)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a51a6a)
Location: include/linux/skbuff.h:2270
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a52901)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/8021q/vlan_core.c (ffffffff81a5b255)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff819f4740-ffffffff819f477d: pskb_may_pull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pskb_may_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817c8ce0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/skbuff.c (ffffffff8191ed04)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81936a9f)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81959f77)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
```
```
In net/core/tso.c (ffffffff8196127c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff8198bbf2)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/route.c (ffffffff819a8705)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (ffffffff819adfce)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819af7d2)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db496)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff819e198d)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819e9eec)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff819eb459)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff819ed047)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819ef245)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (ffffffff819f44f0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff819f8e3a)
Location: include/linux/skbuff.h:2284
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
In net/ipv4/ip_tunnel_core.c (ffffffff81a095f6)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81a09d0e)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a0fa2e)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b7d8)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1f942)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b3f0)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a3a476)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c86d)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a61240)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a66d85)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81a6bf8c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a6cc11)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70962)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a73562)
Location: include/linux/skbuff.h:2284
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
In net/ipv6/udp_offload.c (ffffffff81a779a9)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a79fa8)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81a85390)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87f08)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a8866a)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a894e1)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/8021q/vlan_core.c (ffffffff81a91e85)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81a2b3f0-ffffffff81a2b42d: pskb_may_pull (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff8188da95)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81893651)
Location: include/linux/skbuff.h:2307
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
In net/core/skbuff.c (ffffffff819f1f34)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81a02201)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/core/dev.c:napi_frags_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81a2d9da)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_generic_pop
```
```
In net/ethernet/eth.c (ffffffff81a637f4)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/route.c (ffffffff81a91db5)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81a97e72)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81a9965c)
Location: include/linux/skbuff.h:2307
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac853b)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81acf031)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81ad7aca)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81ad92a4)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81adafa7)
Location: include/linux/skbuff.h:2307
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81add197)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
```
```
In net/ipv4/af_inet.c (ffffffff81ae2db7)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81ae6d09)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8f16)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81afa4d4)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81b032ee)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c878)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11df5)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1dcdf)
Location: include/linux/skbuff.h:2307
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
In net/ipv6/ip6_output.c (ffffffff81b2c606)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
```
```
In net/ipv6/ip6_input.c (ffffffff81b31f0f)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81b5a690)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5f812)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81b64efc)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81b662cd)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a0df)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d9c2)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b71daa)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b75d98)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78c18)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81b7fd40)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81b833c5)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b83c0a)
Location: include/linux/skbuff.h:2307
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b84971)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
```
```
In net/8021q/vlan_core.c (ffffffff81b8d045)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In drivers/net/tun.c (ffffffff8189bfd5)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a1ae1)
Location: include/linux/skbuff.h:2328
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
In net/core/skbuff.c (ffffffff819f1606)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81a02a01)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/core/dev.c:napi_frags_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81a2d419)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_generic_pop
```
```
In net/ethernet/eth.c (ffffffff81a6b949)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/route.c (ffffffff81a9bc47)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81aa1dd2)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa35cc)
Location: include/linux/skbuff.h:2328
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad44db)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81adb007)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81ae411a)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5cc3)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81ae7a62)
Location: include/linux/skbuff.h:2328
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ae9ee7)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
```
```
In net/ipv4/af_inet.c (ffffffff81aefc88)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81af3bd9)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06ddd)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81b07c78)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81b1144e)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1aba8)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b204f5)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c5af)
Location: include/linux/skbuff.h:2328
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
In net/ipv6/ip6_output.c (ffffffff81b3b016)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
```
```
In net/ipv6/ip6_input.c (ffffffff81b40b0f)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81b68d90)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b6dfb2)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81b7369c)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81b74a4d)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78bc0)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b7c472)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b80ae4)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b84b08)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87b98)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f135)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92a78)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b932ba)
Location: include/linux/skbuff.h:2328
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b942d1)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
```
```
In net/8021q/vlan_core.c (ffffffff81b9cca5)
Location: include/linux/skbuff.h:2328
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool pskb_may_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8187e54e)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81883fbe)
Location: include/linux/skbuff.h:2344
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
In net/core/skbuff.c (ffffffff819d6896)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff819f25cc)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81a15438)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_hdr_pop
```
```
In net/ethernet/eth.c (ffffffff81a540b3)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/route.c (ffffffff81a86cb7)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81a8cd02)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e73f)
Location: include/linux/skbuff.h:2344
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf59e)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac6080)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81acf30a)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0fb0)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81ad2d22)
Location: include/linux/skbuff.h:2344
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ad5635)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
```
```
In net/ipv4/af_inet.c (ffffffff81adb3d1)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81adf275)
Location: include/linux/skbuff.h:2344
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
In net/ipv4/ip_tunnel_core.c (ffffffff81af2527)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81af3486)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81aff07e)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b08865)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0e3ba)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a20f)
Location: include/linux/skbuff.h:2344
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
In net/ipv6/ip6_output.c (ffffffff81b2cf19)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e3a5)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81b56e24)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5c37b)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81b5edf9)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
Direct callers:
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81b63570)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67713)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b6af82)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f705)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b73796)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b76855)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81b7ee85)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81bcd)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b8235a)
Location: include/linux/skbuff.h:2344
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b833d8)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81b8577c)
Location: include/linux/skbuff.h:2344
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff81b8bd89)
Location: include/linux/skbuff.h:2344
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81b5cc50-ffffffff81b5cc8a: pskb_may_pull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool pskb_may_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8190fd5b)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8191597e)
Location: include/linux/skbuff.h:2373
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
In net/core/skbuff.c (ffffffff81a86ee6)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81aa449c)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81ac6458)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_hdr_pop
```
```
In net/ethernet/eth.c (ffffffff81b0cdc3)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/route.c (ffffffff81b41477)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81b47e3a)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81b4992f)
Location: include/linux/skbuff.h:2373
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d0e6)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81b84890)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81b8dd2a)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f9cd)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81b91972)
Location: include/linux/skbuff.h:2373
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81b9446c)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
```
```
In net/ipv4/af_inet.c (ffffffff81b9a781)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81b9e755)
Location: include/linux/skbuff.h:2373
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
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2a37)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81bb3996)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81bc225e)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb765)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd18a1)
Location: include/linux/skbuff.h:2373
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
In net/xfrm/xfrm_input.c (ffffffff81bde82f)
Location: include/linux/skbuff.h:2373
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
In net/ipv6/ip6_output.c (ffffffff81bf307b)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81bf469b)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81c1d044)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff81c23ab0)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81c2659e)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
Direct callers:
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81c2b030)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f343)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81c32de2)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81c377c2)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/seg6.c (ffffffff81c38124)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6.c:seg6_get_srh
```
```
In net/ipv6/ip6mr.c (ffffffff81c3dd66)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c412d5)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a625)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4dc1d)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e40a)
Location: include/linux/skbuff.h:2373
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f4a8)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81c51af1)
Location: include/linux/skbuff.h:2373
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff81c58069)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81c244a0-ffffffff81c244da: pskb_may_pull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool pskb_may_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a669a5)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6baed)
Location: include/linux/skbuff.h:2741
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
In net/core/skbuff.c (ffffffff81bfc656)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81c18e49)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81c423c8)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_hdr_pop
```
```
In net/core/gro.c (ffffffff81c54470)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81c936e2)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/route.c (ffffffff81ccde77)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81cd50f0)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6f57)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d063)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81d150d4)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81d1ee51)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81d20c84)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81d22e61)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv4/icmp.c (ffffffff81d25cf9)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
```
```
In net/ipv4/af_inet.c (ffffffff81d2cb20)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81d30ac5)
Location: include/linux/skbuff.h:2741
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
In net/ipv4/ip_tunnel_core.c (ffffffff81d461fe)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81d470b4)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81d52b6d)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d61223)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d67a07)
Location: include/linux/skbuff.h:2741
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
In net/xfrm/xfrm_input.c (ffffffff81d7567f)
Location: include/linux/skbuff.h:2741
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
In net/ipv6/ip6_output.c (ffffffff81d8bc38)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d439)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81dbbb94)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff81dc09dc)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81dc41f6)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
Direct callers:
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81dc82d9)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcd625)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81dd05c2)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81dd5354)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/seg6.c (ffffffff81dd5d44)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6.c:seg6_get_srh
```
```
In net/ipv6/ip6mr.c (ffffffff81ddad28)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddfa63)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81de9f14)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee2db)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81deeccb)
Location: include/linux/skbuff.h:2741
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81defee8)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81df36b4)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
```
In net/8021q/vlan_core.c (ffffffff81df9759)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
```
In net/mctp/route.c (ffffffff81e3aa8d)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
```
**Symbols:**

```
ffffffff81dc1620-ffffffff81dc1676: pskb_may_pull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool pskb_may_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bf1e6c)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfea0d)
Location: include/linux/skbuff.h:2624
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
In net/core/skbuff.c (ffffffff81dab556)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff81dc9e10)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81dfae8a)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_generic_pop
```
```
In net/core/sock_reuseport.c (ffffffff81e0458c)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/gro.c (ffffffff81e09bc0)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81e4ede9)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/route.c (ffffffff81e8de17)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81e955c0)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81e974f7)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2ae1)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81edb1fb)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81ee5f61)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7efe)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81eea361)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv4/icmp.c (ffffffff81eed474)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
```
```
In net/ipv4/af_inet.c (ffffffff81ef43e9)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81ef8bd5)
Location: include/linux/skbuff.h:2624
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
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f5de)
Location: include/linux/skbuff.h:2624
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
In net/ipv4/gre_offload.c (ffffffff81f101a2)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f1cebd)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2bb23)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f32a67)
Location: include/linux/skbuff.h:2624
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
In net/xfrm/xfrm_input.c (ffffffff81f41c9f)
Location: include/linux/skbuff.h:2624
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
In net/xfrm/xfrm_device.c (ffffffff81f46f19)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff81f4809d)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81f59bd0)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b520)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/ndisc.c (ffffffff81f84240)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff81f8bcb4)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff81f91160)
Location: include/linux/skbuff.h:2624
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
In net/ipv6/mcast.c (ffffffff81f94356)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
Direct callers:
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81f99069)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e738)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81fa1972)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81fa6a5d)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/seg6.c (ffffffff81fa7544)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6.c:seg6_get_srh
```
```
In net/ipv6/ip6mr.c (ffffffff81faca38)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1d53)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81fbd794)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc2860)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2d2b)
Location: include/linux/skbuff.h:2624
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc4008)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81fc8484)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
```
In net/strparser/strparser.c (ffffffff81fcd7e5)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81fcdeb1)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
```
In net/mctp/route.c (ffffffff8201405d)
Location: include/linux/skbuff.h:2624
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
```
**Symbols:**

```
ffffffff81f91e10-ffffffff81f91e66: pskb_may_pull (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff81c4aad4)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81c4e134)
Location: include/linux/skbuff.h:2682
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c6406d)
Location: include/linux/skbuff.h:2682
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
Location: include/linux/skbuff.h:2682
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
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81e6c08b)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_generic_pop
```
```
In net/core/sock_reuseport.c (ffffffff81e76ddc)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/gro.c (ffffffff81e7c386)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81eaa489)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff81eea5a5)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
```
```
In net/ipv4/route.c (ffffffff81eec557)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81ef3dc0)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef5d27)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f317c8)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81f3a316)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81f45761)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81f4778c)
Location: include/linux/skbuff.h:2682
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
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv4/icmp.c (ffffffff81f4ce34)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
```
```
In net/ipv4/af_inet.c (ffffffff81f53ce0)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81f58645)
Location: include/linux/skbuff.h:2682
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
Location: include/linux/skbuff.h:2682
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
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f7c99d)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b563)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f93be6)
Location: include/linux/skbuff.h:2682
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
Location: include/linux/skbuff.h:2682
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
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff81fa7b9d)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81fb9882)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb2ee)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/ndisc.c (ffffffff81fe4539)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff81fec454)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff81ff1a23)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81ff4cd6)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81ff9a39)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81fff1f4)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff820021e2)
Location: include/linux/skbuff.h:2682
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
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/seg6.c (ffffffff82007da4)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6.c:seg6_get_srh
```
```
In net/ipv6/ip6mr.c (ffffffff8200d448)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff82012461)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff8201e424)
Location: include/linux/skbuff.h:2682
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
Location: include/linux/skbuff.h:2682
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
Location: include/linux/skbuff.h:2682
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff82025028)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff82028fa4)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
```
In net/strparser/strparser.c (ffffffff82049115)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff820497e1)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
```
In net/mctp/route.c (ffffffff82090edd)
Location: include/linux/skbuff.h:2682
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
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
In drivers/net/netkit.c (ffffffff81ce51ef)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_xmit
```
```
In drivers/net/tun.c (ffffffff81d00438)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81d04199)
Location: include/linux/skbuff.h:2689
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1aa8d)
Location: include/linux/skbuff.h:2689
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
Location: include/linux/skbuff.h:2689
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
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81f2b97b)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_generic_pop
```
```
In net/core/sock_reuseport.c (ffffffff81f36d9c)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/gro.c (ffffffff81f3c6d6)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81f6cf39)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff81fae355)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
```
```
In net/ipv4/route.c (ffffffff81fb05a7)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81fb7d50)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9cd7)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff79bf)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff82000406)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff8200b8b1)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff8200d8cc)
Location: include/linux/skbuff.h:2689
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
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv4/icmp.c (ffffffff82012f44)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
```
```
In net/ipv4/af_inet.c (ffffffff8201a0a0)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8201eb05)
Location: include/linux/skbuff.h:2689
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
Location: include/linux/skbuff.h:2689
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
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8204309d)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff82052e95)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_gro_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:__xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff8206e84e)
Location: include/linux/skbuff.h:2689
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
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff82074e5d)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff82086dc7)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff820886fe)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/ndisc.c (ffffffff820b2439)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff820ba064)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff820bf622)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff820c28a6)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff820c76a9)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cdf04)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff820d0fe2)
Location: include/linux/skbuff.h:2689
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
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/seg6.c (ffffffff820d6cc4)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6.c:seg6_get_srh
```
```
In net/ipv6/ip6mr.c (ffffffff820dc415)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e1647)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_gro_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:__xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff820ed554)
Location: include/linux/skbuff.h:2689
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
Location: include/linux/skbuff.h:2689
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
Location: include/linux/skbuff.h:2689
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f4308)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff820f89e4)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
```
In net/strparser/strparser.c (ffffffff8211b495)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff8211bb51)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
```
In net/mctp/route.c (ffffffff821673fd)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pskb_may_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffff800010a03104)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/skbuff.c (ffff800010bb9520)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffff800010bd51d0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffff800010bfbb4c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
```
```
In net/core/tso.c (ffff800010c04b5c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffff800010c36c64)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/route.c (ffff800010c58014)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (ffff800010c5e018)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffff800010c60014)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e888)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffff800010c95990)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffff800010c9f6ec)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffff800010ca0fc0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffff800010ca2ac4)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/icmp.c (ffff800010ca5090)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (ffff800010caa494)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffff800010cae608)
Location: include/linux/skbuff.h:2284
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
In net/ipv4/ip_tunnel_core.c (ffff800010cc29a4)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffff800010cc2f98)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffff800010ccca2c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd7a3c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdb5b0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (ffff800010ce9c00)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/ip6_output.c (ffff800010cfb438)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffff800010cfdfb8)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffff800010d2449c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffff800010d2ccfc)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffff800010d339f4)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffff800010d358f4)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38e58)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffff800010d3c028)
Location: include/linux/skbuff.h:2284
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
In net/ipv6/udp_offload.c (ffff800010d41010)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffff800010d45be0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/seg6_local.c (ffff800010d513f0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/ip6_offload.c (ffff800010d54a98)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffff800010d55220)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffff800010d5630c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/8021q/vlan_core.c (ffff800010d5fb34)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffff800010ce9c00-ffff800010ce9c4c: pskb_may_pull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pskb_may_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c0addf44)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/skbuff.c (c0cd5fb4)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (c0cef5a8)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (c0d16604)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
```
```
In net/core/tso.c (c0d1df94)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (c0d495a8)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/route.c (c0d67c1c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (c0d6d904)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (c0d6f800)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (c0d9d7d4)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (c0da4118)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (c0daca10)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (c0dad3fc)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (c0daf928)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/icmp.c (c0db1998)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (c0db6c4c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (c0dbc90c)
Location: include/linux/skbuff.h:2284
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
In net/ipv4/ip_tunnel_core.c (c0dce1d0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (c0dce8bc)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (c0dd7034)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (c0de1548)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (c0de6360)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (c0df22b8)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/ipv6/ip6_output.c (c0e02090)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c0e05538)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (c0e2b300)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (c0e30d58)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (c0e3668c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (c0e37b9c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (c0e3b9f4)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (c0e3f248)
Location: include/linux/skbuff.h:2284
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
In net/ipv6/udp_offload.c (c0e438f4)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (c0e465cc)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/seg6_local.c (c0e51fac)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/ip6_offload.c (c0e550a8)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (c0e557b4)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/mcast_snoop.c (c0e568f4)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/8021q/vlan_core.c (c0e5f6ac)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
c0df1e10-c0df1e5c: pskb_may_pull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pskb_may_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c000000000aa90d0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/skbuff.c (c000000000c91ad4)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (c000000000cb45d0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (c000000000ce6904)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
```
```
In net/core/tso.c (c000000000ceeb34)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (c000000000d2f240)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/route.c (c000000000d5992c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (c000000000d60c40)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (c000000000d62dfc)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d2b4)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (c000000000da6c10)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (c000000000db21bc)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (c000000000db3ef0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (c000000000db620c)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/icmp.c (c000000000db8dd4)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (c000000000dc0560)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (c000000000dc69e4)
Location: include/linux/skbuff.h:2284
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
In net/ipv4/ip_tunnel_core.c (c000000000dde228)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (c000000000dde680)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (c000000000de762c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (c000000000df798c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (c000000000e008f8)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (c000000000e0d790)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/ip6_output.c (c000000000e22a70)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c000000000e25d70)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (c000000000e56d20)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (c000000000e5e7d8)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (c000000000e660fc)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (c000000000e679c8)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c334)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (c000000000e6fb3c)
Location: include/linux/skbuff.h:2284
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
In net/ipv6/udp_offload.c (c000000000e758a0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (c000000000e78e84)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/seg6_local.c (c000000000e894bc)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/ip6_offload.c (c000000000e8d620)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (c000000000e8dfac)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f4cc)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/8021q/vlan_core.c (c000000000e9a880)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
c000000000e0d790-c000000000e0d808: pskb_may_pull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pskb_may_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffe00062d528)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/skbuff.c (ffffffe000748aa0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffe00075ec48)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffe00077e176)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
```
```
In net/core/tso.c (ffffffe000783736)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffe0007a863c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/route.c (ffffffe0007c2286)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (ffffffe0007c6bca)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c80c8)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eeb92)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f4be4)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffe0007fc21c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd518)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffe0007fea46)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/icmp.c (ffffffe0008009c8)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (ffffffe0008052d8)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffe0008099c4)
Location: include/linux/skbuff.h:2284
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
In net/ipv4/ip_tunnel_core.c (ffffffe000817dfc)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffe0008183e6)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffe00081e2a2)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffe0008280d6)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082cfd4)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (ffffffe000837b52)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffe000845f10)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffe000848034)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffe000867fce)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffe00086cf54)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffe000871c34)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffe000872d9c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087623a)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffe000878a54)
Location: include/linux/skbuff.h:2284
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
In net/ipv6/udp_offload.c (ffffffe00087c6b0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffe00087ed18)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/seg6_local.c (ffffffe00088962e)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c41a)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffe00088ca44)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088dbae)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/8021q/vlan_core.c (ffffffe0008950ee)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffe000837b52-ffffffe000837b8a: pskb_may_pull (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pskb_may_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff8178d7c0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/skbuff.c (ffffffff818bed04)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff818d6a6f)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff818f9f47)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
```
```
In net/core/tso.c (ffffffff8190124c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff8192ba62)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/route.c (ffffffff81948575)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (ffffffff8194de3e)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff8194f642)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b306)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff819817fd)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81989d5c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff8198b2c9)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff8198cdf8)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8198efe5)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (ffffffff81994290)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81998bda)
Location: include/linux/skbuff.h:2284
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
In net/ipv4/ip_tunnel_core.c (ffffffff819a9396)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff819a9aae)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff819af45d)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff819bae68)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff819befd2)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (ffffffff819caa80)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819d9b06)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff819dbefd)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a008d0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a06415)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81a0b61c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a0c2a1)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0fff2)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a12bf2)
Location: include/linux/skbuff.h:2284
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
In net/ipv6/udp_offload.c (ffffffff81a17039)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a19638)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81a24a20)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81a27598)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a27cfa)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28b71)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/8021q/vlan_core.c (ffffffff81a31515)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff819caa80-ffffffff819caabd: pskb_may_pull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pskb_may_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/vxlan.c (ffffffff81773ee6)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:route_shortcircuit
  - drivers/net/vxlan.c:route_shortcircuit
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:vxlan_err_lookup
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81776590)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/skbuff.c (ffffffff81878c44)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff818908af)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff818b3d77)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
```
```
In net/core/tso.c (ffffffff818bb07c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff818e5812)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/route.c (ffffffff81902065)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (ffffffff8190792e)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81909132)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934dc6)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff8193b2bd)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff8194381c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81944d89)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff819468b8)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81948aa5)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (ffffffff8194dd50)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8195269a)
Location: include/linux/skbuff.h:2284
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
In net/ipv4/ip_tunnel_core.c (ffffffff81962e56)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff8196356e)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8196ba8d)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977c58)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197bdc2)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (ffffffff81987870)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819968c6)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81998cbd)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819bd690)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c31d5)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff819c83dc)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff819c9061)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ccdb2)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cf9b2)
Location: include/linux/skbuff.h:2284
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
In net/ipv6/udp_offload.c (ffffffff819d3df9)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff819d63f8)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff819e17e0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff819e4358)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e4aba)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5d61)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/8021q/vlan_core.c (ffffffff819ee705)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81987870-ffffffff819878ad: pskb_may_pull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pskb_may_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817bdb60)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/skbuff.c (ffffffff8190fd04)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81927a9f)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff8194af77)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
```
```
In net/core/tso.c (ffffffff8195227c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff8197cbf2)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/route.c (ffffffff819b2d45)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (ffffffff819b860e)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9e12)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5ad6)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff819ebfcd)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819f452c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff819f5a99)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff819f7687)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819f9885)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (ffffffff819feb30)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81a0347a)
Location: include/linux/skbuff.h:2284
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
In net/ipv4/ip_tunnel_core.c (ffffffff81a13c36)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81a1434e)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a19cfd)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a258e8)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a29a52)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35500)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a44586)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a4697d)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a6b350)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a70e95)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81a7609c)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a76d21)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7aa72)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a7d672)
Location: include/linux/skbuff.h:2284
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
In net/ipv6/udp_offload.c (ffffffff81a81ab9)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a840b8)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f4a0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a91231)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather
```
```
In net/ipv6/ip6_offload.c (ffffffff81a93148)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a938aa)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a94721)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/8021q/vlan_core.c (ffffffff81a9d0c5)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81a35500-ffffffff81a3553d: pskb_may_pull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pskb_may_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817d8390)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/skbuff.c (ffffffff81930e34)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff8194916f)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff8196c887)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
```
```
In net/core/tso.c (ffffffff81973cbc)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff8199f160)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/route.c (ffffffff819bc407)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (ffffffff819c1e6e)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819c3852)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef796)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5e7d)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819fe6ec)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff819ffc99)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81a018a7)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81a03b75)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (ffffffff81a0a6aa)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81a0d9ca)
Location: include/linux/skbuff.h:2284
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
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e616)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81a1ed52)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a24b1e)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30d78)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a34fe2)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (ffffffff81a40de0)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a50248)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a526ad)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a77960)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a7d4a5)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81a827cc)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a83341)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a872b2)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a89ec2)
Location: include/linux/skbuff.h:2284
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
In net/ipv6/udp_offload.c (ffffffff81a8e3b9)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a909e8)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81a9c220)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f1c2)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9f9fa)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa0881)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/8021q/vlan_core.c (ffffffff81aa92b5)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81a40de0-ffffffff81a40e1d: pskb_may_pull (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

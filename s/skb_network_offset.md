# Function: <code>skb_network_offset</code>

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
In security/selinux/hooks.c (ffffffff81348f1d)
Location: include/linux/skbuff.h:2098
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81361e32)
Location: include/linux/skbuff.h:2098
Inline: True
```
```
In security/lsm_audit.c (0)
Location: include/linux/skbuff.h:2098
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:2098
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81712051)
Location: include/linux/skbuff.h:2098
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81719790)
Location: include/linux/skbuff.h:2098
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff817258c6)
Location: include/linux/skbuff.h:2098
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/tso.c (ffffffff817340de)
Location: include/linux/skbuff.h:2098
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (0)
Location: include/linux/skbuff.h:2098
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff8175993d)
Location: include/linux/skbuff.h:2098
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8175f0b5)
Location: include/linux/skbuff.h:2098
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2098
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2098
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8178f1d7)
Location: include/linux/skbuff.h:2098
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81797dd3)
Location: include/linux/skbuff.h:2098
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff817c7df2)
Location: include/linux/skbuff.h:2098
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff817c85af)
Location: include/linux/skbuff.h:2098
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff817e782d)
Location: include/linux/skbuff.h:2098
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/skbuff.h:2098
Inline: True
```
```
In net/ipv6/exthdrs_core.c (ffffffff817ffd1c)
Location: include/linux/skbuff.h:2098
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/output_core.c (ffffffff818007fc)
Location: include/linux/skbuff.h:2098
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/skbuff.h:2098
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2098
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff818026fa)
Location: include/linux/skbuff.h:2098
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81806b12)
Location: include/linux/skbuff.h:2098
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In security/selinux/hooks.c (ffffffff8137e00d)
Location: include/linux/skbuff.h:2233
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81397f82)
Location: include/linux/skbuff.h:2233
Inline: True
```
```
In security/lsm_audit.c (ffffffff8139c3ad)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81771e7a)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/flow_dissector.c (ffffffff81779a33)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81781c70)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff8178f366)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/tso.c (ffffffff8179fbae)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff817a8204)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_fragment.c (ffffffff817c5c45)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff817cb325)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff817f106d)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff817f8da9)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff817fc83b)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/igmp.c (ffffffff8180577a)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff81834f32)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81835a31)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/icmp.c (ffffffff8185705b)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/udp_offload.c (ffffffff81866d0c)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81867e27)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/exthdrs_core.c (ffffffff818713bd)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/output_core.c (ffffffff81871f1c)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81872b7e)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81873a0a)
Location: include/linux/skbuff.h:2233
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818785cc)
Location: include/linux/skbuff.h:2233
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In security/selinux/hooks.c (ffffffff81394a9d)
Location: include/linux/skbuff.h:2250
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff813aeb62)
Location: include/linux/skbuff.h:2250
Inline: True
```
```
In security/lsm_audit.c (ffffffff813b2f5d)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff8179ef95)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/flow_dissector.c (ffffffff817a6a68)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff817af580)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff817bcc16)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff817cb490)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff817ce57e)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff817d6d52)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_fragment.c (ffffffff817f5745)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff817faf85)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81821dfd)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81829c79)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff8182d79e)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81836bca)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff81866a68)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81867561)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/icmp.c (ffffffff81888e5b)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff8188ea5c)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff8189940c)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff8189ac87)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/exthdrs_core.c (ffffffff818a590c)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/output_core.c (ffffffff818a64fc)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818a719e)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a808a)
Location: include/linux/skbuff.h:2250
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818ace22)
Location: include/linux/skbuff.h:2250
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In security/selinux/hooks.c (ffffffff813aab47)
Location: include/linux/skbuff.h:2299
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff813c3573)
Location: include/linux/skbuff.h:2299
Inline: True
```
```
In security/lsm_audit.c (ffffffff813c992d)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff817bc6f1)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/flow_dissector.c (ffffffff817c4dcf)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff817cde90)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff817db2dd)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff817eaca8)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/tso.c (ffffffff817eda2e)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff817f6dc2)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_fragment.c (ffffffff81815be1)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8181b626)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81842a7b)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8184af9c)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff8184ecf6)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81857c2a)
Location: include/linux/skbuff.h:2299
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8188b484)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff8188bcf4)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/icmp.c (ffffffff818af541)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff818b4db8)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff818bf72a)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff818c16e0)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/exthdrs_core.c (ffffffff818cc38c)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/output_core.c (ffffffff818ccf57)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818cdc0b)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ce8ca)
Location: include/linux/skbuff.h:2299
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d55a5)
Location: include/linux/skbuff.h:2299
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In security/selinux/hooks.c (ffffffff813d0ba7)
Location: include/linux/skbuff.h:2386
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff813e9833)
Location: include/linux/skbuff.h:2386
Inline: True
```
```
In security/lsm_audit.c (ffffffff813efdbd)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81836da6)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/flow_dissector.c (ffffffff8183e8bf)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff8184ab64)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81855a9d)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81867749)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/tso.c (ffffffff81869c6e)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff818733a5)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_fragment.c (ffffffff81894dbc)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8189a55c)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff818c23db)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff818cabfc)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff818cea7c)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/igmp.c (ffffffff818d73ea)
Location: include/linux/skbuff.h:2386
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8190c6d4)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff8190cfdf)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/ndisc.c (ffffffff8192a4f5)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff81932257)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81937b28)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff819427fa)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81944a61)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/exthdrs_core.c (ffffffff8195113c)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/output_core.c (ffffffff81951d43)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81952a0b)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff8195377a)
Location: include/linux/skbuff.h:2386
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8195a055)
Location: include/linux/skbuff.h:2386
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In security/selinux/hooks.c (ffffffff813fde1e)
Location: include/linux/skbuff.h:2398
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8141a752)
Location: include/linux/skbuff.h:2398
Inline: True
```
```
In security/lsm_audit.c (ffffffff81421364)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81880eff)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/flow_dissector.c (ffffffff8188927b)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81894f44)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff818a15c0)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff818b57bc)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/tso.c (ffffffff818b994f)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff818c4b1f)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_fragment.c (ffffffff818e8ee1)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff818eea0b)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff8191803a)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81920b3c)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81924e52)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/igmp.c (ffffffff8192dd25)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff81963b69)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff819643d3)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/ndisc.c (ffffffff81982710)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff8198aba5)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81990ac3)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff8199b5d6)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff8199d7a0)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/exthdrs_core.c (ffffffff819aa6ee)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/output_core.c (ffffffff819ab2e8)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819abfc9)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad1b6)
Location: include/linux/skbuff.h:2398
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819af067)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In security/selinux/hooks.c (ffffffff81419cce)
Location: include/linux/skbuff.h:2476
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81436b32)
Location: include/linux/skbuff.h:2476
Inline: True
```
```
In security/lsm_audit.c (ffffffff8143da04)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff818a1d96)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/flow_dissector.c (ffffffff818a9ac3)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818b5a24)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff818c38fd)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff818dc3c0)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/tso.c (ffffffff818e070f)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff818edb8f)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_fragment.c (ffffffff819160b6)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8191c1ab)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff8194678a)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff8194da9f)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff8194ff12)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81953c64)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff8195d5f5)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff81998b0d)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81999d9e)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff819b8dbd)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff819bc45e)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff819c1473)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff819c7201)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff819d1ff0)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff819d42fa)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/exthdrs_core.c (ffffffff819e11ee)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/output_core.c (ffffffff819e1e08)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e2ba9)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3b63)
Location: include/linux/skbuff.h:2476
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e5a31)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In security/selinux/hooks.c (ffffffff81447721)
Location: include/linux/skbuff.h:2562
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814647f2)
Location: include/linux/skbuff.h:2562
Inline: True
```
```
In security/lsm_audit.c (ffffffff8146b5c3)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff818ec77f)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/flow_dissector.c (ffffffff818f5a2e)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818ff38c)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff8190faad)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff819294c0)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/tso.c (ffffffff8192ed9c)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff8193e4c5)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff81971c18)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_fragment.c (ffffffff81978216)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff8197e4d4)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff819aadeb)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff819b22b9)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819b47d0)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff819b855c)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff819c2265)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6245)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a04977)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81a05cf4)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81a27845)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81a2af8a)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a3024c)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81a36360)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a40dcc)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a43183)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a4ffbe)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/output_core.c (ffffffff81a50b9f)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a518f2)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a52990)
Location: include/linux/skbuff.h:2562
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a55463)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In security/selinux/hooks.c (ffffffff814612b1)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8147e5c2)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In security/lsm_audit.c (ffffffff814853a3)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff8191e8af)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/flow_dissector.c (ffffffff8192792b)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff819316f3)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff8194211d)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff8195bb9c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/tso.c (ffffffff8196100c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81971355)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff819a86e8)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_fragment.c (ffffffff819aeb86)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff819b4e80)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1abb)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff819e9059)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819eb500)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff819ef25c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff819f8e05)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2cec5)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b568)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c85c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81a5e2a5)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81a61aea)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a66d9c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81a6ce80)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a77a4c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a79ce3)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a86c0e)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/output_core.c (ffffffff81a8778f)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a884f2)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a89570)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a8c533)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In security/selinux/hooks.c (ffffffff814b42bb)
Location: include/linux/skbuff.h:2599
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814d3e60)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff814db543)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff819f06d7)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff819fbbd3)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a06e73)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81a1207d)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a2ed8f)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/tso.c (ffffffff81a3458d)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81a452ad)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff81a91d98)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_fragment.c (ffffffff81a98fa6)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81a9f07d)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81acf12b)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81ad3b45)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err_encap
```
```
In net/ipv4/udp_offload.c (ffffffff81ad91be)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81add1ae)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81ae6815)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:ip_mc_check_iphdr
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1edcd)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
```
```
In net/ipv6/ip6_output.c (ffffffff81b30b33)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81b31efe)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81b57082)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81b5a2b5)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err_encap
```
```
In net/ipv6/icmp.c (ffffffff81b5f829)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81b65df9)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/udp_offload.c (ffffffff81b71cc3)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81b7485a)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/exthdrs_core.c (ffffffff81b81ebe)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b82722)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81b82bdb)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b83a93)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b84b20)
Location: include/linux/skbuff.h:2599
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b878f8)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In security/selinux/hooks.c (ffffffff814d1a1b)
Location: include/linux/skbuff.h:2625
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814f1330)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff814f89d3)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff819f15da)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff819fb2e5)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a083f3)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81a1241d)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a308a1)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/tso.c (ffffffff81a36885)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81a494c2)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/sched/sch_frag.c (ffffffff81a6f634)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_frag_prepare_frag
```
```
In net/ipv4/route.c (ffffffff81a9bc2a)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa2f16)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81aa8fbd)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81adb136)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81adfc55)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err_encap
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5bd5)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81ae9efe)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81af36e5)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:ip_mc_check_iphdr
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2d67d)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f763)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81b40afe)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81b656f2)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81b689ec)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err_encap
```
```
In net/ipv6/icmp.c (ffffffff81b6dfc9)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81b74569)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/udp_offload.c (ffffffff81b809f8)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81b835d0)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/exthdrs_core.c (ffffffff81b915ae)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b91d8e)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81b9225b)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b9314b)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b94480)
Location: include/linux/skbuff.h:2625
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b973d8)
Location: include/linux/skbuff.h:2625
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In security/selinux/hooks.c (ffffffff814d7ecb)
Location: include/linux/skbuff.h:2641
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814f7fd0)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff814ff743)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff819d686a)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff819e1537)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff819eeb53)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff819f904d)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a1a59f)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/tso.c (ffffffff81a1d9f6)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81a2e424)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/sched/sch_frag.c (ffffffff81a57f04)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_frag_prepare_frag
```
```
In net/ipv4/route.c (ffffffff81a86c9a)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8df26)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81a940b3)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac6182)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81ace8fe)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0eca)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81ad564c)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81adf245)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1b339)
Location: include/linux/skbuff.h:2641
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d604)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e396)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81b539b2)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81b572a4)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81b5c392)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81b62fc8)
Location: include/linux/skbuff.h:2641
Inline: True
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f618)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81b72243)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/exthdrs_core.c (ffffffff81b807a6)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b80fe2)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81b813c2)
Location: include/linux/skbuff.h:2641
Inline: True
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b821e4)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b83602)
Location: include/linux/skbuff.h:2641
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b863d4)
Location: include/linux/skbuff.h:2641
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In security/selinux/hooks.c (ffffffff81530e8b)
Location: include/linux/skbuff.h:2670
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81552bc0)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff8155a7b3)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81a86eba)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff81a91977)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a9fe73)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81aaac2d)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81acc87f)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/tso.c (ffffffff81ad1477)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81ae3a04)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/sched/sch_frag.c (ffffffff81b10ed4)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_frag_prepare_frag
```
```
In net/ipv4/route.c (ffffffff81b4145a)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_fragment.c (ffffffff81b49116)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81b4f4f8)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81b84992)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81b8d2cb)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f8e7)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81b94483)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81b9e725)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff81bdfba9)
Location: include/linux/skbuff.h:2670
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81bf37a7)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81bf468c)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81c1aee9)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81c1e87e)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81c23ac7)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81c2aa78)
Location: include/linux/skbuff.h:2670
Inline: True
```
```
In net/ipv6/udp_offload.c (ffffffff81c376d5)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c71d)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/exthdrs_core.c (ffffffff81c4c7c6)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/ip6_icmp.c (ffffffff81c4d002)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81c4d3e2)
Location: include/linux/skbuff.h:2670
Inline: True
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e294)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f6d2)
Location: include/linux/skbuff.h:2670
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c52794)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In security/selinux/hooks.c (ffffffff815c8388)
Location: include/linux/skbuff.h:3039
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff815ec73d)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff815f5530)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81bfc62a)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff81c07bb4)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81c15933)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81c23b7d)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81c49741)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/tso.c (ffffffff81c4ed5a)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81c671df)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/sched/sch_frag.c (ffffffff81c97f95)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_frag_prepare_frag
```
```
In net/ipv4/route.c (ffffffff81ccde74)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6e9b)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81cdce7c)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81d151fb)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81d1e47b)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81d20bda)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81d25d0c)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81d30a95)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45fa5)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/xfrm/xfrm_output.c (ffffffff81d76a8d)
Location: include/linux/skbuff.h:3039
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c35a)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d42a)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81db750c)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81dbb0d3)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81dc09ef)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81dc7f67)
Location: include/linux/skbuff.h:3039
Inline: True
```
```
In net/ipv6/udp_offload.c (ffffffff81dd52da)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81ddab09)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/exthdrs_core.c (ffffffff81decba0)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/ip6_icmp.c (ffffffff81ded4b8)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81ded948)
Location: include/linux/skbuff.h:3039
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee81a)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81deeb49)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81df0120)
Location: include/linux/skbuff.h:3039
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df576d)
Location: include/linux/skbuff.h:3039
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In security/selinux/hooks.c (ffffffff816754a8)
Location: include/linux/skbuff.h:2933
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8169c43d)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff816a6015)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81dab52a)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff81db7663)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81dc6cf3)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81dd60ed)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81dfe75c)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/tso.c (ffffffff81e03deb)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81e1e2fb)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/sched/sch_frag.c (ffffffff81e53f45)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_frag_prepare_frag
```
```
In net/ipv4/route.c (ffffffff81e8de14)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_fragment.c (ffffffff81e9743b)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81e9d8ec)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81edb3db)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81ee551b)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7e54)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81eed487)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81ef8ba5)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f385)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/xfrm/xfrm_output.c (ffffffff81f432bd)
Location: include/linux/skbuff.h:2933
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a31a)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b511)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81f871e1)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81f8b1a8)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81f91173)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81f98cd9)
Location: include/linux/skbuff.h:2933
Inline: True
```
```
In net/ipv6/udp_offload.c (ffffffff81fa69e3)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81fac80d)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/exthdrs_core.c (ffffffff81fc0990)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/ip6_icmp.c (ffffffff81fc12d8)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81fc1858)
Location: include/linux/skbuff.h:2933
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc1e40)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2b99)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc4250)
Location: include/linux/skbuff.h:2933
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc960a)
Location: include/linux/skbuff.h:2933
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In security/selinux/hooks.c (ffffffff816ad828)
Location: include/linux/skbuff.h:2987
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff816d516d)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff816de9f5)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81e1b02a)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff81e27fa6)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81e3609e)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81e46f2d)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81e705a9)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/tso.c (ffffffff81e765db)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81e9562f)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/sched/sch_frag.c (ffffffff81eaf7c5)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_frag_prepare_frag
```
```
In net/ipv4/route.c (ffffffff81eec554)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81ef3fbd)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef5c6b)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81efc038)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81f3a49b)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81f44cf1)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81f476dd)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81f4ce47)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81f58615)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f075)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa2abd)
Location: include/linux/skbuff.h:2987
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81fb9fcd)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb2df)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81fe7521)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81feb866)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81ff1a36)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81ff96b3)
Location: include/linux/skbuff.h:2987
Inline: True
```
```
In net/ipv6/udp_offload.c (ffffffff820071bc)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff8200cfa7)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/exthdrs_core.c (ffffffff82021910)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/ip6_icmp.c (ffffffff82022258)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff820227d8)
Location: include/linux/skbuff.h:2987
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff82022dc0)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/ipv6/tcpv6_offload.c (ffffffff82023b28)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff82025270)
Location: include/linux/skbuff.h:2987
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202bc01)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In security/selinux/hooks.c (ffffffff816ea8b8)
Location: include/linux/skbuff.h:2994
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8171151d)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff8171b5c5)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81ed85ea)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff81ee6029)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81ef435e)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81f05bed)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81f2fc39)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/tso.c (ffffffff81f3659b)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81f57ba6)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/sched/sch_frag.c (ffffffff81f72245)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_frag_prepare_frag
```
```
In net/ipv4/route.c (ffffffff81fb05a4)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81fb7f50)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9c1b)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81fbff78)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff8200058b)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff8200ad43)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff8200d81d)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff82012f57)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff8201ead5)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff820357a5)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/xfrm/xfrm_output.c (ffffffff8206fdbd)
Location: include/linux/skbuff.h:2994
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff820873d3)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff820886ef)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff820b5380)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff820b9531)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff820bf635)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff820c7323)
Location: include/linux/skbuff.h:2994
Inline: True
```
```
In net/ipv6/udp_offload.c (ffffffff820d601c)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff820dbf77)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/exthdrs_core.c (ffffffff820f0a30)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/ip6_icmp.c (ffffffff820f1378)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff820f18f8)
Location: include/linux/skbuff.h:2994
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff820f2882)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/ipv6/tcpv6_offload.c (ffffffff820f2c88)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f4550)
Location: include/linux/skbuff.h:2994
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fb6b2)
Location: include/linux/skbuff.h:2994
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In security/selinux/hooks.c (ffff80001054e9c4)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In security/smack/smack_lsm.c (ffff80001056f7d4)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In security/lsm_audit.c (ffff8000105778a0)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffff800010bb907c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/flow_dissector.c (ffff800010bc3d84)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffff800010bcff9c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffff800010be1b44)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffff800010bfcf50)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/tso.c (ffff800010c04890)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffff800010c19d84)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffff800010c57ffc)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_fragment.c (ffff800010c5f7a4)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffff800010c65378)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffff800010c95ae4)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffff800010c9e9a4)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffff800010ca104c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffff800010ca50a0)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffff800010cae5ec)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffff800010cebb20)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffff800010cfc368)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffff800010cfdf98)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffff800010d232ec)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffff800010d26b7c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffff800010d2cd0c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffff800010d355d0)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/udp_offload.c (ffff800010d41090)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffff800010d43fb8)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/exthdrs_core.c (ffff800010d53298)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/output_core.c (ffff800010d54070)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (ffff800010d550ac)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffff800010d563a4)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d57cfc)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In security/selinux/hooks.c (c070836c)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In security/smack/smack_lsm.c (c0722e34)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (c072a6c4)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (c0cd5b40)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/flow_dissector.c (c0cdf220)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (c0ce8e64)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (c0cfcb40)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (c0d175b8)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/tso.c (c0d1dd34)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (c0d2f5d0)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (c0d67c00)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_fragment.c (c0d6e7f8)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (c0d7524c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (c0da4250)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (c0dabc60)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (c0dad57c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (c0db19ac)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (c0dbc8e8)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (c0df3878)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (c0e03b44)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (c0e0551c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (c0e2795c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (c0e2bd18)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (c0e30d6c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (c0e376a0)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/udp_offload.c (c0e43ad4)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (c0e45d80)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/exthdrs_core.c (c0e53c14)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/output_core.c (c0e54834)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (c0e5565c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (c0e56990)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In net/packet/af_packet.c (c0e59c8c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In security/selinux/hooks.c (c0000000006afa78)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In security/smack/smack_lsm.c (c0000000006d4d30)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In security/lsm_audit.c (c0000000006e0f20)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (c000000000c91550)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/flow_dissector.c (c000000000c9e090)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (c000000000caccc4)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (c000000000cc2eac)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (c000000000ce53a0)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/tso.c (c000000000cee7f8)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (c000000000d06838)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (c000000000d59918)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_fragment.c (c000000000d61cc8)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (c000000000d69c40)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (c000000000da6de8)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (c000000000db1140)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (c000000000db3fbc)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (c000000000db8df4)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (c000000000dc69bc)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (c000000000e0fa48)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (c000000000e24250)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (c000000000e25d68)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (c000000000e53278)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (c000000000e578b0)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (c000000000e5e7f8)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (c000000000e6763c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/udp_offload.c (c000000000e7596c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (c000000000e78b80)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/exthdrs_core.c (c000000000e8b9a8)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/output_core.c (c000000000e8cae8)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (c000000000e8ddb8)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f5c8)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In net/packet/af_packet.c (c000000000e92db4)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In security/selinux/hooks.c (ffffffe0003a8abe)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffe0003c57d4)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffe0003c9dac)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffe00074866a)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/flow_dissector.c (ffffffe0007507e0)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffe00075a0b8)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffe00076890e)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffe00077fa22)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/tso.c (ffffffe00078346e)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffe0007910ec)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffe0007c227e)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c75ae)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffe0007ccbb0)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f4cba)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffe0007fb5be)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd656)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffe0008009d6)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffe0008099b8)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffe0008393f2)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffe000846c42)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffe00084802c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffe000864cf8)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffe000868c5e)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffe00086cf64)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffe00087296e)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/udp_offload.c (ffffffe00087c7ec)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffe00087eafc)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/exthdrs_core.c (ffffffe00088aff2)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/output_core.c (ffffffe00088bb8c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (ffffffe00088c8e2)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088dc20)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In net/packet/af_packet.c (ffffffe00088f9ce)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In security/selinux/hooks.c (ffffffff81459891)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81476ba2)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In security/lsm_audit.c (ffffffff8147d983)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff818be8af)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/flow_dissector.c (ffffffff818c792b)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818d16f3)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff818e20ed)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff818fbb6c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/tso.c (ffffffff81900fdc)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81911325)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff81948558)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_fragment.c (ffffffff8194e9f6)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81954cf0)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff8198192b)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81988ec9)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff8198b370)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff8198effc)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81998ba5)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc555)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff819dabf8)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff819dbeec)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff819fd935)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81a0117a)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a0642c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81a0c510)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a170dc)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a19373)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a2629e)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/output_core.c (ffffffff81a26e1f)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a27b82)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28c00)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2bbc3)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In security/selinux/hooks.c (ffffffff8144a2c1)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814675c2)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In security/lsm_audit.c (ffffffff8146e3a3)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/vxlan.c (ffffffff817740c0)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:neigh_reduce
```
```
In net/core/skbuff.c (ffffffff818787ef)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/flow_dissector.c (ffffffff8188186b)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff8188b583)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff8189bf2d)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff818b599c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/tso.c (ffffffff818bae0c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff818cb0e5)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff81902048)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_fragment.c (ffffffff819084e6)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff8190e7e0)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff8193b3eb)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81942989)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81944e30)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81948abc)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81952665)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff81989345)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff819979b8)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81998cac)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff819ba6f5)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff819bdf3a)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff819c31ec)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff819c92d0)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff819d3e9c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff819d6133)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/exthdrs_core.c (ffffffff819e305e)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/output_core.c (ffffffff819e3bdf)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e4942)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5df0)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e8db3)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In security/selinux/hooks.c (ffffffff81455931)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81472c42)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In security/lsm_audit.c (ffffffff81479a23)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff8190f8af)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/flow_dissector.c (ffffffff8191892b)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff819226f3)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff8193311d)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff8194cb9c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/tso.c (ffffffff8195200c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81962355)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199f5ee)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_update
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_update
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_in
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_in
```
```
In net/netfilter/nf_conntrack_proto.c (ffffffff819a49b4)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto.c:ipv4_confirm
```
```
In net/ipv4/route.c (ffffffff819b2d28)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_fragment.c (ffffffff819b91c6)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff819bf4c0)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff819ec0fb)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff819f3699)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819f5b40)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff819f989c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81a03445)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff81a36fd5)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a45678)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81a4696c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81a683b5)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81a6bbfa)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a70eac)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81a76f90)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a81b5c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a83df3)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a9115e)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a91e4e)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/output_core.c (ffffffff81a929cf)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a93732)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a947b0)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a97773)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In security/selinux/hooks.c (ffffffff81470c21)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8148a532)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In security/lsm_audit.c (ffffffff814914d3)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff819309df)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/flow_dissector.c (ffffffff81939570)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff819438c3)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81954a4d)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff8196e55c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/tso.c (ffffffff81973a4c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff819845c5)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff819bc3ea)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_fragment.c (ffffffff819c2ab6)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff819c8e40)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5fab)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff819fd859)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819ffd40)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81a03b8c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81a0d995)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42965)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a51348)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81a5269c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81a749a5)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81a7820a)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a7d4bc)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81a835b0)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a8e45c)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a9071e)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a9defe)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/output_core.c (ffffffff81a9eacf)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9f882)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa0910)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa4093)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
</details>
</li>
</ul>

## Differences

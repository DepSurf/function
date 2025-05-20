# Function: <code>skb_mac_header</code>

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
In kernel/bpf/core.c (0)
Location: include/linux/skbuff.h:2029
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:2029
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/skbuff.h:2029
Inline: True
```
```
In net/core/dev.c (ffffffff8171b47d)
Location: include/linux/skbuff.h:2029
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/net-traces.c (0)
Location: include/linux/skbuff.h:2029
Inline: True
```
```
In net/ethernet/eth.c (0)
Location: include/linux/skbuff.h:2029
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:2029
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2029
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/skbuff.h:2029
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2029
Inline: True
```
```
In net/ipv6/ip6_offload.c (0)
Location: include/linux/skbuff.h:2029
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2029
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/skbuff.h:2029
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/skbuff.h:2029
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
In kernel/bpf/core.c (ffffffff811806b5)
Location: include/linux/skbuff.h:2159
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In net/core/skbuff.c (ffffffff817709d6)
Location: include/linux/skbuff.h:2159
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_segment
```
```
In net/core/flow_dissector.c (ffffffff81779832)
Location: include/linux/skbuff.h:2159
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81783b67)
Location: include/linux/skbuff.h:2159
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8179dbd5)
Location: include/linux/skbuff.h:2159
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/core/net-traces.c (ffffffff817a89e7)
Location: include/linux/skbuff.h:2159
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/ethernet/eth.c (ffffffff817aca85)
Location: include/linux/skbuff.h:2159
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffffffff817bfaa7)
Location: include/linux/skbuff.h:2159
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2159
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8180253f)
Location: include/linux/skbuff.h:2159
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2159
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2159
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81872987)
Location: include/linux/skbuff.h:2159
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81879c87)
Location: include/linux/skbuff.h:2159
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff8187b1fb)
Location: include/linux/skbuff.h:2159
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff8118c525)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In net/core/skbuff.c (ffffffff8179da9f)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_segment
```
```
In net/core/flow_dissector.c (ffffffff817a694a)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff817b10c9)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff817cc635)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/net-traces.c (ffffffff817d7525)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/ethernet/eth.c (ffffffff817dc075)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffffffff817ef3f7)
Location: include/linux/skbuff.h:2176
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2176
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff818334ee)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2176
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2176
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a41d6)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6fa5)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff818ae384)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff818afabb)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff8118fdf3)
Location: include/linux/skbuff.h:2215
Inline: True
Inline callers:
  - kernel/bpf/core.c:___bpf_prog_run
  - kernel/bpf/core.c:___bpf_prog_run
  - kernel/bpf/core.c:___bpf_prog_run
```
```
In net/socket.c (ffffffff817ae290)
Location: include/linux/skbuff.h:2215
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff817bb95f)
Location: include/linux/skbuff.h:2215
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_segment
```
```
In net/core/flow_dissector.c (ffffffff817c4afe)
Location: include/linux/skbuff.h:2215
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff817d14c8)
Location: include/linux/skbuff.h:2215
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff817eb955)
Location: include/linux/skbuff.h:2215
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/net-traces.c (ffffffff817f6b84)
Location: include/linux/skbuff.h:2215
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/ethernet/eth.c (ffffffff817fb675)
Location: include/linux/skbuff.h:2215
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:2215
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2215
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81854863)
Location: include/linux/skbuff.h:2215
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2215
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81872201)
Location: include/linux/skbuff.h:2215
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_device.c (ffffffff81880103)
Location: include/linux/skbuff.h:2215
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2215
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff818c5b9a)
Location: include/linux/skbuff.h:2215
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca821)
Location: include/linux/skbuff.h:2215
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff818cda00)
Location: include/linux/skbuff.h:2215
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff818d4d8b)
Location: include/linux/skbuff.h:2215
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff818d6283)
Location: include/linux/skbuff.h:2215
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff8119d0a8)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (ffffffff81826360)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff81834a0f)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_segment
```
```
In net/core/flow_dissector.c (ffffffff8183e451)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff8184b863)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:do_xdp_generic
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818667a5)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/net-traces.c (ffffffff81873167)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/ethernet/eth.c (ffffffff81879025)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:2302
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2302
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff818d4707)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2302
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2c25)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_device.c (ffffffff8190121f)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffffffff81915f78)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81929196)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2302
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81948ece)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e4ca)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff81952802)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff8195980d)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff8195be1d)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff811b17d8)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (ffffffff8186fc43)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff8187f85d)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/flow_dissector.c (ffffffff81888c8b)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81895c5b)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818b546a)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/net-traces.c (ffffffff818c48ed)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/ethernet/eth.c (ffffffff818caa15)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffffffff818e7676)
Location: include/linux/skbuff.h:2313
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2313
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8192adda)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2313
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81949540)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_device.c (ffffffff81957de6)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffffffff8196f442)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff8198295f)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2313
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff819a1fa9)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a782a)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff819abdc6)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff819b04b4)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff819b564e)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff811bfe68)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (ffffffff81890820)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff8189faba)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/flow_dissector.c (ffffffff818aa0a7)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818b7868)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818d5aa9)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/net-traces.c (ffffffff818ed96d)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/ethernet/eth.c (ffffffff818f5ae5)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffffffff81914526)
Location: include/linux/skbuff.h:2391
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194d12c)
Location: include/linux/skbuff.h:2391
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2391
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8195a555)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2391
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b217)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_device.c (ffffffff8198cefc)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffffffff819a4ff2)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff819b8fff)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp.c (ffffffff819bb41c)
Location: include/linux/skbuff.h:2391
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2391
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff819d8c14)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de391)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff819e297a)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff819e7cbb)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff819ec919)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff811d0698)
Location: include/linux/skbuff.h:2479
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (ffffffff818da722)
Location: include/linux/skbuff.h:2479
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff818ec983)
Location: include/linux/skbuff.h:2479
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/flow_dissector.c (ffffffff818f5389)
Location: include/linux/skbuff.h:2479
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff819036de)
Location: include/linux/skbuff.h:2479
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8192324c)
Location: include/linux/skbuff.h:2479
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/net-traces.c (ffffffff8193e2b3)
Location: include/linux/skbuff.h:2479
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/ethernet/eth.c (ffffffff81955115)
Location: include/linux/skbuff.h:2479
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffffffff819769e0)
Location: include/linux/skbuff.h:2479
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b18fc)
Location: include/linux/skbuff.h:2479
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2479
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff819bf0d9)
Location: include/linux/skbuff.h:2479
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2479
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e473c)
Location: include/linux/skbuff.h:2479
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4b7e)
Location: include/linux/skbuff.h:2479
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff819f8755)
Location: include/linux/skbuff.h:2479
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffffffff81a11432)
Location: include/linux/skbuff.h:2479
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81a27b09)
Location: include/linux/skbuff.h:2479
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp.c (ffffffff81a2a02c)
Location: include/linux/skbuff.h:2479
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2479
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a47481)
Location: include/linux/skbuff.h:2479
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4cef1)
Location: include/linux/skbuff.h:2479
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff81a51618)
Location: include/linux/skbuff.h:2479
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81a54852)
Location: include/linux/skbuff.h:2479
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81a5bac8)
Location: include/linux/skbuff.h:2479
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff811dcc28)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (ffffffff8190c872)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff8191eab9)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/flow_dissector.c (ffffffff81927267)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81936491)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8195547c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/net-traces.c (ffffffff81971143)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/core/drop_monitor.c (ffffffff81975f1e)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ethernet/eth.c (ffffffff8198b5b5)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffffffff819ad3b7)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e865c)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff819f5d19)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b74c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b82e)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f3b5)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffffffff81a480a1)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81a5e569)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp.c (ffffffff81a60b4c)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a7e031)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83ac1)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff81a88238)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81a8b442)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81a926bf)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff811f9648)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (ffffffff819df379)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff819f134c)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff819fb6c4)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a00a8f)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a2ea14)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/net-traces.c (ffffffff81a4554b)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/core/drop_monitor.c (ffffffff81a4aad6)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
```
```
In net/ethernet/eth.c (ffffffff81a632b5)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffffffff81a9715a)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_handle_martian_source
```
```
In net/ipv4/udp.c (ffffffff81ad65d5)
Location: include/linux/skbuff.h:2516
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81ad86b9)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ae400b)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81afa03f)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c7e9)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d6c1)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_device.c (ffffffff81b22089)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffffffff81b3eb6b)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81b5733f)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp.c (ffffffff81b59a15)
Location: include/linux/skbuff.h:2516
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b6cd8d)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b71a03)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78b8b)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e89a)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff81b83586)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81b87260)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81b8db6f)
Location: include/linux/skbuff.h:2516
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff811f8688)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (ffffffff819ded1e)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff819f12dc)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff819fb39d)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a00e9f)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a30684)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/net-traces.c (ffffffff81a4981f)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/core/drop_monitor.c (ffffffff81a50716)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
```
```
In net/core/ptp_classifier.c (ffffffff81a51115)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_parse_header
```
```
In net/ethernet/eth.c (ffffffff81a6b405)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffffffff81c32432)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_handle_martian_source
```
```
In net/ipv4/tcp_input.c (ffffffff81abb058)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff81ae2bb5)
Location: include/linux/skbuff.h:2537
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81ae4bec)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81af0f3b)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06851)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81b077b7)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1ab02)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2bee3)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_device.c (ffffffff81b309cb)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffffffff81c32c15)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81c32e3c)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp.c (ffffffff81b68075)
Location: include/linux/skbuff.h:2537
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b7b819)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b806a7)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87af4)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d8aa)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92c46)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81b96db9)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81b9d83e)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff811f947b)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (ffffffff819c4cde)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff819d6585)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff819e161b)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff819e7621)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81a17724)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/net-traces.c (ffffffff81a2e76f)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/core/drop_monitor.c (ffffffff81a357e9)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/selftests.c (ffffffff81a364fb)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/ptp_classifier.c (ffffffff81a36995)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_parse_header
```
```
In net/ethernet/eth.c (ffffffff81a53b25)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffffffff81c2471b)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_handle_martian_source
```
```
In net/ipv4/tcp_input.c (ffffffff81aa6018)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff81acdad5)
Location: include/linux/skbuff.h:2553
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81acfe09)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81adc6fb)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af1f65)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81af2f7b)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b087b2)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19b51)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e704)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffffffff81c24f3b)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81c2513d)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp.c (ffffffff81b56385)
Location: include/linux/skbuff.h:2553
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a2e1)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f2ca)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b767a4)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c75a)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81d96)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81b85dbe)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81b8c967)
Location: include/linux/skbuff.h:2553
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff8122ab0b)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (ffffffff81a7416a)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff81a86bd5)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff81a91a5c)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a9838d)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81ac8cb4)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/net-traces.c (ffffffff81ae3d4f)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/core/drop_monitor.c (ffffffff81aeb3b9)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/selftests.c (ffffffff81aec1cb)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/ptp_classifier.c (ffffffff81aec6e5)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_parse_header
```
```
In net/ethernet/eth.c (ffffffff81b0c835)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffffffff81d39c6c)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_handle_martian_source
```
```
In net/ipv4/tcp_input.c (ffffffff81b623f8)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff81b8c4a5)
Location: include/linux/skbuff.h:2582
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e829)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81b9badb)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2475)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81bb348b)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb6bd)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdde21)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_device.c (ffffffff81be320b)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffffffff81d3fa4c)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81d4052a)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp.c (ffffffff81c1c9f5)
Location: include/linux/skbuff.h:2582
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81c32141)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81c3738a)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c4122f)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c475f0)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4bea4)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4de0f)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81c52164)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81c58d27)
Location: include/linux/skbuff.h:2582
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff8126c427)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (ffffffff81be6d75)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff81bfc320)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff81c07caa)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81c19d76)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81c45b07)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro.c (ffffffff81c53b6e)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:skb_mac_gso_segment
```
```
In net/core/net-traces.c (ffffffff81c68a55)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/core/drop_monitor.c (ffffffff81c6dc17)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/selftests.c (ffffffff81c6eb62)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/ptp_classifier.c (ffffffff81c6f215)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_msg_is_sync
```
```
In net/ethernet/eth.c (ffffffff81c93165)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffffffff81f063af)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_handle_martian_source
```
```
In net/ipv4/tcp_input.c (ffffffff81cf16a8)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff81d1cb15)
Location: include/linux/skbuff.h:2951
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81d1ff87)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81d2d89b)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45c37)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81d46cba)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d61183)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81d74f85)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a414)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffffffff81f0c3c0)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81f0cef5)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp.c (ffffffff81db92c5)
Location: include/linux/skbuff.h:2951
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81dcf93f)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81dd4f2d)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddf9cc)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de69d1)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81debe79)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff81dedc88)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81df44c9)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81dfa3da)
Location: include/linux/skbuff.h:2951
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff812c1447)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (ffffffff81d93ce0)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff81dab1f0)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff81db7766)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81dcadf6)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81df9d67)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro.c (ffffffff81e092d3)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:skb_mac_gso_segment
```
```
In net/core/net-traces.c (ffffffff81e20101)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/core/drop_monitor.c (ffffffff81e25887)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/selftests.c (ffffffff81e268a2)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/ptp_classifier.c (ffffffff81e26fe5)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_msg_is_sync
```
```
In net/ethernet/eth.c (ffffffff81e4e7a5)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffffffff81e8ceaf)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_handle_martian_source
```
```
In net/ipv4/tcp_input.c (ffffffff81eb5ea8)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff81ee3bf5)
Location: include/linux/skbuff.h:2848
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7184)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ef579b)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f007)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81f1050a)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2ba75)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81f421bf)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_device.c (ffffffff81f4736a)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffffffff81f68a5f)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81f8470a)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp.c (ffffffff81f89315)
Location: include/linux/skbuff.h:2848
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81fa0cc3)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81fa6633)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1c96)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb97d5)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfad9)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc1ba8)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/packet/af_packet.c (ffffffff81fc923c)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81fceafb)
Location: include/linux/skbuff.h:2848
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff812e8212)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (ffffffff81e01880)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff81e1acf0)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff81e27d12)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81e3b97d)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81e6bb57)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro.c (ffffffff81e7bb19)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/core/gso.c (ffffffff81e7d602)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_validate_mac_len
  - net/core/gso.c:skb_mac_gso_segment
```
```
In net/core/net-traces.c (ffffffff81e948c1)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/core/drop_monitor.c (ffffffff81e9adc7)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/selftests.c (ffffffff81e9be42)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/ptp_classifier.c (ffffffff81e9c565)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_msg_is_sync
```
```
In net/ethernet/eth.c (ffffffff81ea9e45)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffffffff81eeb5df)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_handle_martian_source
```
```
In net/ipv4/tcp_input.c (ffffffff81f142c8)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff81f43465)
Location: include/linux/skbuff.h:2902
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81f46a27)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81f5514b)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6ed07)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81f701f4)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b8cd)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa19a7)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6db6)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffffffff81fc8b3c)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81fe4a57)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp.c (ffffffff81fe8745)
Location: include/linux/skbuff.h:2902
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff8200166a)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff82006e7d)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/xfrm6_input.c (ffffffff8201237e)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019fca)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8201d17e)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020a69)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff82022b28)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/packet/af_packet.c (ffffffff8202995e)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff8204a4b0)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff81306562)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In drivers/net/netkit.c (ffffffff81ce53bc)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_xmit
```
```
In net/socket.c (ffffffff81ebe23c)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff81ed8390)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff81ee5cc2)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81ef9ebd)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81f2ac37)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro.c (ffffffff81f3be4b)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/core/gso.c (ffffffff81f3e582)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_validate_mac_len
  - net/core/gso.c:skb_mac_gso_segment
```
```
In net/core/net-traces.c (ffffffff81f56dd9)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/core/drop_monitor.c (ffffffff81f5d521)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/selftests.c (ffffffff81f5e5a2)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/ptp_classifier.c (ffffffff81f5ecf5)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_msg_is_sync
```
```
In net/ethernet/eth.c (ffffffff81f6c905)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffffffff81faf5e3)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_handle_martian_source
```
```
In net/ipv4/tcp_input.c (ffffffff81fd87a8)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff820093c5)
Location: include/linux/skbuff.h:2909
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff8200cb67)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8201b3bb)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035427)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff82036924)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff820531cd)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff8206ecc7)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_device.c (ffffffff82074098)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffffffff8209629c)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff820b295b)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp.c (ffffffff820b7295)
Location: include/linux/skbuff.h:2909
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff820d04aa)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff820d5cdd)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e14ee)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8f9a)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff820ec15e)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820efb99)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff820f1c4f)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/packet/af_packet.c (ffffffff820f9425)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff8211c91c)
Location: include/linux/skbuff.h:2909
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffff80001025d5d8)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (ffff800010ba170c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffff800010bb928c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/flow_dissector.c (ffff800010bc37e0)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffff800010bd4adc)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffff800010bf726c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/net-traces.c (ffff800010c19bb4)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/core/drop_monitor.c (ffff800010c1c104)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ethernet/eth.c (ffff800010c36410)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffff800010c5923c)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9daf8)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/af_inet.c (ffff800010cab94c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd79b0)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffff800010cea2b8)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffff800010cee518)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffff800010d08e2c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffff800010d222e0)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp.c (ffff800010d26798)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffff800010d493d8)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f7ec)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ip6_offload.c (ffff800010d54d20)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffff800010d59f48)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffff800010d60480)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (c0490e64)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (c0cc47bc)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (c0cd5d48)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_segment
```
```
In net/core/flow_dissector.c (c0cdeadc)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (c0cef074)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (c0d10360)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/net-traces.c (c0d2f80c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/core/drop_monitor.c (c0d341f8)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ethernet/eth.c (c0d48ea0)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (c0d66e98)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_handle_martian_source
```
```
In net/ipv4/udp.c (c0dab5a8)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/udp_offload.c (c0dad8bc)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (c0db8690)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (c0dce484)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (c0de14c8)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (c0df249c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/xfrm/xfrm_device.c (c0df6390)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (c0e0f3e4)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (c0e27fcc)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (c0e29de8)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv6/udp_offload.c (c0e43734)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv6/xfrm6_input.c (c0e4a7b0)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (c0e50590)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ip6_offload.c (c0e55258)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (c0e589d8)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (c0e5ff3c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (c000000000302010)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (c000000000c75cf8)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (c000000000c91828)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/flow_dissector.c (c000000000c9d984)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (c000000000cb3e40)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (c000000000cdccd4)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/net-traces.c (c000000000d065e8)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/core/drop_monitor.c (c000000000d0d164)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ethernet/eth.c (c000000000d2e4f8)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (c000000000d58764)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_handle_martian_source
```
```
In net/ipv4/udp.c (c000000000daf44c)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/af_inet.c (c000000000dc2330)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/xfrm4_input.c (c000000000df78e0)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (c000000000e0ddb4)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/xfrm/xfrm_device.c (c000000000e1315c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (c000000000e33404)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (c000000000e51d64)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp.c (c000000000e5647c)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e990)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86eb0)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ip6_offload.c (c000000000e8d944)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (c000000000e941cc)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (c000000000e9b41c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffe00019bc6e)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (ffffffe00073985e)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffe00074885a)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/flow_dissector.c (ffffffe000750480)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffe00075e896)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffe0007790b6)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/net-traces.c (ffffffe00079149c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/core/drop_monitor.c (ffffffe0007961b8)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ethernet/eth.c (ffffffe0007a7d80)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffffffe0007c15b0)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_handle_martian_source
```
```
In net/ipv4/udp.c (ffffffe0007fac20)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffe0008065be)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffe000828060)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffe000837ef0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b7a2)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffffffe000850bb2)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffe000863ef8)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp.c (ffffffe000866f7c)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffe0008828c2)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000888036)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c608)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffe00088fe46)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffe000895890)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff811d5248)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (ffffffff818ac872)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff818beab9)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/flow_dissector.c (ffffffff818c7267)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818d6461)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818f544c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/net-traces.c (ffffffff81911113)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/core/drop_monitor.c (ffffffff81915eee)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ethernet/eth.c (ffffffff8192b425)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffffffff8194d227)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819884cc)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81995ab9)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff819baddc)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff819caebe)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff819cea45)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffffffff819e7731)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff819fdbf9)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp.c (ffffffff81a001dc)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a1d6c1)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a23151)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff81a278c8)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81a2aad2)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81a31d4f)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff811c8008)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In drivers/net/vxlan.c (ffffffff81773b34)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:route_shortcircuit
  - drivers/net/vxlan.c:route_shortcircuit
  - drivers/net/vxlan.c:route_shortcircuit
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/socket.c (ffffffff818667c2)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff818789f9)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/flow_dissector.c (ffffffff818811a7)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818902a1)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818af27c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/net-traces.c (ffffffff818caed3)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/core/drop_monitor.c (ffffffff818cfc9e)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ethernet/eth.c (ffffffff818e51d5)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffffffff81906d17)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81941f8c)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8194f579)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967ec3)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977bcc)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81987cae)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b80a)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffffffff819a44f1)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff819ba9b9)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp.c (ffffffff819bcf9c)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff819da481)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dff11)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff819e4688)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff819e7cc2)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff819eef3f)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff811d3018)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (ffffffff818fd872)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff8190fab9)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/flow_dissector.c (ffffffff81918267)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81927491)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8194647c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/net-traces.c (ffffffff81962143)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/core/drop_monitor.c (ffffffff81966f1e)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ethernet/eth.c (ffffffff8197c5b5)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff81999aae)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199c078)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:__build_packet_message
  - net/netfilter/nfnetlink_log.c:__build_packet_message
```
```
In net/ipv4/route.c (ffffffff819b79f7)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f2c9c)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81a00359)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a2585c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81a3593e)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81a394c5)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffffffff81a521b1)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81a68679)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp.c (ffffffff81a6ac5c)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a88141)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8dbd1)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff81a93478)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81a96682)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81a9d8ff)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/bpf/core.c (ffffffff811e1308)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In net/socket.c (ffffffff8191e8ec)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff81930be9)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/flow_dissector.c (ffffffff81939611)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81948af9)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81967d6c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/net-traces.c (ffffffff819843b3)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/core/drop_monitor.c (ffffffff819891ae)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ethernet/eth.c (ffffffff8199eb05)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/route.c (ffffffff819c1267)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fd1ac)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81a0a3a9)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30cee)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81a412a9)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44ef5)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/addrconf.c (ffffffff81a5e101)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81a74c74)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/ipv6/udp.c (ffffffff81a7726c)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2493
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a94d72)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a8d1)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f5c8)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/packet/af_packet.c (ffffffff81aa32fc)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81aa9aff)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
</ul>

## Differences

# Function: <code>skb_push</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned char *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81705eb0)
Location: net/core/skbuff.c:1446
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81705eb0-ffffffff81705eef: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned char *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81770a7f)
Location: net/core/skbuff.c:1451
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff8176cb30-ffffffff8176cb6f: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned char *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179db29)
Location: net/core/skbuff.c:1451
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81799d00-ffffffff81799d3f: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817bb9e4)
Location: net/core/skbuff.c:1464
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_skb_generic_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff817b9260-ffffffff817b929f: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81834a94)
Location: net/core/skbuff.c:1709
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_skb_generic_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81831b70-ffffffff81831baf: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1711
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff8188341a-ffffffff8188342a: skb_push.cold.81 (STB_LOCAL)
ffffffff8187a6c0-ffffffff8187a6f4: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1721
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff818a3e61-ffffffff818a3e71: skb_push.cold.82 (STB_LOCAL)
ffffffff8189b2d0-ffffffff8189b301: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1880
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff818eeb61-ffffffff818eeb85: skb_push.cold (STB_LOCAL)
ffffffff818e5b50-ffffffff818e5b85: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1880
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81920c4e-ffffffff81920c72: skb_push.cold (STB_LOCAL)
ffffffff81917ca0-ffffffff81917cd5: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff819f0603)
Location: net/core/skbuff.c:1879
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:validate_xmit_vlan
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff819f49df-ffffffff819f49ef: skb_push.cold (STB_LOCAL)
ffffffff819ea0e0-ffffffff819ea10e: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff819f0351)
Location: net/core/skbuff.c:1890
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:validate_xmit_vlan
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81c30958-ffffffff81c30968: skb_push.cold (STB_LOCAL)
ffffffff819e9e10-ffffffff819e9e3e: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff819d4c93)
Location: net/core/skbuff.c:1932
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:validate_xmit_vlan
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/selftests.c:net_test_get_skb
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81c22c37-ffffffff81c22c4b: skb_push.cold (STB_LOCAL)
ffffffff819d0350-ffffffff819d0379: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81a84a23)
Location: net/core/skbuff.c:2004
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/dev.c:validate_xmit_vlan
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/selftests.c:net_test_get_skb
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81d350bf-ffffffff81d350d3: skb_push.cold (STB_LOCAL)
ffffffff81a7fad0-ffffffff81a7faf9: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfaa32)
Location: net/core/skbuff.c:2029
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/selftests.c:net_test_get_skb
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff81f01188-ffffffff81f0119c: skb_push.cold (STB_LOCAL)
ffffffff81bf3fa0-ffffffff81bf3fd5: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da98c2)
Location: net/core/skbuff.c:2232
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/filter.c:bpf_skb_generic_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/selftests.c:net_test_get_skb
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff81da1d60-ffffffff81da1da5: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e183c2)
Location: net/core/skbuff.c:2396
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/filter.c:bpf_skb_generic_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/selftests.c:net_test_get_skb
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff81e105b0-ffffffff81e105f5: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed5862)
Location: net/core/skbuff.c:2484
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/filter.c:bpf_skb_generic_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/selftests.c:net_test_get_skb
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_gro_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_gro_udp_encap_rcv
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/xfrm6_input.c:xfrm6_gro_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_gro_udp_encap_rcv
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff81ecd0d0-ffffffff81ecd115: skb_push (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb0f78)
Location: net/core/skbuff.c:1880
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffff800010bb0f78-ffff800010bb0fe4: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cce9e4)
Location: net/core/skbuff.c:1880
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
c0cce9e4-c0ccea34: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c87ed0)
Location: net/core/skbuff.c:1880
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
c000000000c87ed0-c000000000c87f4c: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000742a60)
Location: net/core/skbuff.c:1880
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_rcv
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffe000742a60-ffffffe000742abc: skb_push (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1880
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff818c0c4e-ffffffff818c0c72: skb_push.cold (STB_LOCAL)
ffffffff818b7ca0-ffffffff818b7cd5: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1880
Inline: False
Direct callers:
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff8187ab8e-ffffffff8187abb2: skb_push.cold (STB_LOCAL)
ffffffff81871bf0-ffffffff81871c25: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1880
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81911c4e-ffffffff81911c72: skb_push.cold (STB_LOCAL)
ffffffff81908ca0-ffffffff81908cd5: skb_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *skb_push(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1880
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_header
  - net/802/fc.c:fc_header
  - net/802/fc.c:fc_header
  - net/802/fddi.c:fddi_header
  - net/802/fddi.c:fddi_header
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_exthdr
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81932dae-ffffffff81932dd2: skb_push.cold (STB_LOCAL)
ffffffff81929d50-ffffffff81929d85: skb_push (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned char *</code> ➡️ <code>void *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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

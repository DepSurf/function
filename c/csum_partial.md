# Function: <code>csum_partial</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff813f6399)
Location: arch/x86/lib/csum-partial_64.c:133
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
Direct callers:
  - net/core/skbuff.c:csum_partial_ext
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff813f63c0-ffffffff813f63d9: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff8143cf69)
Location: arch/x86/lib/csum-partial_64.c:133
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
Direct callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:csum_partial_ext
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff8143cf90-ffffffff8143cfa9: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff81459f09)
Location: arch/x86/lib/csum-partial_64.c:133
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
Direct callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:csum_partial_ext
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81459ee0-ffffffff81459ef9: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff818fba59)
Location: arch/x86/lib/csum-partial_64.c:133
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
Direct callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:csum_partial_ext
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff818fba30-ffffffff818fba49: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff819828a9)
Location: arch/x86/lib/csum-partial_64.c:134
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
Direct callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:csum_partial_ext
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81982880-ffffffff81982899: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff819dedd5)
Location: arch/x86/lib/csum-partial_64.c:134
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
Direct callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:csum_partial_ext
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff819dedb0-ffffffff819dedc9: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff81a19d05)
Location: arch/x86/lib/csum-partial_64.c:134
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
Direct callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:csum_partial_ext
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81a19ce0-ffffffff81a19cf9: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff81a89a25)
Location: arch/x86/lib/csum-partial_64.c:134
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mod_eth_type
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81a89a00-ffffffff81a89a19: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff81ac0cc5)
Location: arch/x86/lib/csum-partial_64.c:134
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mod_eth_type
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81ac0ca0-ffffffff81ac0cb9: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff815fd115)
Location: arch/x86/lib/csum-partial_64.c:134
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_mkname
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:seg6_update_csum
  - net/ipv6/exthdrs.c:seg6_update_csum
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff815fd0f0-ffffffff815fd10c: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff81621f15)
Location: arch/x86/lib/csum-partial_64.c:134
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_gro_receive
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_mkname
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:seg6_update_csum
  - net/ipv6/exthdrs.c:seg6_update_csum
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81621ef0-ffffffff81621f0c: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff81605825)
Location: arch/x86/lib/csum-partial_64.c:134
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb2
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_gro_receive
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_mkname
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81605800-ffffffff8160581c: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff81674115)
Location: arch/x86/lib/csum-partial_64.c:134
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb2
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_gro_receive
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/unix/af_unix.c:unix_mkname
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
  - net/mptcp/subflow.c:validate_data_csum
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
```
**Symbols:**

```
ffffffff816740f0-ffffffff8167410c: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff8178e650)
Location: arch/x86/lib/csum-partial_64.c:35
Inline: False
Direct callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb2
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_gro_receive
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_find_other
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
```
**Symbols:**

```
ffffffff8178e650-ffffffff8178e7af: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff8204bf50)
Location: arch/x86/lib/csum-partial_64.c:35
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb2
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_gro_receive
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_find_other
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
**Symbols:**

```
ffffffff8204bf50-ffffffff8204c08c: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff820ca7c0)
Location: arch/x86/lib/csum-partial_64.c:47
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb2
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_gro_receive
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_find_other
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
**Symbols:**

```
ffffffff820ca7c0-ffffffff820ca97a: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff821a50c0)
Location: arch/x86/lib/csum-partial_64.c:44
Inline: False
Direct callers:
  - drivers/net/netkit.c:netkit_xmit
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/dev.c:__dev_forward_skb2
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_gro_receive
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_find_other
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
**Symbols:**

```
ffffffff821a50c0-ffffffff821a51bd: csum_partial (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum wsum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/checksum.c (ffff8000106622f8)
Location: lib/checksum.c:125
Inline: True
Inline callers:
  - lib/checksum.c:csum_partial_copy
  - lib/checksum.c:csum_partial_copy_from_user
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mod_eth_type
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:csum_partial_ext
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffff800010662268-ffff800010662288: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - block/t10-pi.c:t10_pi_ip_fn
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mod_eth_type
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:csum_partial_ext
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:pim_rcv
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_mkname
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
c0e7c950-c0e7c9d4: csum_partial (STB_GLOBAL)
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
In arch/powerpc/lib/checksum_wrappers.c (c0000000000a9ef8)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_to_user
  - arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_from_user
```
```
In block/t10-pi.c (c0000000007be3ac)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_ip_fn
```
```
In net/core/skbuff.c (c000000000c919f0)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mod_eth_type
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:csum_partial_ext
```
```
In net/core/datagram.c (c000000000c955e0)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (c000000000ca74d4)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/utils.c (c000000000cd86c8)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (c000000000ce3af8)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (c000000000cfe250)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (c000000000d115e4)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (c000000000d2f1b4)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_output.c (c000000000d69558)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_offload.c (c000000000da641c)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (c000000000daf1c8)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (c000000000db3c0c)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/igmp.c (c000000000dc5e7c)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ping.c (c000000000ddbb10)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (c000000000dde7d0)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (c000000000de768c)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/unix/af_unix.c (c000000000e17b34)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/ip6_input.c (c000000000e25bac)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (c000000000e4edcc)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c000000000e56268)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (c000000000e5bf28)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c000000000e5d034)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (c000000000e612c0)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/reassembly.c (c000000000e67200)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c08c)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/exthdrs.c (c000000000e6f228)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (c000000000e7b868)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e930)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86c2c)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c000000000e88b40)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (c000000000e8bf4c)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (c000000000e8d690)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
```
```
In net/8021q/vlan_core.c (c000000000e9aa08)
Location: arch/powerpc/include/asm/checksum.h:167
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum wsum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/checksum.c (ffffffe00048ec86)
Location: lib/checksum.c:125
Inline: True
Inline callers:
  - lib/checksum.c:csum_partial_copy
  - lib/checksum.c:csum_partial_copy_from_user
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mod_eth_type
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:csum_partial_ext
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/unix/af_unix.c:unix_autobind
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffe00048eb62-ffffffe00048eb88: csum_partial (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff81a5fb15)
Location: arch/x86/lib/csum-partial_64.c:134
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mod_eth_type
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81a5faf0-ffffffff81a5fb09: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff81a1cbe5)
Location: arch/x86/lib/csum-partial_64.c:134
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
Direct callers:
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mod_eth_type
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81a1cbc0-ffffffff81a1cbd9: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff81acbf05)
Location: arch/x86/lib/csum-partial_64.c:134
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mod_eth_type
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81acbee0-ffffffff81acbef9: csum_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-partial_64.c (ffffffff81ad8455)
Location: arch/x86/lib/csum-partial_64.c:134
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
Direct callers:
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mod_eth_type
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__dev_forward_skb
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81ad8430-ffffffff81ad8449: csum_partial (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>__wsum wsum</code>
</li>
<li>
<b>Param removed. </b>
<code>__wsum sum</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>__wsum wsum</code>
</li>
<li>
<b>Param removed. </b>
<code>__wsum sum</code>
</li>
</ul>
</details>
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

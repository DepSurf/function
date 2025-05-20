# Function: <code>skb_transport_offset</code>

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
In net/core/skbuff.c (ffffffff8170a1f2)
Location: include/linux/skbuff.h:2083
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/tso.c (ffffffff817340b5)
Location: include/linux/skbuff.h:2083
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_start
```
```
In net/core/net-traces.c (0)
Location: include/linux/skbuff.h:2083
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/skbuff.h:2083
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177e22d)
Location: include/linux/skbuff.h:2083
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff817833f0)
Location: include/linux/skbuff.h:2083
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81785ca4)
Location: include/linux/skbuff.h:2083
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81786569)
Location: include/linux/skbuff.h:2083
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/udp_offload.c (ffffffff8178b1af)
Location: include/linux/skbuff.h:2083
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:2083
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff817a5292)
Location: include/linux/skbuff.h:2083
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/ip6_input.c (ffffffff817c8695)
Location: include/linux/skbuff.h:2083
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff817e1b1e)
Location: include/linux/skbuff.h:2083
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff817e7029)
Location: include/linux/skbuff.h:2083
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff817edd63)
Location: include/linux/skbuff.h:2083
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f046d)
Location: include/linux/skbuff.h:2083
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff817f34d5)
Location: include/linux/skbuff.h:2083
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/skbuff.h:2083
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81800ead)
Location: include/linux/skbuff.h:2083
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818027d8)
Location: include/linux/skbuff.h:2083
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
In net/core/skbuff.c (ffffffff81772042)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81780752)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - net/core/dev.c:__skb_csum_offload_chk
```
```
In net/core/tso.c (ffffffff8179fd05)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff817a822c)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cbe14)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eb67d)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff817f32c4)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff817f7f0d)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/igmp.c (ffffffff81805884)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_input.c (ffffffff818357e3)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff8184ff8e)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff81854a13)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff8185c5a3)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185f2bd)
Location: include/linux/skbuff.h:2218
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff818625c7)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff818642d9)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/ip6_offload.c (ffffffff8187266c)
Location: include/linux/skbuff.h:2218
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81873ade)
Location: include/linux/skbuff.h:2218
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
In net/core/skbuff.c (ffffffff8179f142)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (0)
Location: include/linux/skbuff.h:2235
Inline: True
```
```
In net/core/tso.c (ffffffff817ce6d5)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff817d6d7a)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fba53)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181bfed)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff818240a4)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81828dad)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/igmp.c (ffffffff81836cd4)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_input.c (ffffffff81867313)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff81881d8e)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff81886745)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff8188e4b3)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818912dd)
Location: include/linux/skbuff.h:2235
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81894658)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff8189698d)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6c6c)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a815e)
Location: include/linux/skbuff.h:2235
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
In net/core/skbuff.c (ffffffff817be5b2)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff817eaccd)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff817edb85)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff817f6dea)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181be30)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183c7b7)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81844dd7)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8184a08d)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/igmp.c (ffffffff81857d31)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff8188ba93)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff818a856e)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/raw.c (ffffffff818accbd)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff818b4b02)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b78d7)
Location: include/linux/skbuff.h:2284
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff818baa39)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff818bcf0b)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd69b)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ce99e)
Location: include/linux/skbuff.h:2284
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
In net/core/skbuff.c (ffffffff81837f52)
Location: include/linux/skbuff.h:2371
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2371
Inline: True
```
```
In net/core/filter.c (ffffffff8186777d)
Location: include/linux/skbuff.h:2371
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff81869dc5)
Location: include/linux/skbuff.h:2371
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff818733cd)
Location: include/linux/skbuff.h:2371
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189ad66)
Location: include/linux/skbuff.h:2371
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bbee8)
Location: include/linux/skbuff.h:2371
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff818c483d)
Location: include/linux/skbuff.h:2371
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff818c9c48)
Location: include/linux/skbuff.h:2371
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/igmp.c (ffffffff818d74f1)
Location: include/linux/skbuff.h:2371
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff8190cd73)
Location: include/linux/skbuff.h:2371
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/route.c (ffffffff8191a6b0)
Location: include/linux/skbuff.h:2371
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/udp.c (ffffffff8192b01e)
Location: include/linux/skbuff.h:2371
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/raw.c (ffffffff8192f645)
Location: include/linux/skbuff.h:2371
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff8193785a)
Location: include/linux/skbuff.h:2371
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193a717)
Location: include/linux/skbuff.h:2371
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff8193da49)
Location: include/linux/skbuff.h:2371
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff8194002b)
Location: include/linux/skbuff.h:2371
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e567)
Location: include/linux/skbuff.h:2371
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff8195248d)
Location: include/linux/skbuff.h:2371
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff8195384e)
Location: include/linux/skbuff.h:2371
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
In net/core/skbuff.c (ffffffff81882445)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2383
Inline: True
```
```
In net/core/filter.c (ffffffff818b57e2)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff818b9a85)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff818c4b47)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff818ef20d)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819118c2)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff8191a4e8)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8191fcec)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/igmp.c (ffffffff8192de3c)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_input.c (ffffffff81964187)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/route.c (ffffffff81975f3d)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/udp.c (ffffffff81985309)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/raw.c (ffffffff819882ed)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff819906a5)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819935d0)
Location: include/linux/skbuff.h:2383
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81996964)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81998e74)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7785)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff819aba10)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad270)
Location: include/linux/skbuff.h:2383
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
In net/core/skbuff.c (ffffffff818a2f15)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2461
Inline: True
```
```
In net/core/filter.c (ffffffff818dc3e6)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff818e0845)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff818edbb7)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191ca30)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819400b2)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81948d43)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8194e95c)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/igmp.c (ffffffff8195d6fd)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_input.c (ffffffff81999a47)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff819abb8b)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/udp.c (ffffffff819bba89)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff819becfb)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff819c6dd5)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c99a0)
Location: include/linux/skbuff.h:2461
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff819cd264)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff819cf96a)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de2f2)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff819e25a7)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3c17)
Location: include/linux/skbuff.h:2461
Inline: True
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
In net/core/skbuff.c (ffffffff818edb95)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2547
Inline: True
```
```
In net/core/filter.c (ffffffff819294e6)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff8192eed5)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff8193e4ed)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff8197ed90)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a45c2)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff819ad3bc)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819b313c)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/igmp.c (ffffffff819c2371)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6245)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_input.c (ffffffff81a05977)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a1473e)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/udp.c (ffffffff81a2a6c9)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81a2dc02)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81a360bf)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a38450)
Location: include/linux/skbuff.h:2547
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c325)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a3e681)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4ce52)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81a5126a)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a528a5)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In net/core/skbuff.c (ffffffff8191fc95)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/core/filter.c (ffffffff8195bbc2)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff81961145)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff8197137d)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b6190)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db2c2)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff819e407c)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819e9ebc)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/igmp.c (ffffffff819f8f11)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2cec5)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c4f6)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a4b32e)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/udp.c (ffffffff81a61219)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81a6476d)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81a6cbdf)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6efa0)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a72fa5)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a752f1)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83a22)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87e8a)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a89485)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In drivers/net/tun.c (ffffffff8188adc7)
Location: include/linux/skbuff.h:2584
Inline: True
```
```
In net/core/skbuff.c (ffffffff819f3245)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81a00d76)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81a2edb5)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff81a34672)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81a452d5)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa09f4)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8352)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81ad172e)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ad7a9a)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err_encap
```
```
In net/ipv4/igmp.c (ffffffff81ae6cca)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1edcd)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81b21ac6)
Location: include/linux/skbuff.h:2584
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b23125)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_push_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81b31b96)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81b411ae)
Location: include/linux/skbuff.h:2584
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b5784c)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err_encap
```
```
In net/ipv6/raw.c (ffffffff81b5b8da)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81b6629b)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6842f)
Location: include/linux/skbuff.h:2584
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d42d)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81b6f52d)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e802)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81b8334f)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b84915)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
```
```
In net/packet/af_packet.c (ffffffff81b86d17)
Location: include/linux/skbuff.h:2584
Inline: True
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
In drivers/net/tun.c (ffffffff81898ee7)
Location: include/linux/skbuff.h:2610
Inline: True
```
```
In net/core/skbuff.c (ffffffff819f3275)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81a01186)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81a308cb)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff81a36990)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81a494ea)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa9e64)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad42f2)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81add7ae)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ae40ea)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err_encap
```
```
In net/ipv4/icmp.c (ffffffff81ae8c95)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
```
```
In net/ipv4/igmp.c (ffffffff81af3b9a)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2d67d)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30496)
Location: include/linux/skbuff.h:2610
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b31b15)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_push_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81b40796)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81b4fc6e)
Location: include/linux/skbuff.h:2610
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b65d5c)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err_encap
```
```
In net/ipv6/raw.c (ffffffff81b6a126)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81b74a1b)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b76c9f)
Location: include/linux/skbuff.h:2610
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b7bedd)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81b7e05d)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d812)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81b929fe)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b94275)
Location: include/linux/skbuff.h:2610
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
```
```
In net/packet/af_packet.c (ffffffff81b967f7)
Location: include/linux/skbuff.h:2610
Inline: True
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
In drivers/net/tun.c (ffffffff8187c5e7)
Location: include/linux/skbuff.h:2626
Inline: True
```
```
In net/core/skbuff.c (ffffffff819d94b5)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff819e79e5)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81a190bc)
Location: include/linux/skbuff.h:2626
Inline: True
```
```
In net/core/tso.c (ffffffff81a1db0c)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81a2e44c)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a95030)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf392)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81ac887e)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81acf2da)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff81ad4162)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
```
```
In net/ipv4/igmp.c (ffffffff81adf34d)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c101)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e309)
Location: include/linux/skbuff.h:2626
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b1f845)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_push_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e026)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81b3dacc)
Location: include/linux/skbuff.h:2626
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b53dff)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81b58456)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81b6353f)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b656df)
Location: include/linux/skbuff.h:2626
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a9c1)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81b6cc61)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c6c2)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81b56)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b83375)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81b85797)
Location: include/linux/skbuff.h:2626
Inline: True
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
In drivers/net/tun.c (ffffffff8190db8c)
Location: include/linux/skbuff.h:2655
Inline: True
```
```
In net/core/skbuff.c (ffffffff81a89475)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81a98105)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81ac736c)
Location: include/linux/skbuff.h:2655
Inline: True
```
```
In net/core/tso.c (ffffffff81ad15ac)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81ae3a2c)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b50490)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7cecb)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81b870e8)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81b8dcfa)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff81b92e52)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
```
```
In net/ipv4/igmp.c (ffffffff81b9e82d)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0a8d)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81be2df9)
Location: include/linux/skbuff.h:2655
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81be4485)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_push_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4306)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81c0432c)
Location: include/linux/skbuff.h:2655
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81c1d2af)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81c1f7e6)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81c2afff)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2c8cf)
Location: include/linux/skbuff.h:2655
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81c32821)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81c34b1b)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47696)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4dbab)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f445)
Location: include/linux/skbuff.h:2655
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81c51b0c)
Location: include/linux/skbuff.h:2655
Inline: True
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
In drivers/net/tun.c (ffffffff81a63587)
Location: include/linux/skbuff.h:3024
Inline: True
```
```
In net/core/skbuff.c (ffffffff81bfe7a5)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81c0fdd0)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81c43bcc)
Location: include/linux/skbuff.h:3024
Inline: True
```
```
In net/core/tso.c (ffffffff81c4eea0)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81c67207)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdea71)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0ce0d)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81d17dd4)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81d1ee2a)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff81d25062)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
```
```
In net/ipv4/igmp.c (ffffffff81d30b92)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff81d777af)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81d79f99)
Location: include/linux/skbuff.h:3024
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81d7b936)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_push_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d017)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81d9e6f0)
Location: include/linux/skbuff.h:3024
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81db9909)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81dbc401)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81dc82af)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcd5fd)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
```
```
In net/ipv6/exthdrs.c (ffffffff81dd001d)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81dd24d4)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6a69)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee27a)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81defe75)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81df3af7)
Location: include/linux/skbuff.h:3024
Inline: True
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
In drivers/net/tun.c (ffffffff81beebe0)
Location: include/linux/skbuff.h:2918
Inline: True
```
```
In net/core/skbuff.c (ffffffff81dad1b5)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81dbf810)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81df7dbc)
Location: include/linux/skbuff.h:2918
Inline: True
```
```
In net/core/tso.c (ffffffff81e03f50)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81e1e323)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9e991)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2892)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81ede654)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ee5f3a)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff81eec642)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
```
```
In net/ipv4/igmp.c (ffffffff81ef8ca2)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff81f4403f)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81f46dd9)
Location: include/linux/skbuff.h:2918
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81f489d6)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_push_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b415)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81f6d5e0)
Location: include/linux/skbuff.h:2918
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81f89999)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81f8d6c6)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81f9903f)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e722)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
```
```
In net/ipv6/exthdrs.c (ffffffff81fa13ad)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81fa3954)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9891)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc27d9)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc3f95)
Location: include/linux/skbuff.h:2918
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81fc89b0)
Location: include/linux/skbuff.h:2918
Inline: True
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
In drivers/net/tun.c (ffffffff81c4792f)
Location: include/linux/skbuff.h:2972
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81c4e1cf)
Location: include/linux/skbuff.h:2972
Inline: True
```
```
In net/core/skbuff.c (ffffffff81e1d0b5)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81e2f484)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81e6749c)
Location: include/linux/skbuff.h:2972
Inline: True
```
```
In net/core/tso.c (ffffffff81e7673d)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81e95666)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efd190)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f3156e)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81f3d9a2)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81f4573a)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff81f4c432)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
```
```
In net/ipv4/igmp.c (ffffffff81f58712)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3901)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6790)
Location: include/linux/skbuff.h:2972
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81fa8846)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_push_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb1e7)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81fcd700)
Location: include/linux/skbuff.h:2972
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81fe9249)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81fedbf8)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81ff9a0f)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81fff1de)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
```
```
In net/ipv6/exthdrs.c (ffffffff82001c4d)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/datagram.c (ffffffff82004233)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019f21)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff82023757)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff82024fb5)
Location: include/linux/skbuff.h:2972
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff820292ef)
Location: include/linux/skbuff.h:2972
Inline: True
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
In drivers/net/tun.c (ffffffff81cfd242)
Location: include/linux/skbuff.h:2979
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81d04242)
Location: include/linux/skbuff.h:2979
Inline: True
```
```
In net/core/skbuff.c (ffffffff81eda7a5)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81ef96ec)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81f2665c)
Location: include/linux/skbuff.h:2979
Inline: True
```
```
In net/core/tso.c (ffffffff81f36700)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff81f57bdd)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc1241)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff775e)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff82003ac7)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff8200b88a)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff82012542)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
```
```
In net/ipv4/igmp.c (ffffffff8201ebd2)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035564)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
```
```
In net/xfrm/xfrm_output.c (ffffffff82070c31)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff82073a80)
Location: include/linux/skbuff.h:2979
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff82075b36)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_push_skb
```
```
In net/ipv6/ip6_input.c (ffffffff820885f7)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff8209af50)
Location: include/linux/skbuff.h:2979
Inline: True
```
```
In net/ipv6/udp.c (ffffffff820b5d59)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff820bb808)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/reassembly.c (ffffffff820c767f)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cdeee)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
```
```
In net/ipv6/exthdrs.c (ffffffff820d0a4d)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/datagram.c (ffffffff820d2ff3)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8ef1)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f4295)
Location: include/linux/skbuff.h:2979
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff820f8d42)
Location: include/linux/skbuff.h:2979
Inline: True
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
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109eb5ec)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
```
```
In net/core/skbuff.c (ffff800010bba700)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/core/tso.c (ffff800010c04a28)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffff800010c19da8)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffff800010c65e44)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e6b4)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffff800010c98a90)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffff800010c9f6d0)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/igmp.c (ffff800010cae6d4)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffff800010cebb20)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_input.c (ffff800010cfd7dc)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffff800010d0e398)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/udp.c (ffff800010d24480)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffff800010d2a5d8)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffff800010d358d8)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d36a08)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/ipv6/exthdrs.c (ffff800010d3ba88)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffff800010d3dccc)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f868)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffff800010d54a40)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffff800010d562b8)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In drivers/net/ethernet/freescale/fec_main.c (c0acd8c8)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
```
```
In net/core/skbuff.c (c0cd6ebc)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/core/filter.c (c0d175d8)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (c0d1de80)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (c0d2f5f8)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (c0d75a58)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (c0d9d600)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (c0da68f8)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c0dac9f0)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/igmp.c (c0dbc9ec)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (c0df3878)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_input.c (c0e04fd8)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (c0e14d0c)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/udp.c (c0e282cc)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (c0e2e64c)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (c0e37b7c)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (c0e3a6bc)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/ipv6/exthdrs.c (c0e3e520)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (c0e40f6c)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (c0e50508)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (c0e5506c)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (c0e568a8)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In net/core/skbuff.c (c000000000c93290)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/core/filter.c (c000000000ce53bc)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (c000000000cee9c4)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (c000000000d06868)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (c000000000d6a69c)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d03c)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (c000000000daa290)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c000000000db2198)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/igmp.c (c000000000dc6acc)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (c000000000e0f574)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_input.c (c000000000e258c0)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (c000000000e3a4b8)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/udp.c (c000000000e56cfc)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (c000000000e5b7cc)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (c000000000e679a4)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6a1d8)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/ipv6/exthdrs.c (c000000000e6f36c)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (c000000000e721f0)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86e20)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (c000000000e8d5c0)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f468)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In net/core/skbuff.c (ffffffe000749994)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/core/filter.c (ffffffe00077fa2c)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffe000783612)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffe00079110e)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cd50a)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eea16)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffe0007f6b88)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffe0007fc212)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/igmp.c (ffffffe000809a68)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffe0008393fc)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_input.c (ffffffe000847d36)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffe000855e8c)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/udp.c (ffffffe000867fc6)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffe00086ae1e)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffe000872d94)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875216)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffe00087851e)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffe00087a308)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe00088800a)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c3bc)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088db58)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In net/core/skbuff.c (ffffffff818bfc95)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/core/filter.c (ffffffff818fbb92)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff81901115)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff8191134d)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81956000)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b132)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81983eec)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81989d2c)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/igmp.c (ffffffff81998cb1)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc555)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_input.c (ffffffff819dbb86)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff819ea9be)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/udp.c (ffffffff81a008a9)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81a03dfd)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81a0c26f)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0e630)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a12635)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a14981)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a230b2)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81a2751a)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28b15)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In drivers/net/vxlan.c (ffffffff81770625)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_err_lookup
```
```
In net/core/skbuff.c (ffffffff81879bd5)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/core/filter.c (ffffffff818b59c2)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff818baf45)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff818cb10d)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff8190faf0)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934bf2)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff8193d9ac)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819437ec)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/igmp.c (ffffffff81952771)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff81989345)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_input.c (ffffffff81998946)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff819a777e)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/udp.c (ffffffff819bd669)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff819c0bbd)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff819c902f)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb3f0)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff819cf3f5)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff819d1741)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dfe72)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff819e42da)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5d05)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In net/core/skbuff.c (ffffffff81910c95)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/core/filter.c (ffffffff8194cbc2)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff81952145)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff8196237d)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c07d0)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5902)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff819ee6bc)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819f44fc)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/igmp.c (ffffffff81a03551)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff81a36fd5)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_input.c (ffffffff81a46606)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a5543e)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/udp.c (ffffffff81a6b329)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81a6e87d)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81a76cef)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a790b0)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a7d0b5)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a7f401)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8db32)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81a930ca)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a946c5)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In net/core/skbuff.c (ffffffff81931df5)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/core/filter.c (ffffffff8196e582)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff81973b85)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-traces.c (ffffffff819845ed)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff819ca1b0)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef5c2)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff819f8712)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819fe6bc)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/igmp.c (ffffffff81a0daa1)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42965)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_input.c (ffffffff81a52336)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a6143e)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/udp.c (ffffffff81a77939)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81a7aea5)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81a8330f)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a85870)
Location: include/linux/skbuff.h:2561
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a89905)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a8bcc1)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a832)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f270)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa0825)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
</details>
</li>
</ul>

## Differences

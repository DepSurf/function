# Function: <code>__csum_partial</code>

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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_to_user
  - arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_from_user
  - block/t10-pi.c:t10_pi_ip_fn
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:csum_partial_ext
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
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
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/unix/af_unix.c:unix_autobind
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
c0000000000a99a0-c0000000000a99a0: __csum_partial (STB_GLOBAL)
```
</details>
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

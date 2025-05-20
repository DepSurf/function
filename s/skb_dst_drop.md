# Function: <code>skb_dst_drop</code>

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
In net/core/skbuff.c (ffffffff817053fd)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/dev.c (ffffffff8171425c)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81724c76)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81731b9b)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff817554bf)
Location: include/net/dst.h:290
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81759df4)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_options.c (ffffffff8175b423)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8175c588)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81761e2f)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff8176ff3b)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177d128)
Location: include/net/dst.h:290
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81782a82)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a4bc0)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff817a94ff)
Location: include/net/dst.h:290
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff817ac229)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b604d)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff817bbd7c)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc319)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff817c4b08)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff817d70c6)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff817e4217)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff817e5c91)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff817ee321)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff817f37bb)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff817f9fe5)
Location: include/net/dst.h:290
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff817fdc95)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/packet/af_packet.c (ffffffff818068b4)
Location: include/net/dst.h:290
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv
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
In net/core/skbuff.c (ffffffff8176cc64)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff817840e5)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff8178e745)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff8179ce01)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff817c1651)
Location: include/net/dst.h:287
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff817c624d)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_options.c (ffffffff817c7728)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff817c9388)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff817ce16f)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff817ded8b)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea7c7)
Location: include/net/dst.h:287
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efbd5)
Location: include/net/dst.h:287
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81816d3f)
Location: include/net/dst.h:287
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff81819561)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff8182306f)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81828d2d)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81829238)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81831bd8)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff818457d6)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff818524ef)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff818550f0)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81856556)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff8185cb61)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818626db)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8186984f)
Location: include/net/dst.h:287
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff8186d5d2)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/packet/af_packet.c (ffffffff8187a247)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff8179a0e4)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff817b16f5)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff817bc015)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff817cae11)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff817f1b5e)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_noref
```
```
In net/ipv4/ip_fragment.c (ffffffff817f5d4d)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_options.c (ffffffff817f7218)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff817f8f28)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fded5)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff8180f11b)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181ad67)
Location: include/net/dst.h:287
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818205e5)
Location: include/net/dst.h:287
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8184850f)
Location: include/net/dst.h:287
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff8184ae07)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff818549b8)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a70d)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8185ac18)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81863608)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff8187753f)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81884365)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81886e60)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81888346)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff8188eaa2)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8189477b)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8189c69f)
Location: include/net/dst.h:287
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff818a03bd)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a4683)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/packet/af_packet.c (ffffffff818aeab7)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff817b93a4)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff817cc8ed)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff817da6f5)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff817e9efc)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff8181172f)
Location: include/net/dst.h:293
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff818160d5)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_options.c (ffffffff818175f9)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81819348)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181e2ef)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff8182f05b)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183b58b)
Location: include/net/dst.h:293
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840af5)
Location: include/net/dst.h:293
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81869cf6)
Location: include/net/dst.h:293
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff8186e877)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81878487)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8187e865)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8187ea2f)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81888a68)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff8189c83c)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff818aa487)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff818ad2da)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff818aea25)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff818b4e0d)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818bab61)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff818c2a6b)
Location: include/net/dst.h:293
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff818c6a00)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818cae97)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/packet/af_packet.c (ffffffff818d37ff)
Location: include/net/dst.h:293
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff8183346d)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff8184625d)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81854e95)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff8186558c)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81890ce7)
Location: include/net/dst.h:296
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81895363)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_options.c (ffffffff818967b3)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81897908)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189d1f9)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff818aea17)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c0265)
Location: include/net/dst.h:296
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818ea426)
Location: include/net/dst.h:296
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff818ef237)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8d90)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff818ff8c3)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffac5)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81909bf8)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff8191f45f)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff8192cf97)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff8192feea)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819316e5)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81937b7d)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193db71)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81944e84)
Location: include/net/dst.h:296
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81949e33)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e7d7)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff8194fb50)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:lookup_nexthop
```
```
In net/packet/af_packet.c (ffffffff81958725)
Location: include/net/dst.h:296
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff8187d905)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff8188db35)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff818a1843)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff818b30a1)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff818e4ae4)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff818e9480)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_options.c (ffffffff818eaa8e)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff818ebc18)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f16b9)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff819040d7)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81915dbc)
Location: include/net/dst.h:279
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81940a8e)
Location: include/net/dst.h:279
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff81945bd7)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194f7d1)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819561c7)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819566cd)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81960f28)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81977585)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81984c34)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81988ce2)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff8198a1fe)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81990b24)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81996a71)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8199e1cb)
Location: include/net/dst.h:279
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff819a2dac)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7ac3)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff819a89f2)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (ffffffff819b2175)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff8189d3e3)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff818ae9c5)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff818c4783)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff818d7ef1)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff819119d4)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81916535)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_options.c (ffffffff81917806)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81918ee8)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191f219)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff819322b7)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193f501)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8194456c)
Location: include/net/dst.h:279
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81970981)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81975ef7)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81982df2)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8198adfa)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b1c3)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819957d8)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff819ad18d)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff819bb21a)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff819bf640)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c0aa8)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff819c725f)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cd36b)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819d4c8b)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff819d9a77)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de613)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff819df51c)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (ffffffff819e909c)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff818e7c63)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff818fa2b5)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff819105c0)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81925c71)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff819432b1)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff8197414c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff819783c7)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff81979f12)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8197b004)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81981b69)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81996047)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a38e1)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a8b5c)
Location: include/net/dst.h:268
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819da1b7)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff819dfa8e)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ec9e5)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819f5825)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819f66e8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a0109a)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a12b7d)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81a29e2c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a2e2bb)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a2f798)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81a363b2)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c417)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a43adc)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff81a482ec)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4d183)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e0c4)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (ffffffff81a57510)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff81919e83)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff8192c3f5)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81942c2d)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff819582c1)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81978233)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (ffffffff819aab6c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff819aed37)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff819b0872)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819b1974)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b83a9)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff819ccbc7)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819da5e3)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819df7fc)
Location: include/net/dst.h:268
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a110a4)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81a16abe)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a23a01)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2c4cd)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d368)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a37c78)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a4976d)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81a6094c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a64e2b)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a662e8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81a6ced2)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a73097)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a7a75c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff81a7ee9c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83d53)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a84cfb)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (ffffffff81a8e558)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff819ec053)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81a00e55)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81a12efd)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81a29bb1)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81a4cd47)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (ffffffff81a94e94)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81a9914c)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff81a9a706)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81a9c1c6)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa2cc9)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81ab8e88)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac77a1)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acccac)
Location: include/net/dst.h:267
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b02921)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81b07afe)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15955)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e9c8)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1ef48)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/ipv6/ip6_output.c (ffffffff81b2dc5a)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81b401bc)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81b598d2)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b5d6df)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5ecf2)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81b65e59)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d639)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b7602e)
Location: include/net/dst.h:267
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81b79aec)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7eb23)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81b80097)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/packet/af_packet.c (ffffffff81b8b0cc)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff819eb863)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81a01265)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81a13266)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81a2a511)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81a52a09)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (ffffffff81a9ee94)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa30bc)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff81aa465c)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81aa6026)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aacfd9)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81ac4278)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad31c1)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8cac)
Location: include/net/dst.h:267
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b10cef)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81b15ed7)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b23dba)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2d3d7)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2d7f8)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/ipv6/ip6_output.c (ffffffff81b3c6aa)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81b4eb9c)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81b67f32)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b6becf)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b6d472)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81b745c9)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffffffff81b7c0e9)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b84dae)
Location: include/net/dst.h:267
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81b88a3a)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8db33)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81b8eb59)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/packet/af_packet.c (ffffffff81b9a0e9)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff819d1e53)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff819f02ef)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff819fa805)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81a116b1)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81a38180)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/skmsg.c (ffffffff81a4e5f1)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
```
In net/ipv4/route.c (ffffffff81a89e0c)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e0cc)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff81a8f750)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81a911e6)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a98229)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81aaf378)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abe251)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3d1c)
Location: include/net/dst.h:270
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81afe8e8)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81b03d44)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11a91)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1b01a)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c53e)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81b29b0a)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81b3c9cc)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81b56120)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b5a1f0)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5b808)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81b63028)
Location: include/net/dst.h:270
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b6abcd)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b73a62)
Location: include/net/dst.h:270
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81b777b9)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7ca03)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81b7dc49)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/packet/af_packet.c (ffffffff81b8905b)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff81a81ad3)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81aa1711)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81aad745)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81ac2b91)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81aedfc0)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/core/skmsg.c (ffffffff81b07331)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
```
In net/ipv4/route.c (ffffffff81b44c9c)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81b492bc)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff81b4a990)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81b4c556)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b536c1)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81b6c084)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7bd11)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b823ac)
Location: include/net/dst.h:270
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bc0104)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81bc5ff4)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd5589)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdf57e)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0e43)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81bef69a)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81c03307)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81c1c79d)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81c2186b)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81c22f18)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81c2aad8)
Location: include/net/dst.h:270
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81c32a2d)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81c3e044)
Location: include/net/dst.h:270
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81c4228a)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47b04)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81c48f77)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/packet/af_packet.c (ffffffff81c5516b)
Location: include/net/dst.h:270
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff81bfd979)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81c1974b)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81c22bb7)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81c3d850)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81c70e02)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/core/skmsg.c (ffffffff81c8bdcf)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
```
In net/ipv4/route.c (ffffffff81cd1caa)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6bba)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff81cd77e2)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81cd9ba6)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ce1137)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81cfc033)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0bc11)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d128ac)
Location: include/net/dst.h:271
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d54aff)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81d5b328)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6bd9d)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81d762fd)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77d30)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81d8817a)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81d9d293)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81db901f)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81dbe72f)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81dbfd8a)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81dc8182)
Location: include/net/dst.h:271
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81dd0211)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81ddc6c1)
Location: include/net/dst.h:271
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81de0c8d)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6f68)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81de866c)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81dec21e)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/packet/af_packet.c (ffffffff81df48a3)
Location: include/net/dst.h:271
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff81dae6a9)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81dca78b)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:tun_dst_unclone
```
```
In net/core/neighbour.c (ffffffff81dd81b8)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81df3d30)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81e28e82)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/core/skmsg.c (ffffffff81e48330)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
```
In net/ipv4/route.c (ffffffff81e921e7)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81e9717c)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff81e97e64)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81e9a336)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea1547)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81ec0bb3)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed0b31)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed86ec)
Location: include/net/dst.h:265
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f1ed5b)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81f257b8)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f370dd)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42a61)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f444c7)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81f55f2a)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81f6c1c3)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81f88f90)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81f8ebf5)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81f904ea)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81f98f09)
Location: include/net/dst.h:265
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81fa15a1)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81fad751)
Location: include/net/dst.h:265
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81fb30cd)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9df8)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb7ac)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfe6e)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/packet/af_packet.c (ffffffff81fc9b33)
Location: include/net/dst.h:265
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff81e1e561)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81e3b30c)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:tun_dst_unclone
```
```
In net/core/neighbour.c (ffffffff81e494d5)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81e65910)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81e9e4b6)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/core/skmsg.c (ffffffff81ea3af5)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
```
In net/ipv4/route.c (ffffffff81ef0970)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef59a8)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff81ef66c1)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81ef8c96)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81effd49)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81f1f123)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f302f1)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f377fc)
Location: include/net/dst.h:279
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f7e85b)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81f85348)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f969a1)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa2264)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3ca6)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81fb58fc)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81fcc2c8)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81fe834f)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81fef513)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81ff0d4a)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81ff98d5)
Location: include/net/dst.h:279
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff8200173d)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8200df01)
Location: include/net/dst.h:279
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff820137bd)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a52b)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff8201be6c)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020e46)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/packet/af_packet.c (ffffffff8202a45c)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff81edbc24)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81ef977a)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:tun_dst_unclone
```
```
In net/core/neighbour.c (ffffffff81f081c5)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81f24ac0)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81f60c2f)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/core/skmsg.c (ffffffff81f663f5)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
```
In net/ipv4/route.c (ffffffff81fb4ac1)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9958)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff81fba651)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81fbcbb6)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc3f09)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81fe37d1)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff6181)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffd8cc)
Location: include/net/dst.h:272
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff82044f00)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff8204ba04)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff82063dcf)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f648)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff82070fd3)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff82082fcc)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff82099aab)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff820b6ea3)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff820bd0f5)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff820be92a)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff820c7545)
Location: include/net/dst.h:272
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820dca91)
Location: include/net/dst.h:272
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff820e2922)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e94eb)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff820eae3c)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820eff73)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/packet/af_packet.c (ffffffff820f9f67)
Location: include/net/dst.h:272
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffff800010bb3d80)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffff800010bc8a08)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffff800010be3210)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffff800010c010e8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffff800010c1ea98)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (ffff800010c5aef8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffff800010c5f8fc)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffff800010c60e58)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffff800010c62340)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffff800010c69748)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffff800010c7f79c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8d9c4)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93398)
Location: include/net/dst.h:268
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010cccd74)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffff800010cd2708)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0c80)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffff800010ceae10)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec1c8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffff800010cf83e8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffff800010d11e98)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffff800010d2654c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffff800010d2ace8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffff800010d2c278)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffff800010d35618)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffff800010d3bbe0)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffff800010d4422c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffff800010d4a764)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4fab4)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffff800010d50da4)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (ffff800010d5b6f8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (c0cd2338)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (c0ce4b00)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (c0cfbc34)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (c0d14974)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (c0d36ae8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (c0d6a3e8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (c0d6e968)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (c0d70834)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (c0d71b24)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (c0d78984)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (c0d8e8b8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (c0d9c6e0)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (c0da1b84)
Location: include/net/dst.h:268
Inline: True
```
```
In net/ipv4/ipmr.c (c0dd73ec)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (c0ddc624)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (c0de9f9c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (c0df3154)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c0df40e0)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (c0dffb2c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (c0e12c88)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (c0e29a14)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (c0e2ec04)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c0e30108)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (c0e376ec)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (c0e3e5ec)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (c0e46788)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (c0e4b6a8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (c0e507fc)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (c0e51904)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (c0e5b81c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (c000000000c8a560)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (c000000000ca517c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (c000000000cc4cec)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (c000000000ce0c7c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (c000000000d10c3c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (c000000000d5cc5c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (c000000000d61ec4)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (c000000000d64114)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (c000000000d655f4)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (c000000000d6e440)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (c000000000d8a04c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9b1bc)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (c000000000da35c8)
Location: include/net/dst.h:268
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000de8a28)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (c000000000df0cf8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (c000000000e02f18)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (c000000000e0ef84)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c000000000e102d8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (c000000000e203bc)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (c000000000e37ea0)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (c000000000e5619c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (c000000000e5bfc0)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c000000000e5dae8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (c000000000e67690)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (c000000000e6f444)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (c000000000e7a6d0)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (c000000000e80030)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e87274)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (c000000000e88c24)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (c000000000e95cac)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffe0007447b0)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffe000755208)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffe0007693be)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffe00077f206)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffe0007986b0)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (ffffffe0007c42ae)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c775e)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffe0007c9054)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffe0007c9ede)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf5b2)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffe0007e18f0)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007edf0c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f28ec)
Location: include/net/dst.h:268
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe00081ee0c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffe000823a42)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082f8f4)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffe000838b30)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffe0008399de)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffe0008441dc)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffe000853e92)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffe000866bc8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffe00086b324)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffe00086c556)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffe0008729aa)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffffffe000878672)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffe00088015a)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffe00088363a)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe0008881f4)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffe0008890c4)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (ffffffe00089283c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff818b9e83)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff818cc3f5)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff818e2bfd)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff818f8291)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff819180a3)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (ffffffff8194a9dc)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff8194eba7)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff819506e2)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819517e4)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81958219)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff8196ca37)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197a453)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197f66c)
Location: include/net/dst.h:268
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819b0a34)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff819b614e)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c3091)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819cbb5d)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc9f8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819d7308)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff819e8dfd)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff819fffdc)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a044bb)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a05978)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81a0c562)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a12727)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a19dec)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff81a1e52c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a233e3)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a2438b)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (ffffffff81a2dbe8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff81873dd3)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81886485)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff8189ca3d)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff818b20c1)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff818d1e53)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (ffffffff819044cc)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81908697)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff8190a1d2)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8190b2d4)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81911d09)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81926527)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81933f13)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8193912c)
Location: include/net/dst.h:268
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196d064)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81972f3e)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fe81)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8198894d)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819897e8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819940c8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff819a5bbd)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff819bcd9c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff819c127b)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c2738)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff819c9322)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cf4e7)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819d6bac)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff819db2ec)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819e01a3)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff819e114b)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (ffffffff819eadd8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff8190ae83)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff8191d3f5)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81933c2d)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff819492c1)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81969233)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (ffffffff819b51ac)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9377)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff819baeb2)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819bbfb4)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c29e9)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff819d7207)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e4c23)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e9e3c)
Location: include/net/dst.h:268
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1b2d4)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81a209ee)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2db11)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a365dd)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a37478)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a41d88)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a5387d)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81a6aa5c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a6ef3b)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a703f8)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81a76fe2)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a7d1a7)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a8486c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff81a88fac)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8de63)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ee0b)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a90b65)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
```
```
In net/packet/af_packet.c (ffffffff81a99798)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In net/core/skbuff.c (ffffffff8192bf83)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff8193e915)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff8195402d)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff8196abd1)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff8198b613)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (ffffffff819be8ef)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff819c2c67)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff819c47bd)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819c58c4)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cc3e9)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff819e0e27)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819edf83)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f3c6c)
Location: include/net/dst.h:268
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a261b4)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81a2bf0e)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a392cd)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41f1c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42e08)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a4da18)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a5f86d)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81a7706c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a7b56b)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a7ca18)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81a83602)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a899f7)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a911bc)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff81a95c0c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9aba7)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bb7c)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (ffffffff81aa45a0)
Location: include/net/dst.h:268
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
</details>
</li>
</ul>

## Differences

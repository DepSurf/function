# Function: <code>refdst_drop</code>

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
In net/core/skbuff.c (ffffffff81705406)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/dev.c (ffffffff817142b5)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81724c7f)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81731ba7)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff817557f5)
Location: include/net/dst.h:278
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81759dfd)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_options.c (ffffffff8175b428)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8175c591)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81761e34)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff8176ff44)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177d131)
Location: include/net/dst.h:278
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81782a8e)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a4bc9)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff817a96a0)
Location: include/net/dst.h:278
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff817ac292)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b6062)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff817bbd85)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc322)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff817c4b11)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff817d70c6)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff817e4221)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff817e5c9a)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff817ee334)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff817f37c4)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff817fa146)
Location: include/net/dst.h:278
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff817fdc9e)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/packet/af_packet.c (ffffffff818068bd)
Location: include/net/dst.h:278
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
In net/core/skbuff.c (ffffffff8176cc6d)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff817840ef)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff8178e74e)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff8179ce0a)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff817c1996)
Location: include/net/dst.h:275
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff817c6256)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_options.c (ffffffff817c772d)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff817c9391)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff817ce174)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff817deeb6)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea7d0)
Location: include/net/dst.h:275
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efbe1)
Location: include/net/dst.h:275
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81816ee0)
Location: include/net/dst.h:275
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff818195ca)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81823084)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81828d36)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81829241)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81831be1)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff818457d6)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff818524f8)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff818550f9)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff8185655f)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff8185cb74)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818626e4)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff818699ac)
Location: include/net/dst.h:275
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff8186d5db)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/packet/af_packet.c (ffffffff8187a258)
Location: include/net/dst.h:275
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
In net/core/skbuff.c (ffffffff8179a0ed)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff817b16ff)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff817bc01e)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff817cae1a)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff817f1f41)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_noref
```
```
In net/ipv4/ip_fragment.c (ffffffff817f5d56)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_options.c (ffffffff817f721d)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff817f8f31)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fdeda)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff8180f251)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181ad70)
Location: include/net/dst.h:275
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818205f1)
Location: include/net/dst.h:275
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818486f6)
Location: include/net/dst.h:275
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff8184ae70)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff818549cd)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a716)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8185ac21)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81863611)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff8187753f)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81884373)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81886e69)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff8188834f)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff8188eab5)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81894784)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8189c7fc)
Location: include/net/dst.h:275
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff818a03c6)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a468c)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/packet/af_packet.c (ffffffff818aeac8)
Location: include/net/dst.h:275
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
In net/core/skbuff.c (ffffffff817b93ad)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff817cc8f6)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff817da757)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff817e9f05)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff8181172f)
Location: include/net/dst.h:281
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff818160e4)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_options.c (ffffffff818176c6)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81819351)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181e2f4)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff8182f064)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183b590)
Location: include/net/dst.h:281
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840b01)
Location: include/net/dst.h:281
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81869cff)
Location: include/net/dst.h:281
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff8186e880)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81878498)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8187e86e)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8187ea38)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81888a71)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff8189c8a1)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff818aa495)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff818ad2e3)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff818aea2e)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff818b4e1c)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818bab6a)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff818c2a74)
Location: include/net/dst.h:281
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff818c6a09)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818caea0)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/packet/af_packet.c (ffffffff818d3810)
Location: include/net/dst.h:281
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
In net/core/skbuff.c (ffffffff81833476)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81846266)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81854ef7)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81865595)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81890ce7)
Location: include/net/dst.h:284
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81895372)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_options.c (ffffffff81896872)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81897911)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189d1fe)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff818aea20)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c0271)
Location: include/net/dst.h:284
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818ea42f)
Location: include/net/dst.h:284
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff818ef240)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8da3)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff818ff8cc)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffaca)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81909c01)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff8191f464)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff8192cfa5)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff8192fef3)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819316ee)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81937b8c)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193db7a)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81944e8d)
Location: include/net/dst.h:284
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81949e3c)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e7e0)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff8194fb96)
Location: include/net/dst.h:284
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:lookup_nexthop
```
```
In net/packet/af_packet.c (ffffffff81958736)
Location: include/net/dst.h:284
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
In net/core/skbuff.c (ffffffff8187d916)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff8188db46)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff818a184c)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff818b31ab)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff818e4ae4)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff818e948f)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_options.c (ffffffff818eaa93)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff818ebc21)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f16be)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff819040e0)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81915dc1)
Location: include/net/dst.h:267
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81940a97)
Location: include/net/dst.h:267
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff81945be0)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194f7db)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819561d0)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8195684a)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81960f31)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff8197758e)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81984c39)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81988ceb)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff8198a207)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81990b31)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81996a7a)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8199e1d4)
Location: include/net/dst.h:267
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff819a2db5)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7b71)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff819a8a2a)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (ffffffff819b217a)
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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189d3ec)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff818ae9d6)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff818c478c)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff818d7ffc)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff819119d4)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81916544)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_options.c (ffffffff8191780f)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81918ef1)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191f21e)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff819322c0)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193f50a)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81944571)
Location: include/net/dst.h:267
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8197098a)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81975f00)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81982dfc)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8198ae03)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b46b)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819957e1)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff819ad196)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff819bb21f)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff819bf649)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c0ab1)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff819c726c)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cd374)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819d4c94)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff819d9a80)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de6be)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff819df554)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (ffffffff819e90a1)
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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e7c6c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff818fa2c7)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff819105ca)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81925dc4)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff819432bb)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff8197414c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff819783d6)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff81979f17)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8197b00d)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81981b6e)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81996050)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a38eb)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a8b61)
Location: include/net/dst.h:256
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819da1c1)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff819dfafc)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ec9ee)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819f582e)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819f68dc)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a010a3)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a12b87)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81a29e31)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a2e2c5)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a2f7a2)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81a363bb)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c421)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a43ae6)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff81a482f6)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4d234)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e0ce)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (ffffffff81a5751a)
Location: include/net/dst.h:256
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
In net/core/skbuff.c (ffffffff81919e8c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff8192c407)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81942c37)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81958414)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff8197823d)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (ffffffff819aab6c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff819aed46)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff819b0877)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819b197d)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b83ae)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff819ccbd0)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819da5ed)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819df801)
Location: include/net/dst.h:256
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a110ae)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81a16b2c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a23a06)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2c4d6)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d553)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a37c81)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a49777)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81a60951)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a64e35)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a662f2)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81a6cedb)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a730a1)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a7a766)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff81a7eea6)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83e04)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a84d05)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (ffffffff81a8e562)
Location: include/net/dst.h:256
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
In net/core/skbuff.c (ffffffff819ec0ad)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81a00e84)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81a12f5f)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81a29ccc)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81a4cef0)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (ffffffff81a94e94)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81a9915b)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff81a9a7f2)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81a9c334)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa2d14)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81ab9041)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac7a16)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acce19)
Location: include/net/dst.h:255
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b029d8)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81b07bcc)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15a56)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1ed29)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1ef60)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/ipv6/ip6_output.c (ffffffff81b2dd63)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81b40232)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81b5990f)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b5d789)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5ee6c)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81b65e64)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d647)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b7618f)
Location: include/net/dst.h:255
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81b79c3a)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7ec0b)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81b800f3)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/packet/af_packet.c (ffffffff81b8b30a)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void refdst_drop(long unsigned int refdst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eb8bd)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81a01294)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81a132c5)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81a2a62c)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81a52bb7)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/sched/sch_frag.c (ffffffff81a6f7ba)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ipv4/route.c (ffffffff81a9ee94)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa30cb)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff81aa4754)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81aa6194)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aad024)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81ac4464)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad3443)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8e19)
Location: include/net/dst.h:255
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b10dae)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81b15fb0)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b23ed9)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c040)
Location: include/net/dst.h:255
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2d810)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/ipv6/ip6_output.c (ffffffff81b3c7b3)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81b4ec1a)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81b67f6f)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b6bf79)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b6d5f1)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81b745d8)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffffffff81b7c0f7)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b84f1d)
Location: include/net/dst.h:255
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81b88b88)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8dc25)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81b8ebe3)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/packet/af_packet.c (ffffffff81b9a2da)
Location: include/net/dst.h:255
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81b2c040-ffffffff81b2c056: refdst_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void refdst_drop(long unsigned int refdst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d1ead)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff819f052c)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff819fa863)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81a117c5)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81a383cc)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/skmsg.c (ffffffff81a4e6be)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
```
In net/sched/sch_frag.c (ffffffff81a580ae)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ipv4/route.c (ffffffff81a89e0c)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e0db)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff81a8f849)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81a91354)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a98276)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81aaf63f)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abe4d3)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3e88)
Location: include/net/dst.h:258
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81afeac1)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81b03e26)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11aeb)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19ca0)
Location: include/net/dst.h:258
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c584)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81b29c13)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81b3ca4a)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81b561b2)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b5a29a)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5b98d)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81b63037)
Location: include/net/dst.h:258
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b6abdb)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b73bd1)
Location: include/net/dst.h:258
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81b77875)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7caf7)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81b7dcd3)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/packet/af_packet.c (ffffffff81b89233)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81b19ca0-ffffffff81b19cb6: refdst_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void refdst_drop(long unsigned int refdst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a81b2d)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81aa1956)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81aad7b0)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81ac2ccb)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81aee235)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/core/skmsg.c (ffffffff81b073fa)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
```
In net/sched/sch_frag.c (ffffffff81b11090)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ipv4/route.c (ffffffff81b44c9c)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81b492cb)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff81b4aab5)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81b4c70d)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b536fa)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81b6c35e)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7bff4)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b82522)
Location: include/net/dst.h:258
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bc0306)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81bc60ff)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd5615)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81bddfb0)
Location: include/net/dst.h:258
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0ede)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81bef7e7)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81c03396)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81c1c82f)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81c21915)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81c2309d)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81c2aae7)
Location: include/net/dst.h:258
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81c32a3b)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81c3e1e1)
Location: include/net/dst.h:258
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81c4236f)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47c60)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81c49070)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/packet/af_packet.c (ffffffff81c5534b)
Location: include/net/dst.h:258
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81bddfb0-ffffffff81bddfc6: refdst_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void refdst_drop(long unsigned int refdst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfd9f0)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81c19be8)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81c22c33)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81c3d9bd)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81c710b4)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/core/skmsg.c (ffffffff81c8bec0)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
```
In net/sched/sch_frag.c (ffffffff81c9805c)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ipv4/route.c (ffffffff81cd19c2)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6bf7)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff81cd78ef)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81cd9d5b)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ce113c)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81cfc162)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0bf2d)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d12a46)
Location: include/net/dst.h:259
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d54bd1)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81d5b3fc)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6be3c)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81d74bc0)
Location: include/net/dst.h:259
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77dec)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81d8830c)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81d9d365)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81db90d8)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81dbe7d0)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81dbff28)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81dc81c5)
Location: include/net/dst.h:259
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81dd021e)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81ddc856)
Location: include/net/dst.h:259
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81de0e31)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de70c1)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81de8796)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81dec3bb)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/packet/af_packet.c (ffffffff81df4ada)
Location: include/net/dst.h:259
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81d74bc0-ffffffff81d74be2: refdst_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void refdst_drop(long unsigned int refdst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81dae720)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81dca9c0)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:tun_dst_unclone
```
```
In net/core/neighbour.c (ffffffff81dd8239)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81df3e9d)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81e29134)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/core/skmsg.c (ffffffff81e483e9)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
```
In net/sched/sch_frag.c (ffffffff81e5400c)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ipv4/route.c (ffffffff81e91f02)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81e971c9)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff81e97f6b)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81e9a4eb)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea154c)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81ec0ce2)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed0e4f)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed8886)
Location: include/net/dst.h:253
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f1ee26)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81f2588c)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f3717c)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41240)
Location: include/net/dst.h:253
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44679)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81f560bc)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81f6c295)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81f890e6)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81f8ecb7)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81f90688)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81f98f5c)
Location: include/net/dst.h:253
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81fa15ae)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81fad900)
Location: include/net/dst.h:253
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81fb3271)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9f51)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb8e5)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fc000b)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/packet/af_packet.c (ffffffff81fc9d6a)
Location: include/net/dst.h:253
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81f41240-ffffffff81f41262: refdst_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void refdst_drop(long unsigned int refdst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1e5f7)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81e3b6cc)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:tun_dst_unclone
```
```
In net/core/neighbour.c (ffffffff81e49556)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81e65a8d)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81e9e77b)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/core/skmsg.c (ffffffff81ea3baf)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
```
In net/sched/sch_frag.c (ffffffff81eaf88c)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ipv4/route.c (ffffffff81ef0688)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef5a00)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff81ef67c6)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81ef8e45)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81effd4e)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81f1f252)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f305ae)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f37996)
Location: include/net/dst.h:267
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f7e926)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81f8541c)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f96ae6)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa0ad0)
Location: include/net/dst.h:267
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3e57)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81fb5a8a)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81fcc39f)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81fe84ac)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81fef5b5)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81ff0ee8)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81ff9931)
Location: include/net/dst.h:267
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff82001831)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8200e0b0)
Location: include/net/dst.h:267
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff82013961)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a684)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff8201bf99)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020f89)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/packet/af_packet.c (ffffffff8202a6a3)
Location: include/net/dst.h:267
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81fa0ad0-ffffffff81fa0af2: refdst_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void refdst_drop(long unsigned int refdst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81edbc71)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81ef9b88)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:tun_dst_unclone
```
```
In net/core/neighbour.c (ffffffff81f08246)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81f24c3d)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81f60eee)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/core/skmsg.c (ffffffff81f664af)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
```
In net/sched/sch_frag.c (ffffffff81f72306)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ipv4/route.c (ffffffff81fb47d8)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb99b0)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff81fba756)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81fbcd65)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc3f12)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81fe390d)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff64b5)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffda70)
Location: include/net/dst.h:260
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff82044fcb)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff8204baf2)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff82063ed3)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8206de30)
Location: include/net/dst.h:260
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff82071184)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff8208315a)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff82099b82)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff820b7002)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff820bd192)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff820beac8)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff820c75a1)
Location: include/net/dst.h:260
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820dcc3d)
Location: include/net/dst.h:260
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff820e2ac2)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e9641)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff820eaf65)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820f00b6)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/packet/af_packet.c (ffffffff820fa18e)
Location: include/net/dst.h:260
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff8206de30-ffffffff8206de52: refdst_drop (STB_LOCAL)
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
In net/core/skbuff.c (ffff800010bb3d84)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffff800010bc8a10)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffff800010be3218)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffff800010c010f0)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffff800010c1eaa0)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (ffff800010c5aef8)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffff800010c5f904)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffff800010c60e5c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffff800010c62344)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffff800010c6974c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffff800010c7f840)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8d9cc)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c933a0)
Location: include/net/dst.h:256
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010cccd7c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffff800010cd2774)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0c84)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffff800010ceae18)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec204)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffff800010cf83ec)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffff800010d11ea0)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffff800010d26550)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffff800010d2acf0)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffff800010d2c284)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffff800010d35620)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffff800010d3bbe8)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffff800010d44234)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffff800010d4a76c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4fb60)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffff800010d50dac)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (ffff800010d5b6fc)
Location: include/net/dst.h:256
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
In net/core/skbuff.c (c0cd2348)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (c0ce4b10)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (c0cfbc40)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (c0d14af4)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (c0d36af4)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (c0d6a3e8)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (c0d6e974)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (c0d7083c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (c0d71b28)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (c0d78988)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (c0d8e8c4)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (c0d9c6ec)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (c0da1b90)
Location: include/net/dst.h:256
Inline: True
```
```
In net/ipv4/ipmr.c (c0dd73f8)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (c0ddc690)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (c0de9fa4)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (c0df3160)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c0df4120)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (c0dffb30)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (c0e12c94)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (c0e29a18)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (c0e2ec10)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c0e30114)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (c0e376f8)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (c0e3e5f8)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (c0e46794)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (c0e4b6b4)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (c0e508b0)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (c0e51910)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (c0e5b824)
Location: include/net/dst.h:256
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
In net/core/skbuff.c (c000000000c8a564)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (c000000000ca518c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (c000000000cc4db0)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (c000000000ce0c88)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (c000000000d10c48)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (c000000000d5cc5c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (c000000000d61ed0)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (c000000000d64290)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (c000000000d655f8)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (c000000000d6e448)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (c000000000d8a058)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9b1c8)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (c000000000da35d4)
Location: include/net/dst.h:256
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000de8a34)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (c000000000df0d90)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (c000000000e02f20)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (c000000000e0ef90)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c000000000e10318)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (c000000000e203c0)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (c000000000e37eac)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (c000000000e561a0)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (c000000000e5bfcc)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c000000000e5daf4)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (c000000000e6769c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (c000000000e6f450)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (c000000000e7a6dc)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (c000000000e8003c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e87350)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (c000000000e88c30)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (c000000000e95cb4)
Location: include/net/dst.h:256
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
In net/core/skbuff.c (ffffffe0007447be)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffe00075520c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffe000769462)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffe00077f33e)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffe0007986b4)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (ffffffe0007c42ae)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c7766)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffe0007c9056)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffe0007c9f04)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf5b4)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffe0007e1a74)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007edf10)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f28f0)
Location: include/net/dst.h:256
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe00081ee10)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffe000823a8c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082f8fc)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffe000838b34)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffe000839a04)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffe0008441fa)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffe000853e96)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffe000866bd2)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffe00086b328)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffe00086c55a)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffe0008729b2)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffffffe00087867e)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffe00088015e)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffe000883640)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000888268)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffe0008890c8)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (ffffffe000892844)
Location: include/net/dst.h:256
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
In net/core/skbuff.c (ffffffff818b9e8c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff818cc407)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff818e2c07)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff818f83e4)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff819180ad)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (ffffffff8194a9dc)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff8194ebb6)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff819506e7)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819517ed)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff8195821e)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff8196ca40)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197a45d)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197f671)
Location: include/net/dst.h:256
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819b0a3e)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff819b61bc)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c3096)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819cbb66)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819ccbe3)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819d7311)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff819e8e07)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff819fffe1)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a044c5)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a05982)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81a0c56b)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a12731)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a19df6)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff81a1e536)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a23494)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a24395)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (ffffffff81a2dbf2)
Location: include/net/dst.h:256
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
In net/core/skbuff.c (ffffffff81873ddc)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81886497)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff8189ca47)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff818b2214)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff818d1e5d)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (ffffffff819044cc)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff819086a6)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff8190a1d7)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8190b2dd)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81911d0e)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff81926530)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81933f1d)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81939131)
Location: include/net/dst.h:256
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196d06e)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81972fac)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fe86)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81988956)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819899d3)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819940d1)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff819a5bc7)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff819bcda1)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff819c1285)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c2742)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff819c932b)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cf4f1)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819d6bb6)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff819db2f6)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819e0254)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff819e1155)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (ffffffff819eade2)
Location: include/net/dst.h:256
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
In net/core/skbuff.c (ffffffff8190ae8c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff8191d407)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81933c37)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff81949414)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff8196923d)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (ffffffff819b51ac)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9386)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff819baeb7)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819bbfbd)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c29ee)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff819d7210)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e4c2d)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e9e41)
Location: include/net/dst.h:256
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1b2de)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81a20a5c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2db16)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a365e6)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a37663)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a41d91)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a53887)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81a6aa61)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a6ef45)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a70402)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81a76feb)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a7d1b1)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a84876)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff81a88fb6)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8df14)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ee15)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a90b74)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
```
```
In net/packet/af_packet.c (ffffffff81a997a2)
Location: include/net/dst.h:256
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
In net/core/skbuff.c (ffffffff8192bf8c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff8193e927)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81954037)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/filter.c (ffffffff8196ad24)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff8198b61d)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/route.c (ffffffff819be8ef)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_fragment.c (ffffffff819c2c76)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (ffffffff819c47c2)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819c58cd)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cc3ee)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_input.c (ffffffff819e0e30)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819edf8d)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f3c71)
Location: include/net/dst.h:256
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a261be)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81a2bf7c)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a392d2)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41f25)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a43008)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a4da21)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a5f877)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81a77071)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a7b575)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a7ca22)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/reassembly.c (ffffffff81a8360b)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a89a01)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a911c6)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff81a95c16)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9ac58)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bbe2)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/packet/af_packet.c (ffffffff81aa45a5)
Location: include/net/dst.h:256
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

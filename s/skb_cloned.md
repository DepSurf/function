# Function: <code>skb_cloned</code>

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
In drivers/net/ppp/ppp_generic.c (ffffffff815f671d)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8170861d)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_pad
  - net/core/skbuff.c:skb_pad
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
```
```
In net/core/dev.c (ffffffff81718d4b)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81732331)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/netfilter/core.c (ffffffff81750ff5)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (ffffffff81758861)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff81759fda)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_forward.c (ffffffff8175a9f8)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8175cba5)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_output.c (ffffffff81775385)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a4ac0)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/ipv4/ipmr.c (ffffffff817a9495)
Location: include/linux/skbuff.h:1220
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817aeeff)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff817b0043)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff817c6cde)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/reassembly.c (ffffffff817ee495)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff817f3283)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff817fa04a)
Location: include/linux/skbuff.h:1220
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
In drivers/net/ppp/ppp_generic.c (ffffffff8165689d)
Location: include/linux/skbuff.h:1311
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8176f19f)
Location: include/linux/skbuff.h:1311
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_pad
  - net/core/skbuff.c:skb_pad
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff817805fb)
Location: include/linux/skbuff.h:1311
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff8179d6cd)
Location: include/linux/skbuff.h:1311
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/netfilter/core.c (ffffffff817bd021)
Location: include/linux/skbuff.h:1311
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (ffffffff817c4b9a)
Location: include/linux/skbuff.h:1311
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff817c63db)
Location: include/linux/skbuff.h:1311
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_forward.c (ffffffff817c6da0)
Location: include/linux/skbuff.h:1311
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817c9991)
Location: include/linux/skbuff.h:1311
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_output.c (ffffffff817e64e7)
Location: include/linux/skbuff.h:1311
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818128d6)
Location: include/linux/skbuff.h:1311
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81816cd5)
Location: include/linux/skbuff.h:1311
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181c035)
Location: include/linux/skbuff.h:1311
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff8181cf73)
Location: include/linux/skbuff.h:1311
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81834512)
Location: include/linux/skbuff.h:1311
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/reassembly.c (ffffffff8185ccd1)
Location: include/linux/skbuff.h:1311
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8186277a)
Location: include/linux/skbuff.h:1311
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff818698b0)
Location: include/linux/skbuff.h:1311
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81870003)
Location: include/linux/skbuff.h:1311
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In drivers/net/ppp/ppp_generic.c (ffffffff8168457d)
Location: include/linux/skbuff.h:1326
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff817a12e9)
Location: include/linux/skbuff.h:1326
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_pad
  - net/core/skbuff.c:skb_pad
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff817adf4b)
Location: include/linux/skbuff.h:1326
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff817cb781)
Location: include/linux/skbuff.h:1326
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/netfilter/core.c (ffffffff817ec961)
Location: include/linux/skbuff.h:1326
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (ffffffff817f46ba)
Location: include/linux/skbuff.h:1326
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff817f5edb)
Location: include/linux/skbuff.h:1326
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_forward.c (ffffffff817f68a1)
Location: include/linux/skbuff.h:1326
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817f991a)
Location: include/linux/skbuff.h:1326
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_output.c (ffffffff81816c27)
Location: include/linux/skbuff.h:1326
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81843dd6)
Location: include/linux/skbuff.h:1326
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff818484a4)
Location: include/linux/skbuff.h:1326
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184d8f5)
Location: include/linux/skbuff.h:1326
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff8184e833)
Location: include/linux/skbuff.h:1326
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81865f72)
Location: include/linux/skbuff.h:1326
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/reassembly.c (ffffffff8188ec0f)
Location: include/linux/skbuff.h:1326
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8189481d)
Location: include/linux/skbuff.h:1326
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff8189c700)
Location: include/linux/skbuff.h:1326
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff818a2f73)
Location: include/linux/skbuff.h:1326
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In drivers/net/ppp/ppp_generic.c (ffffffff81699ac7)
Location: include/linux/skbuff.h:1319
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff817be229)
Location: include/linux/skbuff.h:1319
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff817d0a01)
Location: include/linux/skbuff.h:1319
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff817eaf88)
Location: include/linux/skbuff.h:1319
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gro_cells.c (ffffffff817f98b2)
Location: include/linux/skbuff.h:1319
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/netfilter/core.c (ffffffff8180cd81)
Location: include/linux/skbuff.h:1319
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (ffffffff81814afc)
Location: include/linux/skbuff.h:1319
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff818162ed)
Location: include/linux/skbuff.h:1319
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_forward.c (ffffffff81816ca6)
Location: include/linux/skbuff.h:1319
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81819c72)
Location: include/linux/skbuff.h:1319
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_output.c (ffffffff81836f7c)
Location: include/linux/skbuff.h:1319
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81865662)
Location: include/linux/skbuff.h:1319
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81869bac)
Location: include/linux/skbuff.h:1319
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81871356)
Location: include/linux/skbuff.h:1319
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81872303)
Location: include/linux/skbuff.h:1319
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff8188a71d)
Location: include/linux/skbuff.h:1319
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/reassembly.c (ffffffff818b50cf)
Location: include/linux/skbuff.h:1319
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818bac02)
Location: include/linux/skbuff.h:1319
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff818c2ad2)
Location: include/linux/skbuff.h:1319
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff818c9543)
Location: include/linux/skbuff.h:1319
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In drivers/net/ppp/ppp_generic.c (ffffffff81704267)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81837939)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff8184a5ee)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - net/core/dev.c:do_xdp_generic
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff818665f8)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gro_cells.c (ffffffff818771d2)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/netfilter/core.c (ffffffff8188bf61)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (ffffffff81893cb0)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff818954a0)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_forward.c (ffffffff81895e6c)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff818982ad)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_output.c (ffffffff818b6639)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e57b2)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff818ea263)
Location: include/linux/skbuff.h:1420
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f1d46)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2ce3)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff8190b924)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/reassembly.c (ffffffff81937e45)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193dc12)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff81944ede)
Location: include/linux/skbuff.h:1420
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff8194cbe3)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/strparser/strparser.c (ffffffff8195af40)
Location: include/linux/skbuff.h:1420
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (ffffffff8174295c)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81881e09)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff8188f602)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff818b49d5)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gro_cells.c (ffffffff818c8902)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/netfilter/core.c (ffffffff818dfbf5)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (ffffffff818e7f66)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff818e9619)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_forward.c (ffffffff818ea157)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff818ec2e6)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_output.c (ffffffff8190be79)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193c05b)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81940944)
Location: include/linux/skbuff.h:1431
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8194864f)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff8194960e)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81962cc1)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/reassembly.c (ffffffff81990f4a)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81996b05)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff8199e22c)
Location: include/linux/skbuff.h:1431
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff819a5fca)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/strparser/strparser.c (ffffffff819b45a6)
Location: include/linux/skbuff.h:1431
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (ffffffff817671d9)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff818a2916)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff818aee16)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff818dc2ce)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gro_cells.c (ffffffff818f382f)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/netfilter/core.c (ffffffff8190c77e)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (ffffffff81914e20)
Location: include/linux/skbuff.h:1500
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff8191674b)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_forward.c (ffffffff81917590)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81919480)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_output.c (ffffffff8193a159)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196bd6a)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff819707fe)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8197a32f)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b2d8)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81997cb0)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/reassembly.c (ffffffff819c7681)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cd3ff)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff819d4ce9)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffffffff819dc97a)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/strparser/strparser.c (ffffffff819eb5e9)
Location: include/linux/skbuff.h:1500
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (ffffffff817a48fd)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff818ed566)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff818faa45)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81924a6b)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gro_cells.c (ffffffff819526d6)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffffffff819772f2)
Location: include/linux/skbuff.h:1590
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff819794d7)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8197b7f4)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff8198c6e9)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819915f1)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8199e68c)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf332)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2aba)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff819da04d)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e3e6f)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e480a)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4dc8)
Location: include/linux/skbuff.h:1590
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a03dce)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c4b9)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff81a43b3d)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff81a48678)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81a4b3ba)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/strparser/strparser.c (ffffffff81a5a7e7)
Location: include/linux/skbuff.h:1590
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (ffffffff817c89fd)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8191f666)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff8192cbbd)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81956e9b)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gro_cells.c (ffffffff81988a26)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffffffff819adc82)
Location: include/linux/skbuff.h:1600
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff819afdea)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819b1eb2)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff819c3058)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819c81cb)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819d5187)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/inet_fragment.c (ffffffff81a05ecd)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a0962a)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81a10f3c)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a1ae5f)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b81a)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2ba78)
Location: include/linux/skbuff.h:1600
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a3a9b4)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff81a73139)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff81a7a7bf)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff81a7f239)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81a81f8a)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_local.c (ffffffff81a84bd0)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81a91437)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (ffffffff8189307d)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff819f2bdb)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff81a065dd)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (ffffffff81a2d3ec)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_4_to_6
  - net/core/filter.c:bpf_skb_proto_4_to_6
```
```
In net/core/gro_cells.c (ffffffff81a60696)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffffffff81a97946)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81a99d17)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a9c8cd)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81aae656)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81ab4f9c)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1b46)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/inet_fragment.c (ffffffff81af55dd)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8f4a)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81b02789)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0bec3)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c8ba)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1dcef)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81b30189)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d555)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff81b7608a)
Location: include/linux/skbuff.h:1611
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78c5a)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/netfilter.c (ffffffff81b79eeb)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81b7d0ba)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_local.c (ffffffff81b7fc60)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81b8c8a7)
Location: include/linux/skbuff.h:1611
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (ffffffff818a136d)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff819f2bc8)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff81a07b8d)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (ffffffff81a2ec8c)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_4_to_6
  - net/core/filter.c:bpf_skb_proto_4_to_6
```
```
In net/core/gro_cells.c (ffffffff81a68f1a)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffffffff81aa18a6)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81aa3c7e)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81aa6765)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81ab892e)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81ac00c6)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81acd5a3)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/inet_fragment.c (ffffffff81b0239d)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b068ce)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81b10b50)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b1a253)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1abea)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c5bf)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ec30)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff81b7c005)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff81b84e0a)
Location: include/linux/skbuff.h:1632
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87bda)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/netfilter.c (ffffffff81b88e3b)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81b8c16a)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_local.c (ffffffff81b8ef90)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81b9c4f7)
Location: include/linux/skbuff.h:1632
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (ffffffff818839fd)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff819d8dfb)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff819ea500)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (ffffffff81a162f0)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/selftests.c (ffffffff81a36483)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/gro_cells.c (ffffffff81a4c2da)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffffffff81a8c876)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81a8ecec)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a9184e)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81aa3c22)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81aa70ee)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ab8776)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/inet_fragment.c (ffffffff81aedcad)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af1fe1)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81afe75a)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b07eff)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b088a7)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a21f)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b9c1)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff81b6aae9)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff81b73abe)
Location: include/linux/skbuff.h:1648
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b76897)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/netfilter.c (ffffffff81b77c61)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81b7afea)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_local.c (ffffffff81b7dfd0)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81b8b5b7)
Location: include/linux/skbuff.h:1648
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (ffffffff8191539d)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81a88d9b)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff81aa207e)
Location: include/linux/skbuff.h:1661
Inline: True
```
```
In net/core/filter.c (ffffffff81ac7250)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/selftests.c (ffffffff81aec153)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/gro_cells.c (ffffffff81b0478a)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffffffff81b479a6)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81b49f41)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81b4cc21)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81b5fdd2)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81b636eb)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81b75937)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae05d)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb24f1)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81bbff70)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bcadff)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb7a7)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde83f)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81bf1b1d)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff81c32949)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff81c3e0c9)
Location: include/linux/skbuff.h:1661
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c41317)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/netfilter.c (ffffffff81c42781)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81c45caa)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_local.c (ffffffff81c48e40)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81c57857)
Location: include/linux/skbuff.h:1661
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (ffffffff81a6aa3f)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81bfae9b)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff81c1a11d)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (ffffffff81c429e2)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/selftests.c (ffffffff81c6eb04)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/gro_cells.c (ffffffff81c8a014)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffffffff81cd4c06)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81cd74c7)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81cda379)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_output.c (ffffffff81d04f63)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/inet_fragment.c (ffffffff81d4119d)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45cb9)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81d54944)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d6076b)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d61263)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81d7568f)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a55b)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff81dd0138)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff81ddc73e)
Location: include/linux/skbuff.h:2010
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddfaa3)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/netfilter.c (ffffffff81de1253)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81de4e4a)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_local.c (ffffffff81de854c)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81df8e93)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (ffffffff81bfd7f9)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81da9b68)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff81dcb1ad)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (ffffffff81df79d2)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/selftests.c (ffffffff81e26844)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/gro_cells.c (ffffffff81e44bf4)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffffffff81e94f36)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81e97af9)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81e9ab39)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_output.c (ffffffff81eca020)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/inet_fragment.c (ffffffff81f09f4d)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f080)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81f1eb6a)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f2af2b)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2bb63)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41caf)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81f584eb)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff81fa14c8)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff81fad7da)
Location: include/linux/skbuff.h:1868
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1d93)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/netfilter.c (ffffffff81fb36b3)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81fb75da)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb4f9)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81fcd483)
Location: include/linux/skbuff.h:1868
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (ffffffff81c62f4a)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81e18899)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff81e3bd3d)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (ffffffff81e696c6)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/selftests.c (ffffffff81e9bde4)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/gro_cells.c (ffffffff81e9f9f4)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffffffff81ef3706)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81ef633f)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81ef94dc)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_output.c (ffffffff81f28b70)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69a5d)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6ed7f)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81f7e66a)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f8abfb)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b5a3)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1541)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81fb8101)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff82001dbf)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff8200df8a)
Location: include/linux/skbuff.h:1904
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff820124a1)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/netfilter.c (ffffffff82013ecd)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff82017d2a)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_local.c (ffffffff8201bbb9)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff82048daa)
Location: include/linux/skbuff.h:1904
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (ffffffff81d1996a)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81ed5d39)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_ensure_writable_head_tail
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff81efa27d)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (ffffffff81f28ca6)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/selftests.c (ffffffff81f5e544)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/gro_cells.c (ffffffff81f62264)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffffffff81fb7696)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81fba2d2)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81fbd3f9)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_output.c (ffffffff81fed610)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/inet_fragment.c (ffffffff820300dd)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8203549f)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff82044d15)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8205230b)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff82052caa)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:__xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff8206e861)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff820856f0)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff820d0bbf)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff820dcb17)
Location: include/linux/skbuff.h:1911
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e0eba)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:__xfrm6_udp_encap_rcv
```
```
In net/ipv6/netfilter.c (ffffffff820e3024)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff820e6cfa)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_local.c (ffffffff820eab79)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff8211b12a)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (ffff800010a02e50)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffff800010bba074)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffff800010bcf4d8)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffff800010bf865c)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gro_cells.c (ffff800010c30bb0)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffff800010c5e408)
Location: include/linux/skbuff.h:1600
Inline: True
```
```
In net/ipv4/ip_forward.c (ffff800010c604b0)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffff800010c63bc4)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffff800010c75e28)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffff800010c7bca8)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffff800010c87de4)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/inet_fragment.c (ffff800010cbee68)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc29d4)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffff800010cccc60)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd6ec4)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd7a74)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffff800010cea524)
Location: include/linux/skbuff.h:1600
Inline: True
```
```
In net/ipv6/ip6_output.c (ffff800010cfbb0c)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffff800010d3bb20)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffff800010d44284)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffff800010d4a4d4)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffff800010d4d660)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_local.c (ffff800010d50c8c)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffff800010d5efcc)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (c0addc2c)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (c0cd6928)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (c0ce5898)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (c0d122a8)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gro_cells.c (c0d479bc)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (c0d6d454)
Location: include/linux/skbuff.h:1600
Inline: True
```
```
In net/ipv4/ip_forward.c (c0d6fe88)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c0d72108)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (c0d844d4)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (c0d89c2c)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (c0d9715c)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/inet_fragment.c (c0dca5fc)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (c0dce200)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (c0dd72b0)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (c0de0bd4)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (c0de1584)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (c0df22cc)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/ipv6/ip6_output.c (c0e02a94)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (c0e3e690)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (c0e467f0)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (c0e4baf0)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (c0e4ece8)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_local.c (c0e517dc)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (c0e5ebc8)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (c000000000aa8d10)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (c000000000c929bc)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (c000000000ca6294)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (c000000000cdf578)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gro_cells.c (c000000000d29910)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (c000000000d607f0)
Location: include/linux/skbuff.h:1600
Inline: True
```
```
In net/ipv4/ip_forward.c (c000000000d632d4)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c000000000d65d78)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (c000000000d7d76c)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (c000000000d8491c)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (c000000000d94b2c)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/inet_fragment.c (c000000000dd965c)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dde2ac)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (c000000000de88ac)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (c000000000df6bd8)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (c000000000df79d4)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (c000000000e0e0f4)
Location: include/linux/skbuff.h:1600
Inline: True
```
```
In net/ipv6/ip6_output.c (c000000000e2319c)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (c000000000e6f4e0)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (c000000000e7a730)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (c000000000e8056c)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (c000000000e845fc)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_local.c (c000000000e88aa0)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (c000000000e99a78)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (ffffffe00062d2b2)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffe00074943c)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffe0007559e8)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffe00077a376)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gro_cells.c (ffffffe0007a6ad0)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffffffe0007c689e)
Location: include/linux/skbuff.h:1600
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffe0007c8700)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffe0007ca482)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffe0007d8e46)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffe0007dd946)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffe0007e90c2)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/inet_fragment.c (ffffffe000814c38)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817e34)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffe00081ed80)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffe0008277b0)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffe000828102)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffe000838118)
Location: include/linux/skbuff.h:1600
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffe00084640e)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffe000878582)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffe00088019c)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffe0008839d8)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffe00088682a)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_local.c (ffffffe000888fd8)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffe000894738)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (ffffffff8178d4dd)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff818bf666)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff818ccbbd)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff818f6e6b)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gro_cells.c (ffffffff81928896)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffffffff8194daf2)
Location: include/linux/skbuff.h:1600
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff8194fc5a)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81951d22)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81962ec8)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff8196803b)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81974ff7)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/inet_fragment.c (ffffffff819a5c6d)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a93ca)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff819b08cc)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819ba4ef)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff819baeaa)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb108)
Location: include/linux/skbuff.h:1600
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819da044)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff81a127c9)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff81a19e4f)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff81a1e8c9)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81a2161a)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_local.c (ffffffff81a24260)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81a30ac7)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (ffffffff817762ad)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff818795a6)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff81886c4d)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff818b0c9b)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gro_cells.c (ffffffff818e2646)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffffffff819075e2)
Location: include/linux/skbuff.h:1600
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff8190974a)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8190b812)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff8191c9b8)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81921b2b)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8192eab7)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f72d)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962e8a)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff8196cefc)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819772df)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977c9a)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81987ef8)
Location: include/linux/skbuff.h:1600
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81996e04)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff819cf589)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff819d6c0f)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff819db689)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff819de3da)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_local.c (ffffffff819e1020)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff819edcb7)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (ffffffff817bd87d)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81910666)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff8191dbbd)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81947e9b)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gro_cells.c (ffffffff81979a26)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffffffff819b82c2)
Location: include/linux/skbuff.h:1600
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff819ba42a)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819bc4f2)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff819cd698)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819d280b)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819df7c7)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1050d)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13c6a)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81a1b16c)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a24f6f)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a2592a)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35b88)
Location: include/linux/skbuff.h:1600
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a44ac4)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff81a7d249)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff81a848cf)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff81a89349)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81a8c09a)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ece0)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81a9c677)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/ppp/ppp_generic.c (ffffffff817d80ad)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff819317c6)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff8193f22d)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff819697ab)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gro_cells.c (ffffffff8199bf23)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_input.c (ffffffff819c1b22)
Location: include/linux/skbuff.h:1600
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff819c3d1a)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819c5e02)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff819d7228)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819dc3ab)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819e9477)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1ad5d)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e64a)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81a2604c)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a303df)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30dba)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81a414f8)
Location: include/linux/skbuff.h:1600
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a50784)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff81a89a99)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ip6mr.c (ffffffff81a9121f)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (ffffffff81a95fa9)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81a98f9a)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_local.c (ffffffff81a9ba50)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81aa8857)
Location: include/linux/skbuff.h:1600
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
</details>
</li>
</ul>

## Differences

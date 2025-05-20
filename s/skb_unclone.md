# Function: <code>skb_unclone</code>

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
Location: include/linux/skbuff.h:1226
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/ipv4/ip_fragment.c (ffffffff81759fda)
Location: include/linux/skbuff.h:1226
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_output.c (ffffffff81775378)
Location: include/linux/skbuff.h:1226
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a4ac0)
Location: include/linux/skbuff.h:1226
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/ipv4/xfrm4_input.c (ffffffff817b0043)
Location: include/linux/skbuff.h:1226
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/reassembly.c (ffffffff817ee495)
Location: include/linux/skbuff.h:1226
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
Location: include/linux/skbuff.h:1317
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/filter.c (ffffffff8179d6cd)
Location: include/linux/skbuff.h:1317
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_fragment.c (ffffffff817c63db)
Location: include/linux/skbuff.h:1317
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_output.c (ffffffff817e560c)
Location: include/linux/skbuff.h:1317
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818128d6)
Location: include/linux/skbuff.h:1317
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff8181cf73)
Location: include/linux/skbuff.h:1317
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/reassembly.c (ffffffff8185ccd1)
Location: include/linux/skbuff.h:1317
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
Location: include/linux/skbuff.h:1332
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/filter.c (ffffffff817cc12d)
Location: include/linux/skbuff.h:1332
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_fragment.c (ffffffff817f5edb)
Location: include/linux/skbuff.h:1332
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_output.c (ffffffff81815a99)
Location: include/linux/skbuff.h:1332
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81843dd6)
Location: include/linux/skbuff.h:1332
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff8184e833)
Location: include/linux/skbuff.h:1332
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/reassembly.c (ffffffff8188ec0f)
Location: include/linux/skbuff.h:1332
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
Location: include/linux/skbuff.h:1325
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/filter.c (ffffffff817eb6aa)
Location: include/linux/skbuff.h:1325
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_fragment.c (ffffffff818162ed)
Location: include/linux/skbuff.h:1325
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_output.c (ffffffff81835e3f)
Location: include/linux/skbuff.h:1325
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81865662)
Location: include/linux/skbuff.h:1325
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81872303)
Location: include/linux/skbuff.h:1325
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/reassembly.c (ffffffff818b50cf)
Location: include/linux/skbuff.h:1325
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
Location: include/linux/skbuff.h:1426
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81834138)
Location: include/linux/skbuff.h:1426
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff81867584)
Location: include/linux/skbuff.h:1426
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_fragment.c (ffffffff818954a0)
Location: include/linux/skbuff.h:1426
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_output.c (ffffffff818b5444)
Location: include/linux/skbuff.h:1426
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e57b2)
Location: include/linux/skbuff.h:1426
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2ce3)
Location: include/linux/skbuff.h:1426
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81937e45)
Location: include/linux/skbuff.h:1426
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/strparser/strparser.c (ffffffff8195af40)
Location: include/linux/skbuff.h:1426
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
Location: include/linux/skbuff.h:1437
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8187e8d1)
Location: include/linux/skbuff.h:1437
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff818b6590)
Location: include/linux/skbuff.h:1437
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_fragment.c (ffffffff818e9619)
Location: include/linux/skbuff.h:1437
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_output.c (ffffffff8190ab30)
Location: include/linux/skbuff.h:1437
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193c05b)
Location: include/linux/skbuff.h:1437
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff8194960e)
Location: include/linux/skbuff.h:1437
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81990f4a)
Location: include/linux/skbuff.h:1437
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/strparser/strparser.c (ffffffff819b45a6)
Location: include/linux/skbuff.h:1437
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
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8189f1e1)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff818db634)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_fragment.c (ffffffff8191674b)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_output.c (ffffffff81938dea)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196bd6a)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b2d8)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/reassembly.c (ffffffff819c7681)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/strparser/strparser.c (ffffffff819eb5e9)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
Location: include/linux/skbuff.h:1596
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff818e9a01)
Location: include/linux/skbuff.h:1596
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff8192823e)
Location: include/linux/skbuff.h:1596
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/tcp_output.c (ffffffff8199d029)
Location: include/linux/skbuff.h:1596
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf332)
Location: include/linux/skbuff.h:1596
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2aba)
Location: include/linux/skbuff.h:1596
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e480a)
Location: include/linux/skbuff.h:1596
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4dc8)
Location: include/linux/skbuff.h:1596
Inline: True
```
```
In net/strparser/strparser.c (ffffffff81a5a7e7)
Location: include/linux/skbuff.h:1596
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8191bb6f)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff8195a86e)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/tcp_output.c (ffffffff819d3ae9)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff81a05ecd)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a0962a)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b81a)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2ba78)
Location: include/linux/skbuff.h:1606
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a84bd0)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81a91437)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff819ee541)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff81a2dc50)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_6_to_4
```
```
In net/ipv4/tcp_output.c (ffffffff81ac0669)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff81af55dd)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8f4a)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c8ba)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1dcef)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78c5a)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81b7fc60)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81b8c8a7)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff819f1d89)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff81a2f6e0)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_6_to_4
```
```
In net/ipv4/tcp_output.c (ffffffff81acc0cf)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff81b0239d)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06f3a)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1abea)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c5bf)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87bda)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81b8ef90)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81b9c4f7)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
Location: include/linux/skbuff.h:1654
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff819d7c2d)
Location: include/linux/skbuff.h:1654
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff81a1a6bc)
Location: include/linux/skbuff.h:1654
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/tcp_output.c (ffffffff81ab72e8)
Location: include/linux/skbuff.h:1654
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff81aedcad)
Location: include/linux/skbuff.h:1654
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af2693)
Location: include/linux/skbuff.h:1654
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b088a7)
Location: include/linux/skbuff.h:1654
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a21f)
Location: include/linux/skbuff.h:1654
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b76897)
Location: include/linux/skbuff.h:1654
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81b7dfd0)
Location: include/linux/skbuff.h:1654
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81b8b5b7)
Location: include/linux/skbuff.h:1654
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
Location: include/linux/skbuff.h:1667
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81a87a7d)
Location: include/linux/skbuff.h:1667
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff81acc99c)
Location: include/linux/skbuff.h:1667
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae05d)
Location: include/linux/skbuff.h:1667
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2ba3)
Location: include/linux/skbuff.h:1667
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb7a7)
Location: include/linux/skbuff.h:1667
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde83f)
Location: include/linux/skbuff.h:1667
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c41317)
Location: include/linux/skbuff.h:1667
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81c48e40)
Location: include/linux/skbuff.h:1667
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81c57857)
Location: include/linux/skbuff.h:1667
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
Location: include/linux/skbuff.h:2016
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81bfce61)
Location: include/linux/skbuff.h:2016
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff81c4986a)
Location: include/linux/skbuff.h:2016
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/inet_fragment.c (ffffffff81d4119d)
Location: include/linux/skbuff.h:2016
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d46372)
Location: include/linux/skbuff.h:2016
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d61263)
Location: include/linux/skbuff.h:2016
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81d7568f)
Location: include/linux/skbuff.h:2016
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddfaa3)
Location: include/linux/skbuff.h:2016
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81de854c)
Location: include/linux/skbuff.h:2016
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81df8e93)
Location: include/linux/skbuff.h:2016
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
Location: include/linux/skbuff.h:1874
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81dac975)
Location: include/linux/skbuff.h:1874
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff81dfe871)
Location: include/linux/skbuff.h:1874
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/inet_fragment.c (ffffffff81f09f4d)
Location: include/linux/skbuff.h:1874
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f765)
Location: include/linux/skbuff.h:1874
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2bb63)
Location: include/linux/skbuff.h:1874
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41caf)
Location: include/linux/skbuff.h:1874
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1d93)
Location: include/linux/skbuff.h:1874
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb4f9)
Location: include/linux/skbuff.h:1874
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81fcd483)
Location: include/linux/skbuff.h:1874
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
Location: include/linux/skbuff.h:1910
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81e1c4c2)
Location: include/linux/skbuff.h:1910
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff81e706b7)
Location: include/linux/skbuff.h:1910
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69a5d)
Location: include/linux/skbuff.h:1910
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f455)
Location: include/linux/skbuff.h:1910
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b5a3)
Location: include/linux/skbuff.h:1910
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1541)
Location: include/linux/skbuff.h:1910
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/xfrm6_input.c (ffffffff820124a1)
Location: include/linux/skbuff.h:1910
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff8201bbb9)
Location: include/linux/skbuff.h:1910
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff82048daa)
Location: include/linux/skbuff.h:1910
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
Location: include/linux/skbuff.h:1917
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81ed9bc2)
Location: include/linux/skbuff.h:1917
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff81f2fd47)
Location: include/linux/skbuff.h:1917
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/inet_fragment.c (ffffffff820300dd)
Location: include/linux/skbuff.h:1917
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035b85)
Location: include/linux/skbuff.h:1917
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff82052caa)
Location: include/linux/skbuff.h:1917
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:__xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff8206e861)
Location: include/linux/skbuff.h:1917
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e0eba)
Location: include/linux/skbuff.h:1917
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:__xfrm6_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff820eab79)
Location: include/linux/skbuff.h:1917
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff8211b12a)
Location: include/linux/skbuff.h:1917
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffff800010bb6190)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffff800010bfbf14)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/tcp_output.c (ffff800010c86520)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/inet_fragment.c (ffff800010cbee68)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc29d4)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd7a74)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffff800010cea524)
Location: include/linux/skbuff.h:1606
Inline: True
```
```
In net/ipv6/seg6_local.c (ffff800010d50c8c)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffff800010d5efcc)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (c0cd30c4)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (c0d16f7c)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/tcp_output.c (c0d959c0)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/inet_fragment.c (c0dca5fc)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (c0dce200)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (c0de1584)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (c0df22cc)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/ipv6/seg6_local.c (c0e517dc)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (c0e5ebc8)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (c000000000c8d764)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (c000000000ce7464)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/tcp_output.c (c000000000d92b70)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/inet_fragment.c (c000000000dd965c)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dde2ac)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (c000000000df79d4)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (c000000000e0e0f4)
Location: include/linux/skbuff.h:1606
Inline: True
```
```
In net/ipv6/seg6_local.c (c000000000e88aa0)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (c000000000e99a78)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffe000745fc4)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffe00077e77c)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/tcp_output.c (ffffffe0007e7b4c)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffe000814c38)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817e34)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffe000828102)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffe000838118)
Location: include/linux/skbuff.h:1606
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffe000888fd8)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffe000894738)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff818bbb6f)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff818fa83e)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/tcp_output.c (ffffffff81973959)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff819a5c6d)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a93ca)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff819baeaa)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb108)
Location: include/linux/skbuff.h:1606
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a24260)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81a30ac7)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81875aaf)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff818b466e)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/tcp_output.c (ffffffff8192d429)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f72d)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962e8a)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977c9a)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81987ef8)
Location: include/linux/skbuff.h:1606
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819e1020)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff819edcb7)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8190cb6f)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff8194b86e)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/tcp_output.c (ffffffff819de129)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1050d)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13c6a)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a2592a)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35b88)
Location: include/linux/skbuff.h:1606
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ece0)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81a9c677)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8192dcb2)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff8196d17e)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/tcp_output.c (ffffffff819e7da9)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1ad5d)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e64a)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30dba)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81a414f8)
Location: include/linux/skbuff.h:1606
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a9ba50)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81aa8857)
Location: include/linux/skbuff.h:1606
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
</details>
</li>
</ul>

## Differences

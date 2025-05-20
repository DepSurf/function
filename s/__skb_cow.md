# Function: <code>__skb_cow</code>

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
In drivers/net/ppp/ppp_generic.c (ffffffff815f7fc2)
Location: include/linux/skbuff.h:2546
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81708f10)
Location: include/linux/skbuff.h:2546
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff8171c2f7)
Location: include/linux/skbuff.h:2546
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff81738b3e)
Location: include/linux/skbuff.h:2546
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_input.c (ffffffff8175888b)
Location: include/linux/skbuff.h:2546
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_forward.c (ffffffff8175aa0f)
Location: include/linux/skbuff.h:2546
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff817a94bd)
Location: include/linux/skbuff.h:2546
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817aef23)
Location: include/linux/skbuff.h:2546
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
```
```
In net/ipv6/ip6_output.c (ffffffff817c6cfe)
Location: include/linux/skbuff.h:2546
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff817fa069)
Location: include/linux/skbuff.h:2546
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff8180975d)
Location: include/linux/skbuff.h:2546
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/ppp/ppp_generic.c (ffffffff816581a6)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81770a32)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81784f55)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff8179d88e)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (ffffffff817a4e12)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_input.c (ffffffff817c4bc4)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_forward.c (ffffffff817c6db7)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff81816cfd)
Location: include/linux/skbuff.h:2689
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181c05a)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81833dbe)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff818698cf)
Location: include/linux/skbuff.h:2689
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81870025)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/8021q/vlan_core.c (ffffffff8187b25e)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffff81685f36)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff8179dae6)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff817b2565)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff817cb79b)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (ffffffff817d3882)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_input.c (ffffffff817f46e4)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_forward.c (ffffffff817f68b8)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff818484cc)
Location: include/linux/skbuff.h:2727
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184d91a)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81865835)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff8189c71f)
Location: include/linux/skbuff.h:2727
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff818a2f95)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/8021q/vlan_core.c (ffffffff818afb1e)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffff8169b370)
Location: include/linux/skbuff.h:2776
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff817bb9a9)
Location: include/linux/skbuff.h:2776
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff817cfd80)
Location: include/linux/skbuff.h:2776
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff817eaf95)
Location: include/linux/skbuff.h:2776
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (ffffffff817f2bb3)
Location: include/linux/skbuff.h:2776
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_input.c (ffffffff81814b26)
Location: include/linux/skbuff.h:2776
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_forward.c (ffffffff81816cc9)
Location: include/linux/skbuff.h:2776
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff81869bd1)
Location: include/linux/skbuff.h:2776
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8187137b)
Location: include/linux/skbuff.h:2776
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff8188a044)
Location: include/linux/skbuff.h:2776
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff818c2b06)
Location: include/linux/skbuff.h:2776
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff818c9565)
Location: include/linux/skbuff.h:2776
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818caefc)
Location: include/linux/skbuff.h:2776
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/8021q/vlan_core.c (ffffffff818d62e6)
Location: include/linux/skbuff.h:2776
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffff81705b70)
Location: include/linux/skbuff.h:2873
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81834a59)
Location: include/linux/skbuff.h:2873
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818496d0)
Location: include/linux/skbuff.h:2873
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81866605)
Location: include/linux/skbuff.h:2873
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (ffffffff8186e17d)
Location: include/linux/skbuff.h:2873
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_input.c (ffffffff81893cda)
Location: include/linux/skbuff.h:2873
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_forward.c (ffffffff81895e8f)
Location: include/linux/skbuff.h:2873
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff818ea286)
Location: include/linux/skbuff.h:2873
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f1d6b)
Location: include/linux/skbuff.h:2873
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff8190b234)
Location: include/linux/skbuff.h:2873
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff81944f1f)
Location: include/linux/skbuff.h:2873
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff8194cc05)
Location: include/linux/skbuff.h:2873
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e83c)
Location: include/linux/skbuff.h:2873
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff8195be80)
Location: include/linux/skbuff.h:2873
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffff81745015)
Location: include/linux/skbuff.h:2885
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff8187f8a9)
Location: include/linux/skbuff.h:2885
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818936e0)
Location: include/linux/skbuff.h:2885
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff818b5f82)
Location: include/linux/skbuff.h:2885
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (ffffffff818bf158)
Location: include/linux/skbuff.h:2885
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_input.c (ffffffff818e7f85)
Location: include/linux/skbuff.h:2885
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_forward.c (ffffffff818ea184)
Location: include/linux/skbuff.h:2885
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff81940971)
Location: include/linux/skbuff.h:2885
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8194866a)
Location: include/linux/skbuff.h:2885
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81962660)
Location: include/linux/skbuff.h:2885
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff8199e253)
Location: include/linux/skbuff.h:2885
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff819a5fe5)
Location: include/linux/skbuff.h:2885
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7b2a)
Location: include/linux/skbuff.h:2885
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff819b56b9)
Location: include/linux/skbuff.h:2885
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffff81769102)
Location: include/linux/skbuff.h:2961
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff8189fb05)
Location: include/linux/skbuff.h:2961
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818b40fb)
Location: include/linux/skbuff.h:2961
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff818daff4)
Location: include/linux/skbuff.h:2961
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (ffffffff818e7f84)
Location: include/linux/skbuff.h:2961
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/ipv4/ip_input.c (ffffffff81914e3c)
Location: include/linux/skbuff.h:2961
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff819175ba)
Location: include/linux/skbuff.h:2961
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff81970828)
Location: include/linux/skbuff.h:2961
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8197a347)
Location: include/linux/skbuff.h:2961
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81997671)
Location: include/linux/skbuff.h:2961
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff819d4d0d)
Location: include/linux/skbuff.h:2961
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffffffff819dc992)
Location: include/linux/skbuff.h:2961
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de677)
Location: include/linux/skbuff.h:2961
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff819ec97e)
Location: include/linux/skbuff.h:2961
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffff817a6bda)
Location: include/linux/skbuff.h:3048
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff818ea313)
Location: include/linux/skbuff.h:3048
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff819009d5)
Location: include/linux/skbuff.h:3048
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81927db3)
Location: include/linux/skbuff.h:3048
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (ffffffff819378ee)
Location: include/linux/skbuff.h:3048
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff81943622)
Location: include/linux/skbuff.h:3048
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_input.c (ffffffff81977312)
Location: include/linux/skbuff.h:3048
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff81979506)
Location: include/linux/skbuff.h:3048
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff819da07c)
Location: include/linux/skbuff.h:3048
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e3e87)
Location: include/linux/skbuff.h:3048
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4b42)
Location: include/linux/skbuff.h:3048
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a0366a)
Location: include/linux/skbuff.h:3048
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff81a43b66)
Location: include/linux/skbuff.h:3048
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffffffff81a4b3d2)
Location: include/linux/skbuff.h:3048
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4d1ed)
Location: include/linux/skbuff.h:3048
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff81a5bb3b)
Location: include/linux/skbuff.h:3048
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffff817ca63a)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff8191c49d)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81932d05)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff8195a153)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (ffffffff8196a7ae)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff819785f8)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_input.c (ffffffff819adca2)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff819afe19)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff81a10f6b)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a1ae77)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b7f2)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a3a23a)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff81a7a7e8)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffffffff81a81fa2)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83dbd)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff81a92732)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffff8189568a)
Location: include/linux/skbuff.h:3136
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff819f05b6)
Location: include/linux/skbuff.h:3136
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81a04a29)
Location: include/linux/skbuff.h:3136
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81a3055a)
Location: include/linux/skbuff.h:3136
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_proto_4_to_6
```
```
In net/core/netpoll.c (ffffffff81a3deae)
Location: include/linux/skbuff.h:3136
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff81a4d508)
Location: include/linux/skbuff.h:3136
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_input.c (ffffffff81a9795e)
Location: include/linux/skbuff.h:3136
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81a99d46)
Location: include/linux/skbuff.h:3136
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff81b027b8)
Location: include/linux/skbuff.h:3136
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0bedb)
Location: include/linux/skbuff.h:3136
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d65b)
Location: include/linux/skbuff.h:3136
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f9cc)
Location: include/linux/skbuff.h:3136
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff81b6cb9d)
Location: include/linux/skbuff.h:3136
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b760b7)
Location: include/linux/skbuff.h:3136
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81b7d0d2)
Location: include/linux/skbuff.h:3136
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7eb80)
Location: include/linux/skbuff.h:3136
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff81b8dbdf)
Location: include/linux/skbuff.h:3136
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffff818a3dba)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff819f02fc)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81a057a9)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81a32889)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_proto_4_to_6
```
```
In net/core/netpoll.c (ffffffff81a40bce)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff81a531c8)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81a6f3a0)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_input.c (ffffffff81aa18be)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81aa3caa)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b068ee)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/ipmr.c (ffffffff81b10b7f)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b1a26b)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2be75)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e3fd)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff81b7b62b)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b84e3b)
Location: include/linux/skbuff.h:3162
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81b8c182)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8db92)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff81b9d8ae)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffff81885aca)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff819d4c46)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff819ee139)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81a199ec)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (ffffffff81a2588e)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff81a389f8)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81a57c75)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_input.c (ffffffff81a8c88e)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81a8ed1b)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af2001)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/ipmr.c (ffffffff81afe789)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b07f17)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19aeb)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81b2cbee)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a0ee)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b73aef)
Location: include/linux/skbuff.h:3226
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81b7b002)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7ca60)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff81b8c9d7)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffff8191746c)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81a849d6)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81a9f3d9)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81acbc5c)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (ffffffff81ada5ce)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff81aee8d8)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81b10c15)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_input.c (ffffffff81b479be)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81b49f70)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2511)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/ipmr.c (ffffffff81bbff9f)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bcae17)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdddbb)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81bf2d68)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff81c31f4e)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81c3e0fa)
Location: include/linux/skbuff.h:3263
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81c45cc2)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47b8f)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4c18e)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/8021q/vlan_core.c (ffffffff81c58d97)
Location: include/linux/skbuff.h:3263
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffff81a6b87f)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81bfa9eb)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81c12183)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81c480c4)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (ffffffff81c5bca9)
Location: include/linux/skbuff.h:3632
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81c71830)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81c97daa)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_input.c (ffffffff81cd4c1e)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81cd74db)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45cc4)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/ipmr.c (ffffffff81d54958)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d60783)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81d74f43)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81d8b87f)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff81dcf749)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81ddc744)
Location: include/linux/skbuff.h:3632
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81de4e62)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6fdf)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81dec1b4)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee879)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff81dfa43a)
Location: include/linux/skbuff.h:3632
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffff81bfe77f)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81da987b)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81dc2553)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81dfcb9c)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (ffffffff81e120f9)
Location: include/linux/skbuff.h:3528
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81e29920)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81e53d4a)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_input.c (ffffffff81e94f4e)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81e97b0d)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f08b)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/ipmr.c (ffffffff81f1eb7e)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f2af43)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42180)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/ipv6/ip6_output.c (ffffffff81f598ab)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/exthdrs.c (ffffffff81fa0ace)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81fad7e0)
Location: include/linux/skbuff.h:3528
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81fb75f2)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9e6f)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfe04)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc1e98)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/8021q/vlan_core.c (ffffffff81fceb5b)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffff81c63db4)
Location: include/linux/skbuff.h:3562
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81e1837b)
Location: include/linux/skbuff.h:3562
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81e2eae9)
Location: include/linux/skbuff.h:3562
Inline: True
```
```
In net/core/filter.c (ffffffff81e6dc6c)
Location: include/linux/skbuff.h:3562
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gso.c (ffffffff81e7d7d3)
Location: include/linux/skbuff.h:3562
Inline: True
Inline callers:
  - net/core/gso.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff81e85919)
Location: include/linux/skbuff.h:3562
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81e9ef60)
Location: include/linux/skbuff.h:3562
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81eaf5ca)
Location: include/linux/skbuff.h:3562
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_input.c (ffffffff81ef371e)
Location: include/linux/skbuff.h:3562
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81ef6353)
Location: include/linux/skbuff.h:3562
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6ed89)
Location: include/linux/skbuff.h:3562
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/ipmr.c (ffffffff81f7e67e)
Location: include/linux/skbuff.h:3562
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f8ac13)
Location: include/linux/skbuff.h:3562
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1968)
Location: include/linux/skbuff.h:3562
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/ipv6/ip6_output.c (ffffffff81fb955f)
Location: include/linux/skbuff.h:3562
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff8200df90)
Location: include/linux/skbuff.h:3562
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff82017d42)
Location: include/linux/skbuff.h:3562
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a5a2)
Location: include/linux/skbuff.h:3562
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020ddc)
Location: include/linux/skbuff.h:3562
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff82022e18)
Location: include/linux/skbuff.h:3562
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/8021q/vlan_core.c (ffffffff8204a511)
Location: include/linux/skbuff.h:3562
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffff81d1a7d4)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81ed581b)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81eed469)
Location: include/linux/skbuff.h:3587
Inline: True
```
```
In net/core/filter.c (ffffffff81f2d63c)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/gso.c (ffffffff81f3e750)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
  - net/core/gso.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff81f47849)
Location: include/linux/skbuff.h:3587
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81f616d0)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81f7204a)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_input.c (ffffffff81fb76ae)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81fba2e6)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff820354a9)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/ipmr.c (ffffffff82044d29)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82052323)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff8206ec88)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/ipv6/ip6_output.c (ffffffff82086b03)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff820dcb1d)
Location: include/linux/skbuff.h:3587
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff820e6d12)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e955f)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820eff09)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff820f1f38)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/8021q/vlan_core.c (ffffffff8211c97d)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
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
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e5ff0)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a022ec)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffff800010bb6a9c)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffff800010bd0d10)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffff800010c00498)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (ffff800010c10b54)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffff800010c1f2b0)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_input.c (ffff800010c5e424)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In net/ipv4/ip_forward.c (ffff800010c604d0)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffff800010cccc80)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd6ee0)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffff800010cea274)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In net/ipv6/ip6_output.c (ffff800010cfb1fc)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffff800010d442b0)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffff800010d4d740)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4fb08)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffff800010d604d8)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
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
In drivers/net/ethernet/freescale/fec_main.c (c0ac933c)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (c0adf3f8)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (c0cd38fc)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (c0ceb94c)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (c0d167c4)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (c0d28a90)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (c0d36e54)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_input.c (c0d6d474)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In net/ipv4/ip_forward.c (c0d6fea4)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (c0dd72cc)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (c0de0bf4)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (c0df2644)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/ipv6/ip6_output.c (c0e01d64)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (c0e46814)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (c0e4ed08)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (c0e50860)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (c0e5ff94)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (c000000000aaad18)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (c000000000c8e3a8)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (c000000000caed98)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (c000000000ce6b90)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (c000000000cfd754)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (c000000000d11150)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_input.c (c000000000d60810)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In net/ipv4/ip_forward.c (c000000000d632f0)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (c000000000de88c8)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (c000000000df6bfc)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (c000000000e0dd64)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In net/ipv6/ip6_output.c (c000000000e2277c)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (c000000000e7a758)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (c000000000e84718)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e872e4)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (c000000000e9b49c)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffe00062ed16)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffe000746742)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffe00075b36e)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffe00077e312)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (ffffffe00078d27e)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffe000798a0c)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_input.c (ffffffe0007c68ba)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffe0007c8736)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffe00081edb0)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffe0008277cc)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffe000837e9a)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffe000845d18)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffe0008801ca)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffffffe000886848)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe00088823e)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffe0008958cc)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffff8178f11a)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff818bc49d)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818d2d05)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff818fa123)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (ffffffff8190a77e)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff81918468)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_input.c (ffffffff8194db12)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff8194fc89)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff819b08fb)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819ba507)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff819cae82)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819d98ca)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff81a19e78)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffffffff81a21632)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a2344d)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff81a31dc2)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
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
In drivers/net/vxlan.c (ffffffff8176bd7b)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_build_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81777eea)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff818763dd)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff8188cb95)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff818b3f53)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (ffffffff818c47ce)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff818d2218)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_input.c (ffffffff81907602)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff81909779)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_tunnel.c (ffffffff819677c7)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff8196cf2b)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819772f7)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81987c72)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8199668a)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff819d6c38)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffffffff819de3f2)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819e020d)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff819eefb2)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffff817bf4ba)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff8190d49d)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81923d05)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff8194b153)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (ffffffff8195b7ae)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff819695f8)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_input.c (ffffffff819b82e2)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff819ba459)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff81a1b19b)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a24f87)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35902)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a4434a)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff81a848f8)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffffffff81a8c0b2)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8decd)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff81a9d972)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
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
In drivers/net/ppp/ppp_generic.c (ffffffff817d974a)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff8192e5cd)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81945175)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff8196ca63)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/netpoll.c (ffffffff8197d9ce)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff8198b9d8)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_input.c (ffffffff819c1b42)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff819c3d49)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff81a2607b)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a303f7)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81a4126d)
Location: include/linux/skbuff.h:3113
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a4fff5)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff81a91248)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffffffff81a98fb2)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9ac11)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff81aa9b72)
Location: include/linux/skbuff.h:3113
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
</ul>

## Differences

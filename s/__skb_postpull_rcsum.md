# Function: <code>__skb_postpull_rcsum</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81771dd0)
Location: include/linux/skbuff.h:2851
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff8177fdf7)
Location: include/linux/skbuff.h:2851
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8179d6fc)
Location: include/linux/skbuff.h:2851
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81835925)
Location: include/linux/skbuff.h:2851
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff81855164)
Location: include/linux/skbuff.h:2851
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
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
In net/core/skbuff.c (ffffffff8179eeeb)
Location: include/linux/skbuff.h:2889
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff817ad4c7)
Location: include/linux/skbuff.h:2889
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff817cc15c)
Location: include/linux/skbuff.h:2889
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81867455)
Location: include/linux/skbuff.h:2889
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff81886ed4)
Location: include/linux/skbuff.h:2889
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81894f02)
Location: include/linux/skbuff.h:2889
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a432d)
Location: include/linux/skbuff.h:2889
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/skbuff.c (ffffffff817bc64b)
Location: include/linux/skbuff.h:2955
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff817cc077)
Location: include/linux/skbuff.h:2955
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff817eb083)
Location: include/linux/skbuff.h:2955
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff8188bbcb)
Location: include/linux/skbuff.h:2955
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff818ad37f)
Location: include/linux/skbuff.h:2955
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818bb246)
Location: include/linux/skbuff.h:2955
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca98b)
Location: include/linux/skbuff.h:2955
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/skbuff.c (ffffffff81836d1b)
Location: include/linux/skbuff.h:3054
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff8184572b)
Location: include/linux/skbuff.h:3054
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81866ed3)
Location: include/linux/skbuff.h:3054
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff8190ce98)
Location: include/linux/skbuff.h:3054
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff8192ff8f)
Location: include/linux/skbuff.h:3054
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193e25c)
Location: include/linux/skbuff.h:3054
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e1b4)
Location: include/linux/skbuff.h:3054
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff8194f8f0)
Location: include/linux/skbuff.h:3054
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff81880e59)
Location: include/linux/skbuff.h:3066
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff8188ed20)
Location: include/linux/skbuff.h:3066
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818b5daa)
Location: include/linux/skbuff.h:3066
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff819642ae)
Location: include/linux/skbuff.h:3066
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff81988c21)
Location: include/linux/skbuff.h:3066
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81997189)
Location: include/linux/skbuff.h:3066
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7158)
Location: include/linux/skbuff.h:3066
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff819a88d1)
Location: include/linux/skbuff.h:3066
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff818a1cf9)
Location: include/linux/skbuff.h:3142
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff818afdc0)
Location: include/linux/skbuff.h:3142
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818d724f)
Location: include/linux/skbuff.h:3142
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81999b69)
Location: include/linux/skbuff.h:3142
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff819bf5bb)
Location: include/linux/skbuff.h:3142
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cda77)
Location: include/linux/skbuff.h:3142
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819ddcb2)
Location: include/linux/skbuff.h:3142
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff819df408)
Location: include/linux/skbuff.h:3142
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff818ec96e)
Location: include/linux/skbuff.h:3229
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff818fbc1c)
Location: include/linux/skbuff.h:3229
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81924d5f)
Location: include/linux/skbuff.h:3229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81a05aa5)
Location: include/linux/skbuff.h:3229
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a2e224)
Location: include/linux/skbuff.h:3229
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c09d)
Location: include/linux/skbuff.h:3229
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4c832)
Location: include/linux/skbuff.h:3229
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a4df94)
Location: include/linux/skbuff.h:3229
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff8191eaa4)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff8192e1ec)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8195718f)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c619)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a64d94)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a72d1d)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83402)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a84b6c)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff819f1337)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81a023a9)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a2f7ec)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81b31cb9)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81b5d7b8)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d216)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e218)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81b7fbfc)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff819f12c7)
Location: include/linux/skbuff.h:3344
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81a02ba9)
Location: include/linux/skbuff.h:3344
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a31afc)
Location: include/linux/skbuff.h:3344
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81b408b9)
Location: include/linux/skbuff.h:3344
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81b6bfa8)
Location: include/linux/skbuff.h:3344
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b7bcbf)
Location: include/linux/skbuff.h:3344
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d22a)
Location: include/linux/skbuff.h:3344
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81b8ef2c)
Location: include/linux/skbuff.h:3344
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff819d656e)
Location: include/linux/skbuff.h:3408
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff819e71c0)
Location: include/linux/skbuff.h:3408
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81a18970)
Location: include/linux/skbuff.h:3408
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e151)
Location: include/linux/skbuff.h:3408
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81b5a2c9)
Location: include/linux/skbuff.h:3408
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a786)
Location: include/linux/skbuff.h:3408
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c0df)
Location: include/linux/skbuff.h:3408
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81b7df6c)
Location: include/linux/skbuff.h:3408
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff81a86bbe)
Location: include/linux/skbuff.h:3445
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_pull_rcsum
```
```
In net/core/dev.c (ffffffff81a97b70)
Location: include/linux/skbuff.h:3445
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81ac9e60)
Location: include/linux/skbuff.h:3445
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81bf443e)
Location: include/linux/skbuff.h:3445
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81c21944)
Location: include/linux/skbuff.h:3445
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81c325e6)
Location: include/linux/skbuff.h:3445
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c46fdf)
Location: include/linux/skbuff.h:3445
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81c48ddc)
Location: include/linux/skbuff.h:3445
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4be52)
Location: include/linux/skbuff.h:3445
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c4829b)
Location: include/linux/skbuff.h:3814
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfd22b)
Location: include/linux/skbuff.h:3710
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e731a5)
Location: include/linux/skbuff.h:3744
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f32925)
Location: include/linux/skbuff.h:3772
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
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
In net/core/skbuff.c (ffff800010bb9278)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffff800010bcd650)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffff800010c00910)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffff800010cfd948)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffff800010d2ac68)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffff800010d3b854)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f200)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffff800010d50c1c)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (c0cd5d34)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (c0ce78c0)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (c0d12588)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (c0e05100)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (c0e2ec94)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (c0e3df10)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (c0e4ff58)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (c0e51770)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (c000000000c91814)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_pull_rcsum
```
```
In net/core/dev.c (c000000000ca7410)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (c000000000ce39e4)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (c000000000e25a08)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (c000000000e5bf1c)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (c000000000e6f0cc)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86a5c)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (c000000000e88a24)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffe000748840)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffe000756da2)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffe00077a5e2)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffe000847d18)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffe00086b2b6)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffe00087814c)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000887d18)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffe000888f7a)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff818beaa4)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff818ce1ec)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818f715f)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff819dbca9)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a04424)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a123ad)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a22a92)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a241fc)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In drivers/net/vxlan.c (ffffffff81772a70)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/core/skbuff.c (ffffffff818789e4)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff8188830c)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818b0f8f)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967ec3)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81998a69)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff819c11e4)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cf16d)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819df852)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff819e0fbc)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff8190faa4)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff8191f1ec)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8194818f)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81a46729)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a6eea4)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a7ce2d)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d512)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ec7c)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff81930bd4)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81940f4c)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81969a9f)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81a52459)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a7b4d4)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a8967d)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a202)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a9b9ec)
Location: include/linux/skbuff.h:3294
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
</details>
</li>
</ul>

## Differences

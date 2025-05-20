# Function: <code>skb_cow</code>

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
In net/core/skbuff.c (ffffffff8170a0d6)
Location: include/linux/skbuff.h:2572
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff81758861)
Location: include/linux/skbuff.h:2572
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_forward.c (ffffffff8175a9f8)
Location: include/linux/skbuff.h:2572
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff817a9495)
Location: include/linux/skbuff.h:2572
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817aeeff)
Location: include/linux/skbuff.h:2572
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
```
```
In net/ipv6/ip6_output.c (ffffffff817c6cde)
Location: include/linux/skbuff.h:2572
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff817fa04a)
Location: include/linux/skbuff.h:2572
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
In net/core/skbuff.c (ffffffff81771893)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/filter.c (ffffffff8179d881)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffff817c4b9a)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_forward.c (ffffffff817c6da0)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff81816cd5)
Location: include/linux/skbuff.h:2715
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181c035)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81833d9c)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff818698b0)
Location: include/linux/skbuff.h:2715
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81870003)
Location: include/linux/skbuff.h:2715
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
In net/core/skbuff.c (ffffffff8179e9c3)
Location: include/linux/skbuff.h:2753
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/filter.c (ffffffff817cb781)
Location: include/linux/skbuff.h:2753
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffff817f46ba)
Location: include/linux/skbuff.h:2753
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_forward.c (ffffffff817f68a1)
Location: include/linux/skbuff.h:2753
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff818484a4)
Location: include/linux/skbuff.h:2753
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184d8f5)
Location: include/linux/skbuff.h:2753
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81865813)
Location: include/linux/skbuff.h:2753
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff8189c700)
Location: include/linux/skbuff.h:2753
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff818a2f73)
Location: include/linux/skbuff.h:2753
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
In net/core/skbuff.c (ffffffff817bd9ba)
Location: include/linux/skbuff.h:2802
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/filter.c (ffffffff817eaf88)
Location: include/linux/skbuff.h:2802
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffff81814afc)
Location: include/linux/skbuff.h:2802
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_forward.c (ffffffff81816ca6)
Location: include/linux/skbuff.h:2802
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff81869bac)
Location: include/linux/skbuff.h:2802
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81871356)
Location: include/linux/skbuff.h:2802
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff8188a037)
Location: include/linux/skbuff.h:2802
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff818c2ad2)
Location: include/linux/skbuff.h:2802
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff818c9543)
Location: include/linux/skbuff.h:2802
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
In net/core/skbuff.c (ffffffff8183700a)
Location: include/linux/skbuff.h:2899
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/filter.c (ffffffff818665f8)
Location: include/linux/skbuff.h:2899
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffff81893cb0)
Location: include/linux/skbuff.h:2899
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_forward.c (ffffffff81895e6c)
Location: include/linux/skbuff.h:2899
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff818ea263)
Location: include/linux/skbuff.h:2899
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f1d46)
Location: include/linux/skbuff.h:2899
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff8190b227)
Location: include/linux/skbuff.h:2899
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff81944ede)
Location: include/linux/skbuff.h:2899
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff8194cbe3)
Location: include/linux/skbuff.h:2899
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (ffffffff818814c0)
Location: include/linux/skbuff.h:2911
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/filter.c (ffffffff818b49d5)
Location: include/linux/skbuff.h:2911
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffff818e7f66)
Location: include/linux/skbuff.h:2911
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_forward.c (ffffffff818ea157)
Location: include/linux/skbuff.h:2911
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff81940944)
Location: include/linux/skbuff.h:2911
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8194864f)
Location: include/linux/skbuff.h:2911
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff8196263b)
Location: include/linux/skbuff.h:2911
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff8199e22c)
Location: include/linux/skbuff.h:2911
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff819a5fca)
Location: include/linux/skbuff.h:2911
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (ffffffff818a1fee)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/filter.c (ffffffff818dc2ce)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffff81914e20)
Location: include/linux/skbuff.h:2987
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff81917590)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff819707fe)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8197a32f)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff8199764f)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff819d4ce9)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffffffff819dc97a)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (ffffffff818ecc68)
Location: include/linux/skbuff.h:3074
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/filter.c (ffffffff81929265)
Location: include/linux/skbuff.h:3074
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffff819772f2)
Location: include/linux/skbuff.h:3074
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff819794d7)
Location: include/linux/skbuff.h:3074
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff819da04d)
Location: include/linux/skbuff.h:3074
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e3e6f)
Location: include/linux/skbuff.h:3074
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81a03643)
Location: include/linux/skbuff.h:3074
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff81a43b3d)
Location: include/linux/skbuff.h:3074
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffffffff81a4b3ba)
Location: include/linux/skbuff.h:3074
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (ffffffff8191ed88)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/filter.c (ffffffff8195b945)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffff819adc82)
Location: include/linux/skbuff.h:3139
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff819afdea)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff81a10f3c)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a1ae5f)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81a3a213)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff81a7a7bf)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffffffff81a81f8a)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (ffffffff819f07d2)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/filter.c (ffffffff81a2ec9b)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_proto_4_to_6
```
```
In net/ipv4/ip_input.c (ffffffff81a97946)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81a99d17)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff81b02789)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0bec3)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f9a5)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff81b7608a)
Location: include/linux/skbuff.h:3162
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81b7d0ba)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (ffffffff819eff92)
Location: include/linux/skbuff.h:3188
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/filter.c (ffffffff81a30241)
Location: include/linux/skbuff.h:3188
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_proto_4_to_6
```
```
In net/ipv4/ip_input.c (ffffffff81aa18a6)
Location: include/linux/skbuff.h:3188
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81aa3c7e)
Location: include/linux/skbuff.h:3188
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b068ce)
Location: include/linux/skbuff.h:3188
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/ipmr.c (ffffffff81b10b50)
Location: include/linux/skbuff.h:3188
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b1a253)
Location: include/linux/skbuff.h:3188
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e3e9)
Location: include/linux/skbuff.h:3188
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff81b84e0a)
Location: include/linux/skbuff.h:3188
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81b8c16a)
Location: include/linux/skbuff.h:3188
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (ffffffff819d77c2)
Location: include/linux/skbuff.h:3252
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/filter.c (ffffffff81a15c76)
Location: include/linux/skbuff.h:3252
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffff81a8c876)
Location: include/linux/skbuff.h:3252
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81a8ecec)
Location: include/linux/skbuff.h:3252
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af1fe1)
Location: include/linux/skbuff.h:3252
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/ipmr.c (ffffffff81afe75a)
Location: include/linux/skbuff.h:3252
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b07eff)
Location: include/linux/skbuff.h:3252
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81b2cbd7)
Location: include/linux/skbuff.h:3252
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff81b73abe)
Location: include/linux/skbuff.h:3252
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81b7afea)
Location: include/linux/skbuff.h:3252
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (ffffffff81a86002)
Location: include/linux/skbuff.h:3289
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/filter.c (ffffffff81ac6ea6)
Location: include/linux/skbuff.h:3289
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffff81b479a6)
Location: include/linux/skbuff.h:3289
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81b49f41)
Location: include/linux/skbuff.h:3289
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb24f1)
Location: include/linux/skbuff.h:3289
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/ipmr.c (ffffffff81bbff70)
Location: include/linux/skbuff.h:3289
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bcadff)
Location: include/linux/skbuff.h:3289
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81bf2d51)
Location: include/linux/skbuff.h:3289
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff81c3e0c9)
Location: include/linux/skbuff.h:3289
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81c45caa)
Location: include/linux/skbuff.h:3289
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (ffffffff81bf9001)
Location: include/linux/skbuff.h:3658
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/filter.c (ffffffff81c43ab6)
Location: include/linux/skbuff.h:3658
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffff81cd4c06)
Location: include/linux/skbuff.h:3658
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81cd74c7)
Location: include/linux/skbuff.h:3658
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45cb9)
Location: include/linux/skbuff.h:3658
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/ipmr.c (ffffffff81d54944)
Location: include/linux/skbuff.h:3658
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d6076b)
Location: include/linux/skbuff.h:3658
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81d8b86b)
Location: include/linux/skbuff.h:3658
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff81ddc73e)
Location: include/linux/skbuff.h:3658
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81de4e4a)
Location: include/linux/skbuff.h:3658
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (ffffffff81daa5e1)
Location: include/linux/skbuff.h:3554
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/filter.c (ffffffff81df8066)
Location: include/linux/skbuff.h:3554
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffff81e94f36)
Location: include/linux/skbuff.h:3554
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81e97af9)
Location: include/linux/skbuff.h:3554
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f080)
Location: include/linux/skbuff.h:3554
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/ipmr.c (ffffffff81f1eb6a)
Location: include/linux/skbuff.h:3554
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f2af2b)
Location: include/linux/skbuff.h:3554
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81f59897)
Location: include/linux/skbuff.h:3554
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff81fad7da)
Location: include/linux/skbuff.h:3554
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81fb75da)
Location: include/linux/skbuff.h:3554
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (ffffffff81e1b7a1)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/filter.c (ffffffff81e6a676)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffff81ef3706)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81ef633f)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6ed7f)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/ipmr.c (ffffffff81f7e66a)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f8abfb)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81fb954b)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff8200df8a)
Location: include/linux/skbuff.h:3588
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff82017d2a)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (ffffffff81ed8d61)
Location: include/linux/skbuff.h:3613
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/filter.c (ffffffff81f29606)
Location: include/linux/skbuff.h:3613
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffff81fb7696)
Location: include/linux/skbuff.h:3613
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81fba2d2)
Location: include/linux/skbuff.h:3613
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8203549f)
Location: include/linux/skbuff.h:3613
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/ipmr.c (ffffffff82044d15)
Location: include/linux/skbuff.h:3613
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8205230b)
Location: include/linux/skbuff.h:3613
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff82086aef)
Location: include/linux/skbuff.h:3613
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff820dcb17)
Location: include/linux/skbuff.h:3613
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff820e6cfa)
Location: include/linux/skbuff.h:3613
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (ffff800010bb9598)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/filter.c (ffff800010bfcc70)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffff800010c5e408)
Location: include/linux/skbuff.h:3139
Inline: True
```
```
In net/ipv4/ip_forward.c (ffff800010c604b0)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffff800010cccc60)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd6ec4)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffff800010cfb1dc)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffff800010d44284)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffff800010d4d660)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (c0cd6028)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/filter.c (c0d180a4)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (c0d6d454)
Location: include/linux/skbuff.h:3139
Inline: True
```
```
In net/ipv4/ip_forward.c (c0d6fe88)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (c0dd72b0)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (c0de0bd4)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (c0e01d5c)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (c0e467f0)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (c0e4ece8)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (c000000000c91b48)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/filter.c (c000000000ce51d0)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (c000000000d607f0)
Location: include/linux/skbuff.h:3139
Inline: True
```
```
In net/ipv4/ip_forward.c (c000000000d632d4)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (c000000000de88ac)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (c000000000df6bd8)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (c000000000e2275c)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (c000000000e7a730)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (c000000000e845fc)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (ffffffe000748b04)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/filter.c (ffffffe00077f0ea)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffe0007c689e)
Location: include/linux/skbuff.h:3139
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffe0007c8700)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffe00081ed80)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffe0008277b0)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffe000845cf4)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffe00088019c)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffffffe00088682a)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (ffffffff818bed88)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/filter.c (ffffffff818fb915)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffff8194daf2)
Location: include/linux/skbuff.h:3139
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff8194fc5a)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff819b08cc)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819ba4ef)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff819d98a3)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff81a19e4f)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffffffff81a2161a)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (ffffffff81878cc8)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/filter.c (ffffffff818b5745)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffff819075e2)
Location: include/linux/skbuff.h:3139
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff8190974a)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff8196cefc)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819772df)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81996663)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff819d6c0f)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffffffff819de3da)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (ffffffff8190fd88)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/filter.c (ffffffff8194c945)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffff819b82c2)
Location: include/linux/skbuff.h:3139
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff819ba42a)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff81a1b16c)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a24f6f)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81a44323)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff81a848cf)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffffffff81a8c09a)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
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
In net/core/skbuff.c (ffffffff81930eb8)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/filter.c (ffffffff8196e305)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/ip_input.c (ffffffff819c1b22)
Location: include/linux/skbuff.h:3139
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff819c3d1a)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ipmr.c (ffffffff81a2604c)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a303df)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv6/ip6_output.c (ffffffff81a4ffce)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6mr.c (ffffffff81a9121f)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/calipso.c (ffffffff81a98f9a)
Location: include/linux/skbuff.h:3139
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
</details>
</li>
</ul>

## Differences

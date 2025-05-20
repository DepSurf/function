# Function: <code>skb_postpush_rcsum</code>

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
In net/core/skbuff.c (ffffffff81770ae1)
Location: include/linux/skbuff.h:2896
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff8179dbbc)
Location: include/linux/skbuff.h:2896
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/ipv6/reassembly.c (ffffffff8185d19e)
Location: include/linux/skbuff.h:2896
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
In net/core/skbuff.c (ffffffff8179db84)
Location: include/linux/skbuff.h:2934
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff817cc61c)
Location: include/linux/skbuff.h:2934
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv6/reassembly.c (ffffffff8188f107)
Location: include/linux/skbuff.h:2934
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a42ab)
Location: include/linux/skbuff.h:2934
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/skbuff.c (ffffffff817bba3f)
Location: include/linux/skbuff.h:3000
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff817eb93c)
Location: include/linux/skbuff.h:3000
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv6/reassembly.c (ffffffff818b5613)
Location: include/linux/skbuff.h:3000
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca8f2)
Location: include/linux/skbuff.h:3000
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/skbuff.c (ffffffff81834aef)
Location: include/linux/skbuff.h:3099
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff8186678c)
Location: include/linux/skbuff.h:3099
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv6/reassembly.c (ffffffff81938389)
Location: include/linux/skbuff.h:3099
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81948ddd)
Location: include/linux/skbuff.h:3099
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e2cb)
Location: include/linux/skbuff.h:3099
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/skbuff.c (ffffffff8187f936)
Location: include/linux/skbuff.h:3111
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff818b546a)
Location: include/linux/skbuff.h:3111
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv6/reassembly.c (ffffffff81991395)
Location: include/linux/skbuff.h:3111
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff819a1ec0)
Location: include/linux/skbuff.h:3111
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7261)
Location: include/linux/skbuff.h:3111
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/skbuff.c (ffffffff8189fb8e)
Location: include/linux/skbuff.h:3187
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff818dbac4)
Location: include/linux/skbuff.h:3187
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv6/reassembly.c (ffffffff819c7ad6)
Location: include/linux/skbuff.h:3187
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff819d8b15)
Location: include/linux/skbuff.h:3187
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dddb8)
Location: include/linux/skbuff.h:3187
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/skbuff.c (ffffffff818ea3ab)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff81929134)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/lwt_bpf.c (ffffffff81943674)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv6/reassembly.c (ffffffff81a35d50)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a47370)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4c934)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/skbuff.c (ffffffff8191c532)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff8195b814)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/lwt_bpf.c (ffffffff81978658)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv6/reassembly.c (ffffffff81a6c870)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a7df20)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83504)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/skbuff.c (ffffffff819f0678)
Location: include/linux/skbuff.h:3363
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff81a2ea14)
Location: include/linux/skbuff.h:3363
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/lwt_bpf.c (ffffffff81a4d559)
Location: include/linux/skbuff.h:3363
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv6/reassembly.c (ffffffff81b65a70)
Location: include/linux/skbuff.h:3363
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffff81b6ce4b)
Location: include/linux/skbuff.h:3363
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78a6e)
Location: include/linux/skbuff.h:3363
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e337)
Location: include/linux/skbuff.h:3363
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/skbuff.c (ffffffff819f03ca)
Location: include/linux/skbuff.h:3389
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff81a30684)
Location: include/linux/skbuff.h:3389
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/lwt_bpf.c (ffffffff81a5321b)
Location: include/linux/skbuff.h:3389
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_frag.c (ffffffff81a6f470)
Location: include/linux/skbuff.h:3389
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv6/reassembly.c (ffffffff81b741d0)
Location: include/linux/skbuff.h:3389
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffff81b7b8d8)
Location: include/linux/skbuff.h:3389
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b879de)
Location: include/linux/skbuff.h:3389
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d349)
Location: include/linux/skbuff.h:3389
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/skbuff.c (ffffffff819d4d0b)
Location: include/linux/skbuff.h:3453
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff81a17724)
Location: include/linux/skbuff.h:3453
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/lwt_bpf.c (ffffffff81a38a49)
Location: include/linux/skbuff.h:3453
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_frag.c (ffffffff81a57d52)
Location: include/linux/skbuff.h:3453
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv6/reassembly.c (ffffffff81b62c30)
Location: include/linux/skbuff.h:3453
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a399)
Location: include/linux/skbuff.h:3453
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b7668e)
Location: include/linux/skbuff.h:3453
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c1fe)
Location: include/linux/skbuff.h:3453
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/skbuff.c (ffffffff81a84a9b)
Location: include/linux/skbuff.h:3490
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff81ac8cb4)
Location: include/linux/skbuff.h:3490
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/lwt_bpf.c (ffffffff81aee929)
Location: include/linux/skbuff.h:3490
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_frag.c (ffffffff81b10d19)
Location: include/linux/skbuff.h:3490
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv6/reassembly.c (ffffffff81c2a6cb)
Location: include/linux/skbuff.h:3490
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81c321f9)
Location: include/linux/skbuff.h:3490
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c4111e)
Location: include/linux/skbuff.h:3490
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c470fe)
Location: include/linux/skbuff.h:3490
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4bf1b)
Location: include/linux/skbuff.h:3490
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
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
In net/core/skbuff.c (ffffffff81bfaaa3)
Location: include/linux/skbuff.h:3864
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff81c45b07)
Location: include/linux/skbuff.h:3864
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/lwt_bpf.c (ffffffff81c71b29)
Location: include/linux/skbuff.h:3864
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_frag.c (ffffffff81c97ebe)
Location: include/linux/skbuff.h:3864
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv6/reassembly.c (ffffffff81dc7b77)
Location: include/linux/skbuff.h:3864
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81dcf9f8)
Location: include/linux/skbuff.h:3864
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddf8a7)
Location: include/linux/skbuff.h:3864
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6440)
Location: include/linux/skbuff.h:3864
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81debf69)
Location: include/linux/skbuff.h:3864
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
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
In net/core/skbuff.c (ffffffff81da9931)
Location: include/linux/skbuff.h:3760
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff81df9d67)
Location: include/linux/skbuff.h:3760
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/lwt_bpf.c (ffffffff81e29c19)
Location: include/linux/skbuff.h:3760
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_frag.c (ffffffff81e53e39)
Location: include/linux/skbuff.h:3760
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv6/reassembly.c (ffffffff81f988e7)
Location: include/linux/skbuff.h:3760
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81fa0d7b)
Location: include/linux/skbuff.h:3760
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1b77)
Location: include/linux/skbuff.h:3760
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9140)
Location: include/linux/skbuff.h:3760
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfbc9)
Location: include/linux/skbuff.h:3760
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
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
In net/core/skbuff.c (ffffffff81e18431)
Location: include/linux/skbuff.h:3794
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff81e6bb57)
Location: include/linux/skbuff.h:3794
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/lwt_bpf.c (ffffffff81e9f238)
Location: include/linux/skbuff.h:3794
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_frag.c (ffffffff81eaf6b3)
Location: include/linux/skbuff.h:3794
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv6/reassembly.c (ffffffff81ff92c7)
Location: include/linux/skbuff.h:3794
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff82001722)
Location: include/linux/skbuff.h:3794
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff82012261)
Location: include/linux/skbuff.h:3794
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820198a0)
Location: include/linux/skbuff.h:3794
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8201d28a)
Location: include/linux/skbuff.h:3794
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020b59)
Location: include/linux/skbuff.h:3794
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
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
In net/core/skbuff.c (ffffffff81ed58d1)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff81f2ac37)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/lwt_bpf.c (ffffffff81f619a5)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_frag.c (ffffffff81f72133)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv6/reassembly.c (ffffffff820c6f47)
Location: include/linux/skbuff.h:3822
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff820d0562)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e13d1)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8870)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff820ec26a)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820efc89)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
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
In net/core/skbuff.c (ffff800010bb6b40)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffff800010bfca08)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/lwt_bpf.c (ffff800010c1f2f4)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv6/reassembly.c (ffff800010d35270)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/xfrm6_input.c (ffff800010d492e8)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f2c4)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/skbuff.c (c0cd397c)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (c0d181f0)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/lwt_bpf.c (c0d36e9c)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv6/reassembly.c (c0e37204)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/xfrm6_input.c (c0e4a6ac)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (c0e5002c)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/skbuff.c (c000000000c8e468)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (c000000000ce7f60)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/lwt_bpf.c (c000000000d11194)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv6/reassembly.c (c000000000e6702c)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e814)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86b4c)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/skbuff.c (ffffffe0007467d6)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffe00077f81a)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/lwt_bpf.c (ffffffe000798a62)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv6/reassembly.c (ffffffe000872632)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/xfrm6_input.c (ffffffe0008827ea)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000887dca)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/skbuff.c (ffffffff818bc532)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff818fb7e4)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/lwt_bpf.c (ffffffff819184c8)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv6/reassembly.c (ffffffff81a0bf00)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a1d5b0)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a22b94)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/skbuff.c (ffffffff81876472)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff818b5614)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/lwt_bpf.c (ffffffff818d2278)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv6/reassembly.c (ffffffff819c8cc0)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/xfrm6_input.c (ffffffff819da370)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819df954)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/skbuff.c (ffffffff8190d532)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff8194c814)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/lwt_bpf.c (ffffffff81969658)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv6/reassembly.c (ffffffff81a76980)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a88030)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d614)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/skbuff.c (ffffffff8192e662)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/filter.c (ffffffff8196e1d4)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/lwt_bpf.c (ffffffff8198ba38)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv6/reassembly.c (ffffffff81a830b0)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a94c50)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a304)
Location: include/linux/skbuff.h:3339
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
</ul>

## Differences

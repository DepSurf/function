# Function: <code>__pskb_pull</code>

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
In net/core/skbuff.c (ffffffff8170926c)
Location: include/linux/skbuff.h:1837
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/ipv4/ip_fragment.c (ffffffff817599e7)
Location: include/linux/skbuff.h:1837
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/icmp.c (ffffffff8178f279)
Location: include/linux/skbuff.h:1837
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff817c86c8)
Location: include/linux/skbuff.h:1837
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/ndisc.c (ffffffff817e14e5)
Location: include/linux/skbuff.h:1837
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/icmp.c (ffffffff817e87ac)
Location: include/linux/skbuff.h:1837
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff817edf1f)
Location: include/linux/skbuff.h:1837
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81800e68)
Location: include/linux/skbuff.h:1837
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (ffffffff81771064)
Location: include/linux/skbuff.h:1938
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/sock_reuseport.c (ffffffff817a0067)
Location: include/linux/skbuff.h:1938
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff817c5dc6)
Location: include/linux/skbuff.h:1938
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/icmp.c (ffffffff817fc8e1)
Location: include/linux/skbuff.h:1938
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81835817)
Location: include/linux/skbuff.h:1938
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/ndisc.c (ffffffff8184d383)
Location: include/linux/skbuff.h:1938
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81856f64)
Location: include/linux/skbuff.h:1938
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff8185c766)
Location: include/linux/skbuff.h:1938
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81872636)
Location: include/linux/skbuff.h:1938
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (ffffffff8179e184)
Location: include/linux/skbuff.h:1953
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/sock_reuseport.c (ffffffff817cea37)
Location: include/linux/skbuff.h:1953
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff817f58c6)
Location: include/linux/skbuff.h:1953
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/icmp.c (ffffffff8182d844)
Location: include/linux/skbuff.h:1953
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81867347)
Location: include/linux/skbuff.h:1953
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/ndisc.c (ffffffff8187f23c)
Location: include/linux/skbuff.h:1953
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81888d64)
Location: include/linux/skbuff.h:1953
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff8188e676)
Location: include/linux/skbuff.h:1953
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81894f2f)
Location: include/linux/skbuff.h:1953
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6c26)
Location: include/linux/skbuff.h:1953
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (ffffffff817bbfc0)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/sock_reuseport.c (ffffffff817eded3)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff81815cd2)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/icmp.c (ffffffff8184ec59)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff8188bac7)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/ndisc.c (ffffffff818a52dc)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff818af3e8)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff818b4cbd)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818bb277)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd656)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (ffffffff818361c1)
Location: include/linux/skbuff.h:2079
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/sock_reuseport.c (ffffffff8186a117)
Location: include/linux/skbuff.h:2079
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff81894ec3)
Location: include/linux/skbuff.h:2079
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/icmp.c (ffffffff818ce9d9)
Location: include/linux/skbuff.h:2079
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff8190cda7)
Location: include/linux/skbuff.h:2079
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/ndisc.c (ffffffff81927ccc)
Location: include/linux/skbuff.h:2079
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff819320f8)
Location: include/linux/skbuff.h:2079
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81937a2d)
Location: include/linux/skbuff.h:2079
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193e28d)
Location: include/linux/skbuff.h:2079
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff8194f8c7)
Location: include/linux/skbuff.h:2079
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81952448)
Location: include/linux/skbuff.h:2079
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (ffffffff8195b289)
Location: include/linux/skbuff.h:2079
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff81880222)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/sock_reuseport.c (ffffffff818b9df7)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff818e8f5c)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/icmp.c (ffffffff81924d4e)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81964197)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/ndisc.c (ffffffff81980074)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff8198ac46)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff819908a2)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819971ba)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff819a8897)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff819ab9bf)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (ffffffff819b49ab)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff818a10eb)
Location: include/linux/skbuff.h:2168
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff818d720b)
Location: include/linux/skbuff.h:2168
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff818e0b69)
Location: include/linux/skbuff.h:2168
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff8191612d)
Location: include/linux/skbuff.h:2168
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/icmp.c (ffffffff81953b5a)
Location: include/linux/skbuff.h:2168
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81999a6c)
Location: include/linux/skbuff.h:2168
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff819b665d)
Location: include/linux/skbuff.h:2168
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c1510)
Location: include/linux/skbuff.h:2168
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff819c6fec)
Location: include/linux/skbuff.h:2168
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cdaa5)
Location: include/linux/skbuff.h:2168
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff819df3d4)
Location: include/linux/skbuff.h:2168
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff819e254a)
Location: include/linux/skbuff.h:2168
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (ffffffff819eb9b7)
Location: include/linux/skbuff.h:2168
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff818ebd2e)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81924d1b)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff8192f20a)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff8197828e)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff819b8445)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (ffffffff819f83be)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a0599c)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81a250f0)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a302fa)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81a362a2)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c0c5)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81a4df64)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81a51210)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (ffffffff81a5ab4c)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff8191de65)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff8195714b)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff8196147a)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff819aebfe)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff819ef145)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f01e)
Location: include/linux/skbuff.h:2270
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c51b)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81a5bb70)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a66e4a)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81a6cdc2)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a72d45)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81a84b38)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87e30)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (ffffffff81a917a0)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff819f0beb)
Location: include/linux/skbuff.h:2293
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81a2f7a9)
Location: include/linux/skbuff.h:2293
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff81a34af5)
Location: include/linux/skbuff.h:2293
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/ipv4/ip_fragment.c (ffffffff81a9901e)
Location: include/linux/skbuff.h:2293
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff81add097)
Location: include/linux/skbuff.h:2293
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (ffffffff81b21bea)
Location: include/linux/skbuff.h:2293
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff81b228b9)
Location: include/linux/skbuff.h:2293
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81b31bbb)
Location: include/linux/skbuff.h:2293
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81b548b0)
Location: include/linux/skbuff.h:2293
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5f712)
Location: include/linux/skbuff.h:2293
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81b65d39)
Location: include/linux/skbuff.h:2293
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d23d)
Location: include/linux/skbuff.h:2293
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81b7fbc8)
Location: include/linux/skbuff.h:2293
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81b832e9)
Location: include/linux/skbuff.h:2293
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (ffffffff81b8cbd0)
Location: include/linux/skbuff.h:2293
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff819f0a58)
Location: include/linux/skbuff.h:2314
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81a31ab9)
Location: include/linux/skbuff.h:2314
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff81a36e35)
Location: include/linux/skbuff.h:2314
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa2f8e)
Location: include/linux/skbuff.h:2314
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff81ae9de7)
Location: include/linux/skbuff.h:2314
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06880)
Location: include/linux/skbuff.h:2314
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/xfrm_device.c (ffffffff81b305ba)
Location: include/linux/skbuff.h:2314
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff81b31569)
Location: include/linux/skbuff.h:2314
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81b407bb)
Location: include/linux/skbuff.h:2314
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81b62ed0)
Location: include/linux/skbuff.h:2314
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b6deb2)
Location: include/linux/skbuff.h:2314
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81b744a9)
Location: include/linux/skbuff.h:2314
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffffffff81b7bce5)
Location: include/linux/skbuff.h:2314
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81b8eef8)
Location: include/linux/skbuff.h:2314
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81b9299d)
Location: include/linux/skbuff.h:2314
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (ffffffff81b9c820)
Location: include/linux/skbuff.h:2314
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff819d615f)
Location: include/linux/skbuff.h:2330
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81a18922)
Location: include/linux/skbuff.h:2330
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff81a1dec1)
Location: include/linux/skbuff.h:2330
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8df9e)
Location: include/linux/skbuff.h:2330
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff81ad553d)
Location: include/linux/skbuff.h:2330
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af1f93)
Location: include/linux/skbuff.h:2330
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e42e)
Location: include/linux/skbuff.h:2330
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff81b1f1db)
Location: include/linux/skbuff.h:2330
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e04b)
Location: include/linux/skbuff.h:2330
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81b511e0)
Location: include/linux/skbuff.h:2330
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5c231)
Location: include/linux/skbuff.h:2330
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81b62f08)
Location: include/linux/skbuff.h:2330
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a7ad)
Location: include/linux/skbuff.h:2330
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81b7df2e)
Location: include/linux/skbuff.h:2330
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81af7)
Location: include/linux/skbuff.h:2330
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (ffffffff81b8b8e0)
Location: include/linux/skbuff.h:2330
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff81a867a4)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81ac9e12)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff81ad1951)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/ipv4/ip_fragment.c (ffffffff81b4918e)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff81b94343)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb24a3)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/xfrm_device.c (ffffffff81be2f1e)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff81be3d1b)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81bf432b)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81c18640)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81c23998)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81c2a9b8)
Location: include/linux/skbuff.h:2359
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81c3260d)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81c48d9e)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4db3b)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (ffffffff81c57b80)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff81bfba62)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81c4696c)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff81c4f5e7)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd680a)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff81d25c0a)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45c68)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a0ce)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff81d7ad7d)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d03c)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81db46c9)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81dc08b6)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81dc7e95)
Location: include/linux/skbuff.h:2727
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81dcfe02)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81de84ab)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee212)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (ffffffff81df9204)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb855c)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffff800010c008e0)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffff800010c04cf4)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffff800010c5f800)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffff800010ca4f84)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (ffff800010cedd78)
Location: include/linux/skbuff.h:2270
Inline: True
```
```
In net/ipv6/ip6_input.c (ffff800010cfd7f8)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffff800010d20ec4)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffff800010d2cda4)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffff800010d3552c)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffff800010d3b870)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffff800010d50bec)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffff800010d549fc)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (ffff800010d5f318)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
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
In net/core/skbuff.c (c0cd4fd4)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (c0d12554)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (c0d1e1bc)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (c0d6e858)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (c0db1890)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (c0df5fb4)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_input.c (c0e04ff8)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (c0e27b50)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/icmp.c (c0e30bc8)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (c0e375e8)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (c0e3df40)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (c0e5173c)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (c0e54ff0)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (c0e5ef90)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
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
In net/core/skbuff.c (c000000000c90624)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (c000000000ce39ac)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (c000000000ceeebc)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (c000000000d61da8)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (c000000000db8c3c)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (c000000000e12974)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_input.c (c000000000e258e4)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (c000000000e501bc)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (c000000000e5e8a4)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (c000000000e67574)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (c000000000e6f0e8)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (c000000000e889f0)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (c000000000e8d56c)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (c000000000e99f04)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffe000747d48)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffe00077a5be)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffe000783956)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c768c)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffe0008008b8)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b3c0)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_input.c (ffffffe000847cfe)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffe000862e16)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffe00086cfec)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffe0008728e6)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffffffe000878174)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffe000888f5c)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c37c)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (ffffffe000894a2a)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff818bde65)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff818f711b)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff8190144a)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff8194ea6e)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff8198eee5)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce6ae)
Location: include/linux/skbuff.h:2270
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff819dbbab)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff819fb200)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a064da)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81a0c452)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a123d5)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81a241c8)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81a274c0)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (ffffffff81a30e30)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff81877da5)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff818b0f4b)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff818bb27a)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff8190855e)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff819489a5)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b48e)
Location: include/linux/skbuff.h:2270
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff8199896b)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff819b7fc0)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c329a)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff819c9212)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cf195)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff819e0f88)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff819e4280)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (ffffffff819ee020)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff8190ee65)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff8194814b)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff8195247a)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff819b923e)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff819f9785)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (ffffffff81a3912e)
Location: include/linux/skbuff.h:2270
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a4662b)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81a65c80)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a70f5a)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81a76ed2)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a7ce55)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ec48)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a90a6d)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
```
```
In net/ipv6/ip6_offload.c (ffffffff81a93070)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (ffffffff81a9c9e0)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff8192ff95)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81969a5b)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff81973ec5)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff819c2b2e)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff81a03a75)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44b5e)
Location: include/linux/skbuff.h:2270
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a5235b)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81a72220)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a7d56a)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81a834f2)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a896a5)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81a9b9b8)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f21a)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (ffffffff81aa8bc0)
Location: include/linux/skbuff.h:2270
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
</details>
</li>
</ul>

## Differences

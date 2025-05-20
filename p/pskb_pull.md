# Function: <code>pskb_pull</code>

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
In net/core/skbuff.c (ffffffff81709257)
Location: include/linux/skbuff.h:1846
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/ipv4/ip_fragment.c (ffffffff817599d9)
Location: include/linux/skbuff.h:1846
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/icmp.c (ffffffff8178f26a)
Location: include/linux/skbuff.h:1846
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff817c86b6)
Location: include/linux/skbuff.h:1846
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/ndisc.c (ffffffff817e14d6)
Location: include/linux/skbuff.h:1846
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/icmp.c (ffffffff817e879d)
Location: include/linux/skbuff.h:1846
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff817edf09)
Location: include/linux/skbuff.h:1846
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
In net/core/skbuff.c (ffffffff8177104a)
Location: include/linux/skbuff.h:1947
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/sock_reuseport.c (ffffffff817a0059)
Location: include/linux/skbuff.h:1947
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff817c5db8)
Location: include/linux/skbuff.h:1947
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/icmp.c (ffffffff817fc8d2)
Location: include/linux/skbuff.h:1947
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81835804)
Location: include/linux/skbuff.h:1947
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/ndisc.c (ffffffff8184d374)
Location: include/linux/skbuff.h:1947
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81856f55)
Location: include/linux/skbuff.h:1947
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff8185c751)
Location: include/linux/skbuff.h:1947
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
In net/core/skbuff.c (ffffffff8179e16a)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/sock_reuseport.c (ffffffff817cea29)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff817f58b8)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/icmp.c (ffffffff8182d835)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81867334)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/ndisc.c (ffffffff8187f22d)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81888d55)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff8188e661)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81894f20)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
In net/core/skbuff.c (ffffffff817bbfaa)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/sock_reuseport.c (ffffffff817edec8)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff81815cbd)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/icmp.c (ffffffff8184ec4a)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff8188bab4)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/ndisc.c (ffffffff818a52cd)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff818af3d9)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff818b4ca8)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818bb268)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
In net/core/skbuff.c (ffffffff818361ab)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/sock_reuseport.c (ffffffff8186a108)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff81894eab)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/icmp.c (ffffffff818ce9ca)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff8190cd94)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/ndisc.c (ffffffff81927cbd)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff819320e9)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81937a18)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193e27e)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff8194f8bc)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff8195b276)
Location: include/linux/skbuff.h:2088
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
In net/core/skbuff.c (ffffffff81880217)
Location: include/linux/skbuff.h:2099
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/sock_reuseport.c (ffffffff818b9de7)
Location: include/linux/skbuff.h:2099
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff818e8f53)
Location: include/linux/skbuff.h:2099
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/icmp.c (ffffffff81924d3f)
Location: include/linux/skbuff.h:2099
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81964187)
Location: include/linux/skbuff.h:2099
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/ndisc.c (ffffffff81980065)
Location: include/linux/skbuff.h:2099
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff8198ac37)
Location: include/linux/skbuff.h:2099
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81990899)
Location: include/linux/skbuff.h:2099
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819971ab)
Location: include/linux/skbuff.h:2099
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff819a888c)
Location: include/linux/skbuff.h:2099
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff819b4998)
Location: include/linux/skbuff.h:2099
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
In net/core/skbuff.c (ffffffff818a10dd)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff818d7202)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff818e0b5e)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff81916124)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/icmp.c (ffffffff81953b4e)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81999a64)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff819b6651)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c1504)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff819c6fe3)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cda99)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff819df3cc)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff819eb9a7)
Location: include/linux/skbuff.h:2177
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
In net/core/skbuff.c (ffffffff818ebd24)
Location: include/linux/skbuff.h:2265
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81924d12)
Location: include/linux/skbuff.h:2265
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff8192f1fe)
Location: include/linux/skbuff.h:2265
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff81978285)
Location: include/linux/skbuff.h:2265
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff819b8437)
Location: include/linux/skbuff.h:2265
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (ffffffff819f83ba)
Location: include/linux/skbuff.h:2265
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a05994)
Location: include/linux/skbuff.h:2265
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81a250e3)
Location: include/linux/skbuff.h:2265
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a302ec)
Location: include/linux/skbuff.h:2265
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81a3629a)
Location: include/linux/skbuff.h:2265
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c0b7)
Location: include/linux/skbuff.h:2265
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81a4df5c)
Location: include/linux/skbuff.h:2265
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81a5ab40)
Location: include/linux/skbuff.h:2265
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
In net/core/skbuff.c (ffffffff8191de5b)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81957142)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff8196146e)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff819aebf5)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff819ef137)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f01a)
Location: include/linux/skbuff.h:2279
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c513)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81a5bb63)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a66e3c)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81a6cdba)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a72d37)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81a84b30)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81a91794)
Location: include/linux/skbuff.h:2279
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
In net/core/skbuff.c (ffffffff819f0be3)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81a2f7a0)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff81a34ae8)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/ipv4/ip_fragment.c (ffffffff81a99015)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff81add089)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (ffffffff81b21be2)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_input.c (ffffffff81b31bb3)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81b548a3)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5f704)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81b65d31)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d230)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81b7fbc0)
Location: include/linux/skbuff.h:2302
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81b8cbc4)
Location: include/linux/skbuff.h:2302
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
In net/core/skbuff.c (ffffffff819f0a50)
Location: include/linux/skbuff.h:2323
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81a31ab0)
Location: include/linux/skbuff.h:2323
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff81a36e28)
Location: include/linux/skbuff.h:2323
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa2f85)
Location: include/linux/skbuff.h:2323
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff81ae9dd9)
Location: include/linux/skbuff.h:2323
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06874)
Location: include/linux/skbuff.h:2323
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/xfrm_device.c (ffffffff81b305b2)
Location: include/linux/skbuff.h:2323
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_input.c (ffffffff81b407b3)
Location: include/linux/skbuff.h:2323
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81b62ec3)
Location: include/linux/skbuff.h:2323
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b6dea4)
Location: include/linux/skbuff.h:2323
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81b744a1)
Location: include/linux/skbuff.h:2323
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffffffff81b7bcd8)
Location: include/linux/skbuff.h:2323
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81b8eef0)
Location: include/linux/skbuff.h:2323
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81b9c814)
Location: include/linux/skbuff.h:2323
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
In net/core/skbuff.c (ffffffff819d6157)
Location: include/linux/skbuff.h:2339
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81a18919)
Location: include/linux/skbuff.h:2339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff81a1deb5)
Location: include/linux/skbuff.h:2339
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8df95)
Location: include/linux/skbuff.h:2339
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff81ad552f)
Location: include/linux/skbuff.h:2339
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af1f87)
Location: include/linux/skbuff.h:2339
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e426)
Location: include/linux/skbuff.h:2339
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e043)
Location: include/linux/skbuff.h:2339
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81b511d3)
Location: include/linux/skbuff.h:2339
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5c223)
Location: include/linux/skbuff.h:2339
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81b62f00)
Location: include/linux/skbuff.h:2339
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a7a0)
Location: include/linux/skbuff.h:2339
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81b7df22)
Location: include/linux/skbuff.h:2339
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81b8b8d4)
Location: include/linux/skbuff.h:2339
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
In net/core/skbuff.c (ffffffff81a8679c)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81ac9e09)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff81ad1945)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/ipv4/ip_fragment.c (ffffffff81b49185)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff81b94335)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2497)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/xfrm_device.c (ffffffff81be2f16)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4323)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81c18633)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81c2398a)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81c2a9b0)
Location: include/linux/skbuff.h:2368
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81c32600)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81c48d92)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81c57b74)
Location: include/linux/skbuff.h:2368
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
In net/core/skbuff.c (ffffffff81bfba5a)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81c46964)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff81c4f5d9)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6801)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff81d25bfe)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45c5b)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a0c6)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d034)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81db46bd)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81dc08aa)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81dc7e8d)
Location: include/linux/skbuff.h:2736
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81dcfdf6)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81de84a3)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81df91f5)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff81daaa9d)
Location: include/linux/skbuff.h:2633
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81dfae8a)
Location: include/linux/skbuff.h:2633
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff81e0458c)
Location: include/linux/skbuff.h:2633
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff81e96dba)
Location: include/linux/skbuff.h:2633
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff81eed560)
Location: include/linux/skbuff.h:2633
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f02b)
Location: include/linux/skbuff.h:2633
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/xfrm_device.c (ffffffff81f46f19)
Location: include/linux/skbuff.h:2633
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff81f4809d)
Location: include/linux/skbuff.h:2633
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b438)
Location: include/linux/skbuff.h:2633
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81f84240)
Location: include/linux/skbuff.h:2633
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81f91030)
Location: include/linux/skbuff.h:2633
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81f98c0f)
Location: include/linux/skbuff.h:2633
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81fa1183)
Location: include/linux/skbuff.h:2633
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb479)
Location: include/linux/skbuff.h:2633
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc2784)
Location: include/linux/skbuff.h:2633
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (ffffffff81fcd7e5)
Location: include/linux/skbuff.h:2633
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff81e1a549)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81e6c08b)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff81e76ddc)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef55fa)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff81f4cf20)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6ed29)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6919)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff81fa7b9d)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb20a)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81fe4539)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81ff1920)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81ff95ec)
Location: include/linux/skbuff.h:2687
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff8201bb39)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_offload.c (ffffffff82023702)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/strparser/strparser.c (ffffffff82049115)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff81ed7b09)
Location: include/linux/skbuff.h:2694
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81f2b97b)
Location: include/linux/skbuff.h:2694
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff81f36d9c)
Location: include/linux/skbuff.h:2694
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb95aa)
Location: include/linux/skbuff.h:2694
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff82013030)
Location: include/linux/skbuff.h:2694
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035449)
Location: include/linux/skbuff.h:2694
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/xfrm4_input.c (ffffffff82052e95)
Location: include/linux/skbuff.h:2694
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_gro_udp_encap_rcv
```
```
In net/xfrm/xfrm_device.c (ffffffff82073c09)
Location: include/linux/skbuff.h:2694
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff82074e5d)
Location: include/linux/skbuff.h:2694
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff8208861a)
Location: include/linux/skbuff.h:2694
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff820b2439)
Location: include/linux/skbuff.h:2694
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff820bf51f)
Location: include/linux/skbuff.h:2694
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff820c725c)
Location: include/linux/skbuff.h:2694
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e1647)
Location: include/linux/skbuff.h:2694
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_gro_udp_encap_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff820eaaf9)
Location: include/linux/skbuff.h:2694
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff8211b495)
Location: include/linux/skbuff.h:2694
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffff800010bb8550)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffff800010c008d8)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffff800010c04ce8)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffff800010c5f7f8)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffff800010ca4f78)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (ffff800010cedd70)
Location: include/linux/skbuff.h:2279
Inline: True
```
```
In net/ipv6/ip6_input.c (ffff800010cfd7f0)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffff800010d20ebc)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffff800010d2cd98)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffff800010d35524)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffff800010d3b864)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffff800010d50be4)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffff800010d5f30c)
Location: include/linux/skbuff.h:2279
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
In net/core/skbuff.c (c0cd50d8)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (c0d12548)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (c0d1e1b0)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (c0d6e850)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (c0db1884)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (c0df5fac)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_input.c (c0e04ff0)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (c0e27b48)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/icmp.c (c0e30bbc)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (c0e375e0)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (c0e3df34)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (c0e51730)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (c0e5ef80)
Location: include/linux/skbuff.h:2279
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
In net/core/skbuff.c (c000000000c90618)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (c000000000ce39a0)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (c000000000ceeeb4)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (c000000000d61da4)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (c000000000db8c30)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (c000000000e12970)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_input.c (c000000000e258e0)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (c000000000e501b8)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (c000000000e5e898)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (c000000000e67570)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (c000000000e6f0e0)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (c000000000e889e4)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (c000000000e99ef8)
Location: include/linux/skbuff.h:2279
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
In net/core/skbuff.c (ffffffe000747d38)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffe00077a5b6)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffe00078394a)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c7678)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffe0008008b0)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b3a4)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_input.c (ffffffe000847cfe)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffe000862e06)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffe00086cfe4)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffe0008728d8)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffffffe00087816e)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffe000888f56)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffe000894a24)
Location: include/linux/skbuff.h:2279
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
In net/core/skbuff.c (ffffffff818bde5b)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff818f7112)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff8190143e)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff8194ea65)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff8198eed7)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce6aa)
Location: include/linux/skbuff.h:2279
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff819dbba3)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff819fb1f3)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a064cc)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81a0c44a)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a123c7)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81a241c0)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81a30e24)
Location: include/linux/skbuff.h:2279
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
In net/core/skbuff.c (ffffffff81877d9b)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff818b0f42)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff818bb26e)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff81908555)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff81948997)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b48a)
Location: include/linux/skbuff.h:2279
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81998963)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff819b7fb3)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c328c)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff819c920a)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cf187)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff819e0f80)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff819ee014)
Location: include/linux/skbuff.h:2279
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
In net/core/skbuff.c (ffffffff8190ee5b)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81948142)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff8195246e)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9235)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff819f9777)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (ffffffff81a3912a)
Location: include/linux/skbuff.h:2279
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a46623)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81a65c73)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a70f4c)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81a76eca)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a7ce47)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ec40)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a90a64)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
```
```
In net/strparser/strparser.c (ffffffff81a9c9d4)
Location: include/linux/skbuff.h:2279
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
In net/core/skbuff.c (ffffffff8192ff8b)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81969a52)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
```
```
In net/core/sock_reuseport.c (ffffffff81973eb9)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_fragment.c (ffffffff819c2b25)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffff81a03a67)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44b5a)
Location: include/linux/skbuff.h:2279
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a52353)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81a72213)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a7d55c)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81a834ea)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a89697)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_local.c (ffffffff81a9b9b0)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/strparser/strparser.c (ffffffff81aa8bb4)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
</details>
</li>
</ul>

## Differences

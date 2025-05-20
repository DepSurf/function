# Function: <code>ip6_dst_idev</code>

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
In net/ipv6/ip6_output.c (ffffffff817c4a2c)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff817c8691)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff817d3ab5)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_get_saddr
```
```
In net/ipv6/icmp.c (ffffffff817e7aae)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff817edd16)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff817f2dd1)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff817f7f20)
Location: include/net/ip6_fib.h:138
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/net/ip6_fib.h:138
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff817fdc43)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/ip6_fib.h:138
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
In net/ipv6/ip6_output.c (ffffffff81831afc)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff818361ce)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/route.c (ffffffff81841540)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff81855f40)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff8185c556)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81861c00)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81867c1c)
Location: include/net/ip6_fib.h:138
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/net/ip6_fib.h:138
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff8186d573)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/ip6_fib.h:138
Inline: True
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
In net/ipv6/ip6_output.c (ffffffff8186352c)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81867cde)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/route.c (ffffffff818733a0)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff81887d95)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff8188e466)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81893b70)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8189aa7c)
Location: include/net/ip6_fib.h:138
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/net/ip6_fib.h:138
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff818a035e)
Location: include/net/ip6_fib.h:138
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/ip6_fib.h:138
Inline: True
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
In net/ipv6/ip6_output.c (ffffffff81887be2)
Location: include/net/ip6_fib.h:141
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8188c4ee)
Location: include/net/ip6_fib.h:141
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/route.c (ffffffff81898efe)
Location: include/net/ip6_fib.h:141
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff818ae3fd)
Location: include/net/ip6_fib.h:141
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff818b4e53)
Location: include/net/ip6_fib.h:141
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818ba17b)
Location: include/net/ip6_fib.h:141
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff818c0c2c)
Location: include/net/ip6_fib.h:141
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/net/ip6_fib.h:141
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff818c69a0)
Location: include/net/ip6_fib.h:141
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/ip6_fib.h:141
Inline: True
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
In net/ipv6/ip6_output.c (ffffffff81908ea2)
Location: include/net/ip6_fib.h:185
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8190d7de)
Location: include/net/ip6_fib.h:185
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/route.c (ffffffff8191a204)
Location: include/net/ip6_fib.h:185
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff8193109f)
Location: include/net/ip6_fib.h:185
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81937bc3)
Location: include/net/ip6_fib.h:185
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193d15b)
Location: include/net/ip6_fib.h:185
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81943e3c)
Location: include/net/ip6_fib.h:185
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/net/ip6_fib.h:185
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81949d9e)
Location: include/net/ip6_fib.h:185
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/ip6_fib.h:185
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/ip6_fib.h:185
Inline: True
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
In net/ipv6/ip6_output.c (ffffffff81960172)
Location: include/net/ip6_fib.h:202
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8196415f)
Location: include/net/ip6_fib.h:202
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/route.c (ffffffff8197080b)
Location: include/net/ip6_fib.h:202
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff81989d2e)
Location: include/net/ip6_fib.h:202
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81990670)
Location: include/net/ip6_fib.h:202
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819970a4)
Location: include/net/ip6_fib.h:202
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8199c590)
Location: include/net/ip6_fib.h:202
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a1080)
Location: include/net/ip6_fib.h:202
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (ffffffff819a2e3c)
Location: include/net/ip6_fib.h:202
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (ffffffff819a3aba)
Location: include/net/ip6_fib.h:202
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv6/ip6_output.c (ffffffff81994f52)
Location: include/net/ip6_fib.h:205
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81999a22)
Location: include/net/ip6_fib.h:205
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff819a643b)
Location: include/net/ip6_fib.h:205
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff819c05d2)
Location: include/net/ip6_fib.h:205
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff819c6da0)
Location: include/net/ip6_fib.h:205
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cd992)
Location: include/net/ip6_fib.h:205
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819d4da0)
Location: include/net/ip6_fib.h:205
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d7cb0)
Location: include/net/ip6_fib.h:205
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (ffffffff819d9b11)
Location: include/net/ip6_fib.h:205
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (ffffffff819da3e5)
Location: include/net/ip6_fib.h:205
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv6/ip6_output.c (ffffffff81a009f2)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a05952)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a12b36)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff81a2eb43)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/reassembly.c (ffffffff81a3608a)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c82e)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a43c05)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a46cc0)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (ffffffff81a4838a)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (ffffffff81a48fb0)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv6/ip6_output.c (ffffffff81a375c5)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c4d1)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a49726)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff81a65693)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/reassembly.c (ffffffff81a6cbaa)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a734ae)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a790b0)
Location: include/net/ip6_fib.h:210
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a7d870)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (ffffffff81a7ef3a)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (ffffffff81a7fba0)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv6/ip6_output.c (ffffffff81b2caec)
Location: include/net/ip6_fib.h:238
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b31b71)
Location: include/net/ip6_fib.h:238
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81b40176)
Location: include/net/ip6_fib.h:238
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff81b5de7a)
Location: include/net/ip6_fib.h:238
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/reassembly.c (ffffffff81b66266)
Location: include/net/ip6_fib.h:238
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d908)
Location: include/net/ip6_fib.h:238
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b735b0)
Location: include/net/ip6_fib.h:238
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b78160)
Location: include/net/ip6_fib.h:238
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (ffffffff81b79b84)
Location: include/net/ip6_fib.h:238
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (ffffffff81b7a9b0)
Location: include/net/ip6_fib.h:238
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/core/filter.c (ffffffff81a2ebac)
Location: include/net/ip6_fib.h:239
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b3b4fc)
Location: include/net/ip6_fib.h:239
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b40771)
Location: include/net/ip6_fib.h:239
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81b4eb56)
Location: include/net/ip6_fib.h:239
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff81b6c64a)
Location: include/net/ip6_fib.h:239
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/reassembly.c (ffffffff81b749e6)
Location: include/net/ip6_fib.h:239
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffffffff81b7c3c0)
Location: include/net/ip6_fib.h:239
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b822e0)
Location: include/net/ip6_fib.h:239
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b870b0)
Location: include/net/ip6_fib.h:239
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (ffffffff81b88ad2)
Location: include/net/ip6_fib.h:239
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (ffffffff81b8990d)
Location: include/net/ip6_fib.h:239
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/core/filter.c (ffffffff81a16202)
Location: include/net/ip6_fib.h:240
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b28c7a)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e001)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81b3c986)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff81b5a9ae)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/reassembly.c (ffffffff81b6350a)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b6aead)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b71320)
Location: include/net/ip6_fib.h:240
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b75d80)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (ffffffff81b778d0)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (ffffffff81b7875d)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/core/filter.c (ffffffff81ac7901)
Location: include/net/ip6_fib.h:242
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv6/ip6_output.c (ffffffff81beeb6a)
Location: include/net/ip6_fib.h:242
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81bf42e1)
Location: include/net/ip6_fib.h:242
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81c032ab)
Location: include/net/ip6_fib.h:242
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff81c220ae)
Location: include/net/ip6_fib.h:242
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/reassembly.c (ffffffff81c2afca)
Location: include/net/ip6_fib.h:242
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81c32d0d)
Location: include/net/ip6_fib.h:242
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81c3b590)
Location: include/net/ip6_fib.h:242
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81c407f0)
Location: include/net/ip6_fib.h:242
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (ffffffff81c423ca)
Location: include/net/ip6_fib.h:242
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (ffffffff81c4329d)
Location: include/net/ip6_fib.h:242
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/core/filter.c (ffffffff81c440ff)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv6/ip6_output.c (ffffffff81d871ea)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81d8cff2)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81d9d1f7)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff81dbf0ec)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/reassembly.c (ffffffff81dc827a)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81dd04e8)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81dd96b0)
Location: include/net/ip6_fib.h:243
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81ddee80)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (ffffffff81de0e70)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (ffffffff81de2014)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/core/filter.c (ffffffff81df844f)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv6/ip6_output.c (ffffffff81f54d0a)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b152)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81f6c127)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff81f8f36d)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/reassembly.c (ffffffff81f9900a)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81fa1878)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81fab2e0)
Location: include/net/ip6_fib.h:243
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81fb0f40)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (ffffffff81fb32b0)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (ffffffff81fb4544)
Location: include/net/ip6_fib.h:243
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/core/filter.c (ffffffff81e69ab8)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv6/ip6_output.c (ffffffff81fb471a)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81fbaf22)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81fcc25f)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff81fefb71)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/reassembly.c (ffffffff81ff99da)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff820020ea)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8200ba80)
Location: include/net/ip6_fib.h:240
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820115f0)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (ffffffff820139a0)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (ffffffff82014d09)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/core/filter.c (ffffffff81f29122)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv6/ip6_output.c (ffffffff82081fca)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff82088332)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff82099a41)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff820bd741)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/reassembly.c (ffffffff820c764a)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff820d0eea)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff820daa90)
Location: include/net/ip6_fib.h:240
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e0580)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (ffffffff820e2b01)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (ffffffff820e3e49)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv6/ip6_output.c (ffff800010cf8c28)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffff800010cfd7c4)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffff800010d11e28)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffff800010d2b8fc)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/reassembly.c (ffff800010d35898)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffff800010d3bf20)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffff800010d42db0)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2_finish
  - net/ipv6/ip6mr.c:ip6mr_forward2_finish
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d48a58)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (ffff800010d4a820)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (ffff800010d4b204)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv6/ip6_output.c (c0dfeadc)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c0e04fb8)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (c0e12b74)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (c0e2f4e0)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/reassembly.c (c0e37aa4)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (c0e3efcc)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (c0e46964)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_policy.c (c0e4a0b4)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (c0e4b748)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (c0e4c56c)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv6/ip6_output.c (c000000000e1f0d0)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c000000000e258a8)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (c000000000e37e18)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (c000000000e5ce48)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/reassembly.c (c000000000e6795c)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (c000000000e6fa34)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (c000000000e77474)
Location: include/net/ip6_fib.h:210
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7de94)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (c000000000e80130)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (c000000000e815c8)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv6/ip6_output.c (ffffffe0008435ec)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffe000847d20)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffe000853e1e)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffe00086ba96)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/reassembly.c (ffffffe000872d44)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffffffe000878998)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffe00087d860)
Location: include/net/ip6_fib.h:210
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffe000882160)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (ffffffe0008836ea)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (ffffffe00088425e)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv6/ip6_output.c (ffffffff819d6c55)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff819dbb61)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff819e8db6)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff81a04d23)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/reassembly.c (ffffffff81a0c23a)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a12b3e)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a18740)
Location: include/net/ip6_fib.h:210
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a1cf00)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (ffffffff81a1e5ca)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (ffffffff81a1f230)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv6/ip6_output.c (ffffffff81993a15)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81998921)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff819a5b76)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff819c1ae3)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/reassembly.c (ffffffff819c8ffa)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cf8fe)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819d5500)
Location: include/net/ip6_fib.h:210
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d9cc0)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (ffffffff819db38a)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (ffffffff819dbff0)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv6/ip6_output.c (ffffffff81a416d5)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a465e1)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a53836)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff81a6f7a3)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/reassembly.c (ffffffff81a76cba)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a7d5be)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a831c0)
Location: include/net/ip6_fib.h:210
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a87980)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (ffffffff81a8904a)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (ffffffff81a89cb0)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv6/ip6_output.c (ffffffff81a4d335)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a52311)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a5f826)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/icmp.c (ffffffff81a7bdd3)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/reassembly.c (ffffffff81a832da)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a89e0e)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a8faa0)
Location: include/net/ip6_fib.h:210
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a94560)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/netfilter.c (ffffffff81a95caa)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/fib6_rules.c (ffffffff81a96910)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
```
</details>
</li>
</ul>

## Differences

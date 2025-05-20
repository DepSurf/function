# Function: <code>nf_hook_state_init</code>

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
In net/core/dev.c (ffffffff8171a8dd)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (ffffffff81758df7)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_forward.c (ffffffff8175ab48)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8175e1ab)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_output
```
```
In net/ipv4/raw.c (ffffffff81785629)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8178c277)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff817a92ce)
Location: include/linux/netfilter.h:62
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff817afefa)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff817b032b)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc403)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff817c4efc)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/ip6_input.c (ffffffff817c8e33)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_input
```
```
In net/ipv6/ndisc.c (ffffffff817de918)
Location: include/linux/netfilter.h:62
Inline: True
```
```
In net/ipv6/raw.c (ffffffff817e6820)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff817ea318)
Location: include/linux/netfilter.h:62
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff817f9ecb)
Location: include/linux/netfilter.h:62
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff817fce75)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff817fd3fb)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff8180065a)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (ffffffff81782d70)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (ffffffff817c54c5)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff817c6f06)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817cad44)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff817f2bf6)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff817f98b4)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81816b11)
Location: include/linux/netfilter.h:62
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff8181ce44)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8181d285)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff8182930d)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81833e6f)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81835c5b)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff8184c84b)
Location: include/linux/netfilter.h:62
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81854af3)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff81858beb)
Location: include/linux/netfilter.h:62
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81869743)
Location: include/linux/netfilter.h:62
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff8186c7b1)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff8186cd45)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81871d87)
Location: include/linux/netfilter.h:62
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (ffffffff817b064c)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (ffffffff817f4fce)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff817f6a00)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817fa9b3)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff818239fa)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8182a78d)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff818482b3)
Location: include/linux/netfilter.h:111
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff8184e70d)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8184eb44)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff8185aced)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff818658df)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81867785)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff8187e714)
Location: include/linux/netfilter.h:111
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81886911)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff8188a9d4)
Location: include/linux/netfilter.h:111
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8189c589)
Location: include/linux/netfilter.h:111
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff8189f5b9)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff8189fb34)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff818a6318)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (ffffffff817cee54)
Location: include/linux/netfilter.h:109
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (ffffffff8181546a)
Location: include/linux/netfilter.h:109
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81816db2)
Location: include/linux/netfilter.h:109
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8181adbd)
Location: include/linux/netfilter.h:109
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81844557)
Location: include/linux/netfilter.h:109
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8184b9be)
Location: include/linux/netfilter.h:109
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81869449)
Location: include/linux/netfilter.h:109
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81872187)
Location: include/linux/netfilter.h:109
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff818726e6)
Location: include/linux/netfilter.h:109
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff8187eb04)
Location: include/linux/netfilter.h:109
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff8188a111)
Location: include/linux/netfilter.h:109
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8188bf28)
Location: include/linux/netfilter.h:109
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff818a4765)
Location: include/linux/netfilter.h:109
Inline: True
```
```
In net/ipv6/raw.c (ffffffff818ace80)
Location: include/linux/netfilter.h:109
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff818b0dd5)
Location: include/linux/netfilter.h:109
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff818c296a)
Location: include/linux/netfilter.h:109
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff818c5b20)
Location: include/linux/netfilter.h:109
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff818c6146)
Location: include/linux/netfilter.h:109
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff818ccd8b)
Location: include/linux/netfilter.h:109
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (ffffffff818487d4)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (ffffffff8189462a)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81895f78)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81899d9d)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff818c3e94)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff818cb62e)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff818e9a93)
Location: include/linux/netfilter.h:111
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2b5d)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff818f30e8)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffba2)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff8190b311)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8190d21a)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff8192711b)
Location: include/linux/netfilter.h:111
Inline: True
```
```
In net/ipv6/raw.c (ffffffff8192f810)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff8193341b)
Location: include/linux/netfilter.h:111
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81944710)
Location: include/linux/netfilter.h:111
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81948e54)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff819494e8)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81951b6d)
Location: include/linux/netfilter.h:111
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (ffffffff81892910)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (ffffffff818e8853)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff818ea277)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff818ee22d)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81919b5f)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81921b0a)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff8194013f)
Location: include/linux/netfilter.h:122
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff819494d0)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff819499f8)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff819567b4)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81963708)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81964614)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff8197f4c6)
Location: include/linux/netfilter.h:122
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819883d1)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff8198be06)
Location: include/linux/netfilter.h:122
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8199e0bc)
Location: include/linux/netfilter.h:122
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff819a1f0f)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff819a25c8)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff819ab0fd)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (ffffffff818b677a)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (ffffffff81915576)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff819176d2)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8191b9fa)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff819483ca)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81950916)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81970a40)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b195)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b6b8)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b2ec)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819986c8)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81999f42)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff819b5a97)
Location: include/linux/netfilter.h:122
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819bed67)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff819c26e7)
Location: include/linux/netfilter.h:122
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d39f7)
Location: include/linux/netfilter.h:122
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff819d8b64)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff819d9238)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff819e1c1a)
Location: include/linux/netfilter.h:122
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (ffffffff819027ee)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (ffffffff81977aa4)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff8197962e)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8197dcd3)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff819ac540)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819b51df)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff819d8bf7)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e46a0)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e4be8)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff819f692e)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a03757)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a05e81)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81a24577)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a2d20b)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a315a7)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a42cb7)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a473b2)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a47ab8)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81a509bd)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (ffffffff81934a2e)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (ffffffff819ae434)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff819aff91)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819b4673)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff819e2fc7)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819ebf0f)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a10694)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b6b0)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1bc08)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d5a5)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a3a327)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c9f1)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81a5aff7)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a63dac)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a680f7)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a7a5c4)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a7df62)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a7e668)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81a875dd)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (ffffffff81a096f7)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (ffffffff81a982fb)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81a99e60)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a9e776)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81ad08aa)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81ad9c7d)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81b01ea4)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c74d)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b0cabd)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81b200ed)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81b2faaa)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b3208f)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81b53eb3)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81b5c829)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81b61927)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff81b75e94)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78ab0)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b7910c)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81b829eb)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (ffffffff81a0ac8b)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (ffffffff81aa224b)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81aa3dce)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81aa86b6)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81adc8ba)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81ae66ce)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81b0ff85)
Location: include/linux/netfilter.h:139
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1aa6d)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b1aded)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e9ec)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e535)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b40c91)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81b624a8)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81b6b037)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81b700a9)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (ffffffff81b84c05)
Location: include/linux/netfilter.h:139
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87a20)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b8808c)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81b9204f)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (ffffffff819f1649)
Location: include/linux/netfilter.h:139
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81a8d5ea)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81a8ee38)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a91da6)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81ac78f6)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81ad199e)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81afdb75)
Location: include/linux/netfilter.h:139
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0871d)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b08aac)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c766)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81b2cda8)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e531)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81b5052b)
Location: include/linux/netfilter.h:139
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b59352)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81b5d85b)
Location: include/linux/netfilter.h:139
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b73895)
Location: include/linux/netfilter.h:139
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b766d0)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b76dbc)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81b812df)
Location: include/linux/netfilter.h:139
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (ffffffff81aa2ee8)
Location: include/linux/netfilter.h:145
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81b487bf)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81b4a0c8)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81b4d1b3)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81b86155)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81b905cb)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81bbfc82)
Location: include/linux/netfilter.h:145
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb62a)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81bcb9a9)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81be10d6)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81bf2f05)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81bf484e)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81c17898)
Location: include/linux/netfilter.h:145
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81c20926)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81c24cd8)
Location: include/linux/netfilter.h:145
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81c3de62)
Location: include/linux/netfilter.h:145
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c4115d)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c41869)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47e55)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81c49411)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/output_core.c (ffffffff81c4d2fc)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (ffffffff81c199e1)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/ipv4/ip_input.c (ffffffff81cd5b97)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81cd763b)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81cda978)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81d16ab6)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81d22f51)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81d54633)
Location: include/linux/netfilter.h:145
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d610c6)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81d614c4)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77fc3)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81d8ba5b)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d639)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81db36e3)
Location: include/linux/netfilter.h:145
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81dbd6e7)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81dc2fea)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81ddc4c4)
Location: include/linux/netfilter.h:145
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddf8ff)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81de0094)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de7314)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81de8bd6)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/output_core.c (ffffffff81ded82c)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/packet/af_packet.c (ffffffff81df16a5)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/packet/af_packet.c:nf_hook_direct_egress
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
In net/core/dev.c (ffffffff81dcabf8)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/ipv4/ip_input.c (ffffffff81e96027)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81e97c8e)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81e9b178)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81edd291)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81eea451)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81f1e86f)
Location: include/linux/netfilter.h:145
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2b9b6)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81f2bde4)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44859)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81f59a23)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b75d)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81f8309a)
Location: include/linux/netfilter.h:145
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81f8dc26)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81f93af5)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81fad5c9)
Location: include/linux/netfilter.h:145
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1c0d)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb23d4)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fba134)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81fbbb03)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/output_core.c (ffffffff81fc165c)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/packet/af_packet.c (ffffffff81fc5645)
Location: include/linux/netfilter.h:145
Inline: True
Inline callers:
  - net/packet/af_packet.c:nf_hook_direct_egress
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
In net/core/dev.c (ffffffff81e3b5fc)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/ipv4/ip_input.c (ffffffff81ef486a)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81ef64d4)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81ef9b98)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81f3c4e1)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81f49d81)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81f7e36f)
Location: include/linux/netfilter.h:146
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b810)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81f8ba84)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa4052)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81fb96d7)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb52d)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81fe339a)
Location: include/linux/netfilter.h:146
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81fee412)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81ff446b)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff8200dd89)
Location: include/linux/netfilter.h:146
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff820122f7)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff82012ae4)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a864)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff8201c403)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/output_core.c (ffffffff820225dc)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/packet/af_packet.c (ffffffff82026255)
Location: include/linux/netfilter.h:146
Inline: True
Inline callers:
  - net/packet/af_packet.c:nf_hook_direct_egress
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
In net/core/dev.c (ffffffff81ef9958)
Location: include/linux/netfilter.h:157
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/ipv4/ip_input.c (ffffffff81fb87f1)
Location: include/linux/netfilter.h:157
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff81fba467)
Location: include/linux/netfilter.h:157
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81fbdac3)
Location: include/linux/netfilter.h:157
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff82002610)
Location: include/linux/netfilter.h:157
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff8200fea1)
Location: include/linux/netfilter.h:157
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff82043cde)
Location: include/linux/netfilter.h:157
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff82053110)
Location: include/linux/netfilter.h:157
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff82053384)
Location: include/linux/netfilter.h:157
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff82071382)
Location: include/linux/netfilter.h:157
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff82086c08)
Location: include/linux/netfilter.h:157
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8208893d)
Location: include/linux/netfilter.h:157
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff820b12ba)
Location: include/linux/netfilter.h:157
Inline: True
```
```
In net/ipv6/raw.c (ffffffff820bbfe4)
Location: include/linux/netfilter.h:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff820c0f8a)
Location: include/linux/netfilter.h:157
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820dc913)
Location: include/linux/netfilter.h:157
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e1467)
Location: include/linux/netfilter.h:157
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff820e1c44)
Location: include/linux/netfilter.h:157
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e9824)
Location: include/linux/netfilter.h:157
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff820eb3d3)
Location: include/linux/netfilter.h:157
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/output_core.c (ffffffff820f16fc)
Location: include/linux/netfilter.h:157
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/packet/af_packet.c (ffffffff820f5c65)
Location: include/linux/netfilter.h:157
Inline: True
Inline callers:
  - net/packet/af_packet.c:nf_hook_direct_egress
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
In net/core/dev.c (ffff800010bd2d00)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (ffff800010c5e948)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffff800010c6064c)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffff800010c64dc8)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffff800010c97d98)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/arp.c (ffff800010ca16c0)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffff800010cc9934)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd7920)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7ed4)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffff800010cec4dc)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffff800010cfb318)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffff800010cfdd30)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffff800010d203e4)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/raw.c (ffff800010d29e98)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffff800010d2deac)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/ip6mr.c (ffff800010d42ebc)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffff800010d4931c)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffff800010d49b24)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffff800010d53eac)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (c0ced8c0)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (c0d6ddec)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (c0d6ff70)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c0d74a24)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (c0da5b48)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (c0dae810)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (c0dd7470)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_input.c (c0de13e0)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (c0de19ac)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (c0df4408)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (c0e01d9c)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c0e05798)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (c0e251d0)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (c0e2db58)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (c0e338e8)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/ip6mr.c (c0e468c0)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_input.c (c0e4a6e4)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (c0e4ae24)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (c0e54664)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (c000000000cb1568)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (c000000000d6127c)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (c000000000d6364c)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c000000000d6914c)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (c000000000da8d6c)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/arp.c (c000000000db4c4c)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (c000000000de7ed0)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/xfrm4_input.c (c000000000df780c)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (c000000000df7fe8)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (c000000000e106dc)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (c000000000e228bc)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c000000000e25f9c)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (c000000000e4ec2c)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/raw.c (c000000000e5ad8c)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (c000000000e60c8c)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/ip6mr.c (c000000000e7a450)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e85c)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (c000000000e7f2c8)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (c000000000e8c810)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (ffffffe00075d0c4)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (ffffffe0007c6e60)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffe0007c87ea)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffe0007cc6da)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffe0007f612c)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/arp.c (ffffffe0007fe1f0)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffe00081e63a)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffe000827fb0)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffe000828476)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffe000839b8c)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffe000845d64)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffe0008481c2)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffe0008628e0)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/raw.c (ffffffe00086a586)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffe00086ec4c)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffe00087ff70)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffe000882818)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffe000882ebe)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffe00088b9e4)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (ffffffff818d4a2e)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (ffffffff8194e2a4)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff8194fe01)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819544e3)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff81982e37)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8198bd3f)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff819b00a4)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff819bad40)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb298)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff819ccc35)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819d99b7)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff819dc081)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff819fa687)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a0343c)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a07787)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a19c54)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a1d5f2)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a1dcf8)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81a26c6d)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (ffffffff8188e8be)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (ffffffff81907d94)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff819098f1)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8190dfd3)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff8193c8f7)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819457ff)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff8196c6d4)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977b30)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81978088)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81989a25)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81996777)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81998e41)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff819b7447)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819c01fc)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff819c4547)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d6a14)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff819da3b2)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff819daab8)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff819e3a2d)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (ffffffff81925a2e)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (ffffffff819b8a74)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff819ba5d1)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819becb3)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff819ed607)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819f654f)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a1a944)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a257c0)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25d18)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81a376b5)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a44437)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a46b01)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81a65107)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a6debc)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a72207)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a846d4)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a88072)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a88778)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81a9281d)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
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
In net/core/dev.c (ffffffff81946f37)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/ipv4/ip_input.c (ffffffff819c22f1)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff819c3ec6)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819c8618)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff819f74ec)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81a00757)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a25793)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30c47)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a311c3)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81a4305b)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a500e7)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a52858)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81a71658)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a7a4b4)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a7e858)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a91015)
Location: include/linux/netfilter.h:138
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a94c97)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a953d3)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81a9e908)
Location: include/linux/netfilter.h:138
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
</details>
</li>
</ul>

## Differences

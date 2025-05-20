# Function: <code>ipv6_get_dsfield</code>

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
In net/ipv6/ip6_input.c (ffffffff817c8c14)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff817e8266)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff817edda5)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817efcbb)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff817f529e)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/xfrm6_state.c (ffffffff817fca9b)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
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
In net/ipv6/ip6_input.c (ffffffff81835e8a)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81856a0a)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff8185c6eb)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185ea80)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff818643d1)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/xfrm6_state.c (ffffffff8186c3bb)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
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
In net/ipv6/ip6_input.c (ffffffff818679aa)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff8188880c)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff8188e5fb)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818900f5)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81896abf)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/xfrm6_state.c (ffffffff8189f1cb)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
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
In net/core/flow_dissector.c (ffffffff817c4bed)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/ip6_input.c (ffffffff8188c157)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff818aef04)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff818b4c3b)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b5b95)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff818bd038)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/xfrm6_state.c (ffffffff818c5733)
Location: include/net/dsfield.h:21
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
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
In net/core/flow_dissector.c (ffffffff8183e545)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/ip6_input.c (ffffffff8190d447)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81931c07)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff819379ab)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81938904)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81940158)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/xfrm6_state.c (ffffffff81948a13)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
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
In net/core/flow_dissector.c (ffffffff81888dbc)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/ip6_input.c (ffffffff81964798)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff8198a6b3)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff81990814)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819917a4)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff819990c0)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/xfrm6_state.c (ffffffff819a1acf)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
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
In net/core/flow_dissector.c (ffffffff818a9c51)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/ip6_input.c (ffffffff81999141)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff819c0fb1)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff819c6f61)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c7fe1)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff819cf8f8)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/xfrm6_state.c (ffffffff819d86ff)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
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
In net/core/flow_dissector.c (ffffffff818f57b8)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffff81924ae5)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4ebf)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a0504f)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a2fd36)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff81a36239)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a36a51)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81a3e75d)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/xfrm6_state.c (ffffffff81a46f5f)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
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
In net/core/flow_dissector.c (ffffffff819276ca)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffff81956f15)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2bb6f)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a3bc1f)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a66886)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff81a6cd59)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6d571)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81a753cd)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/xfrm6_state.c (ffffffff81a7db0f)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
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
In net/core/flow_dissector.c (ffffffff819fb945)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffff81a2c0d1)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e157)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1fb58)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
```
In net/ipv6/ip6_input.c (ffffffff81b310a2)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/icmp.c (ffffffff81b5f2e1)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff81b65cc1)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66a55)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81b6f609)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
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
In net/core/flow_dissector.c (ffffffff819fb60a)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffff81a2d6a9)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2ca27)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e468)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
```
In net/ipv6/ip6_input.c (ffffffff81b3fccb)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/icmp.c (ffffffff81b6da71)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff81b74431)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b74fb5)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/ipv6/datagram.c (ffffffff81b7e139)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
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
In net/core/flow_dissector.c (ffffffff819e1a9c)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffff81a149dd)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a667)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1bed8)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
```
In net/ipv6/ip6_input.c (ffffffff81b2db02)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/icmp.c (ffffffff81b5be07)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff81b62e89)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b63a31)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/ipv6/datagram.c (ffffffff81b6cd19)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
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
In net/core/flow_dissector.c (ffffffff81a91fe8)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffff81ac553d)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdec87)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0688)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
```
In net/ipv6/ip6_input.c (ffffffff81bf3d73)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/icmp.c (ffffffff81c2345a)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff81c2a939)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2b4f1)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/ipv6/datagram.c (ffffffff81c34c26)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
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
In net/core/flow_dissector.c (ffffffff81c082bd)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffff81c428bf)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81d75b3d)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81d776ca)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
```
In net/ipv6/ip6_input.c (ffffffff81d8ca8a)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/icmp.c (ffffffff81dc0359)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff81dc7e17)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc8a41)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/ipv6/datagram.c (ffffffff81dd25c9)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
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
In net/core/flow_dissector.c (ffffffff81db7c63)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffff81df789f)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41dc1)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_extract_header
```
```
In net/xfrm/xfrm_output.c (ffffffff81f43059)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_extract_header
```
```
In net/ipv6/ip6_input.c (ffffffff81f5ac9a)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/icmp.c (ffffffff81f90ac9)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff81f98b97)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f99e71)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/ipv6/datagram.c (ffffffff81fa3a49)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
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
In net/core/flow_dissector.c (ffffffff81e27f5b)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffff81e695aa)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1652)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_extract_header
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa2879)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_extract_header
```
```
In net/ipv6/ip6_input.c (ffffffff81fbaa4a)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/icmp.c (ffffffff81ff146b)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff81ff9576)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffa841)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/ipv6/datagram.c (ffffffff82004181)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
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
In net/core/flow_dissector.c (ffffffff81ee5fde)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffff81f28afa)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff8206e972)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_extract_header
```
```
In net/xfrm/xfrm_output.c (ffffffff8206fb79)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_extract_header
```
```
In net/ipv6/ip6_input.c (ffffffff82087e7a)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/icmp.c (ffffffff820bf067)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff820c71e6)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c8531)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/ipv6/datagram.c (ffffffff820d2f41)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
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
In net/core/flow_dissector.c (ffff800010bc4190)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffff800010bf86f8)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffff800010cea578)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/ip6_input.c (ffff800010cfd1b0)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/icmp.c (ffff800010d2c79c)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffff800010d354e0)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d35dec)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffff800010d3da78)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/xfrm6_state.c (ffff800010d48d78)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
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
In net/core/flow_dissector.c (c0cdefb8)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (c0d12328)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (c0df2754)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/ipv6/ip6_input.c (c0e04330)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/icmp.c (c0e30694)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (c0e37594)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (c0e383bc)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (c0e41038)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/xfrm6_state.c (c0e4a224)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
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
In net/core/flow_dissector.c (c000000000c9ea18)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (c000000000cdf634)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (c000000000e0e18c)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/ip6_input.c (c000000000e24c6c)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/icmp.c (c000000000e5e15c)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (c000000000e67494)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6800c)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (c000000000e722e0)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/xfrm6_state.c (c000000000e7e130)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
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
In net/core/flow_dissector.c (ffffffe00075067e)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffe00077a3e6)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffe00083815e)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffe000847558)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/icmp.c (ffffffe00086caca)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffe000872844)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000873380)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffe00087a14a)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/xfrm6_state.c (ffffffe0008822ca)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
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
In net/core/flow_dissector.c (ffffffff818c76ca)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffff818f6ee5)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb1ff)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff819db2af)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a05f16)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff81a0c3e9)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0cc01)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81a14a5d)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/xfrm6_state.c (ffffffff81a1d19f)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
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
In drivers/net/vxlan.c (ffffffff81772621)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/core/flow_dissector.c (ffffffff8188160a)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffff818b0d15)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/ipv4/ip_tunnel.c (ffffffff819679ba)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/ipv4/udp_tunnel.c (ffffffff8197202f)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv4/udp_tunnel.c:udp_tun_rx_dst
```
```
In net/xfrm/xfrm_input.c (ffffffff81987fef)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff8199806f)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff819c2cd6)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff819c91a9)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c99c1)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff819d181d)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/xfrm6_state.c (ffffffff819d9f5f)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
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
In net/core/flow_dissector.c (ffffffff819186ca)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffff81947f15)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35c7f)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a45d2f)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a70996)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff81a76e69)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a77681)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81a7f4dd)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/xfrm6_state.c (ffffffff81a87c1f)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a909f3)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
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
In net/core/flow_dissector.c (ffffffff81939a23)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffff81969825)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81a415ef)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a51a07)
Location: include/net/dsfield.h:22
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a7cfb4)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/reassembly.c (ffffffff81a83489)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a83d71)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81a8bd9d)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/xfrm6_state.c (ffffffff81a9484f)
Location: include/net/dsfield.h:22
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
</details>
</li>
</ul>

## Differences

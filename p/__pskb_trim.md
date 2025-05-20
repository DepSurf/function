# Function: <code>__pskb_trim</code>

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
In net/core/skbuff.c (ffffffff81708dc1)
Location: include/linux/skbuff.h:2175
Inline: True
Inline callers:
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
```
```
In net/core/filter.c (ffffffff81730ad7)
Location: include/linux/skbuff.h:2175
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter
```
```
In net/ipv4/ip_input.c (ffffffff8175917b)
Location: include/linux/skbuff.h:2175
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81759ebc)
Location: include/linux/skbuff.h:2175
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8175dc89)
Location: include/linux/skbuff.h:2175
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/udp.c (ffffffff8178a464)
Location: include/linux/skbuff.h:2175
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff817c652e)
Location: include/linux/skbuff.h:2175
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff817c8e9a)
Location: include/linux/skbuff.h:2175
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff817e4b0b)
Location: include/linux/skbuff.h:2175
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff817ee244)
Location: include/linux/skbuff.h:2175
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff817f2f73)
Location: include/linux/skbuff.h:2175
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
```
In net/packet/af_packet.c (ffffffff81808cb4)
Location: include/linux/skbuff.h:2175
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/skbuff.c (ffffffff81770853)
Location: include/linux/skbuff.h:2310
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff8179b7a0)
Location: include/linux/skbuff.h:2310
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_input.c (ffffffff817c553a)
Location: include/linux/skbuff.h:2310
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817c62a5)
Location: include/linux/skbuff.h:2310
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff817cb153)
Location: include/linux/skbuff.h:2310
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/udp.c (ffffffff817f7b76)
Location: include/linux/skbuff.h:2310
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81833619)
Location: include/linux/skbuff.h:2310
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81836118)
Location: include/linux/skbuff.h:2310
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff818529a3)
Location: include/linux/skbuff.h:2310
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff8185ca86)
Location: include/linux/skbuff.h:2310
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81861dc4)
Location: include/linux/skbuff.h:2310
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
```
In net/packet/af_packet.c (ffffffff8187a1d0)
Location: include/linux/skbuff.h:2310
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/skbuff.c (ffffffff8179d9c3)
Location: include/linux/skbuff.h:2332
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff817ca94f)
Location: include/linux/skbuff.h:2332
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff817f5038)
Location: include/linux/skbuff.h:2332
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817f5da5)
Location: include/linux/skbuff.h:2332
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff817fada8)
Location: include/linux/skbuff.h:2332
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/udp.c (ffffffff81828a5e)
Location: include/linux/skbuff.h:2332
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff818650a9)
Location: include/linux/skbuff.h:2332
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81867c26)
Location: include/linux/skbuff.h:2332
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff818846a3)
Location: include/linux/skbuff.h:2332
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff8188e996)
Location: include/linux/skbuff.h:2332
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81893d34)
Location: include/linux/skbuff.h:2332
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
```
In net/packet/af_packet.c (ffffffff818aea40)
Location: include/linux/skbuff.h:2332
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/skbuff.c (ffffffff817be773)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff817e9b1c)
Location: include/linux/skbuff.h:2381
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff818154c7)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff8181637e)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8181b182)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/udp.c (ffffffff81849d5a)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81888868)
Location: include/linux/skbuff.h:2381
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff8188c43e)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff818aaa59)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff818b4eea)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818ba29d)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
```
In net/packet/af_packet.c (ffffffff818d378b)
Location: include/linux/skbuff.h:2381
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/skbuff.c (ffffffff81837eef)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81865191)
Location: include/linux/skbuff.h:2468
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81894693)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81895535)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8189a149)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/udp.c (ffffffff818c986f)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff8190abab)
Location: include/linux/skbuff.h:2468
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff8190d741)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff8192d576)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81937c5a)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193d286)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
```
In net/packet/af_packet.c (ffffffff81958833)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff8173d680)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818825bf)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff818b2cb1)
Location: include/linux/skbuff.h:2480
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff818ee5fb)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv6/ip6_output.c (ffffffff81961ff9)
Location: include/linux/skbuff.h:2480
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819b235b)
Location: include/linux/skbuff.h:2480
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff8176128c)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818a307c)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff818d5c3e)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff8191bdb9)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv6/ip6_output.c (ffffffff81996a1c)
Location: include/linux/skbuff.h:2556
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e9260)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff8179ef3e)
Location: include/linux/skbuff.h:2642
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818edd0f)
Location: include/linux/skbuff.h:2642
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff8192337f)
Location: include/linux/skbuff.h:2642
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff8197e0bb)
Location: include/linux/skbuff.h:2642
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8198aa05)
Location: include/linux/skbuff.h:2642
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv6/ip6_output.c (ffffffff81a02f61)
Location: include/linux/skbuff.h:2642
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a5773c)
Location: include/linux/skbuff.h:2642
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff817c34a5)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8191fe02)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81955640)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff819b49d2)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819c11ba)
Location: include/linux/skbuff.h:2656
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a39b36)
Location: include/linux/skbuff.h:2656
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a8e4d2)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff8188e9d3)
Location: include/linux/skbuff.h:2679
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff819f33dd)
Location: include/linux/skbuff.h:2679
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81a2bb37)
Location: include/linux/skbuff.h:2679
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81a9ec37)
Location: include/linux/skbuff.h:2679
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aac990)
Location: include/linux/skbuff.h:2679
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/xfrm/espintcp.c (ffffffff81b22995)
Location: include/linux/skbuff.h:2679
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f2fa)
Location: include/linux/skbuff.h:2679
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b8b2d2)
Location: include/linux/skbuff.h:2679
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff8189d344)
Location: include/linux/skbuff.h:2705
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff819f340d)
Location: include/linux/skbuff.h:2705
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81a2d0d6)
Location: include/linux/skbuff.h:2705
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81aa8b75)
Location: include/linux/skbuff.h:2705
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ab42e6)
Location: include/linux/skbuff.h:2705
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06a74)
Location: include/linux/skbuff.h:2705
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81b31645)
Location: include/linux/skbuff.h:2705
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b3dd47)
Location: include/linux/skbuff.h:2705
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b9a2a6)
Location: include/linux/skbuff.h:2705
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff8187fb8a)
Location: include/linux/skbuff.h:2721
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff819d966d)
Location: include/linux/skbuff.h:2721
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81a1416d)
Location: include/linux/skbuff.h:2721
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81a93c91)
Location: include/linux/skbuff.h:2721
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81a9f456)
Location: include/linux/skbuff.h:2721
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af2183)
Location: include/linux/skbuff.h:2721
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81b1f358)
Location: include/linux/skbuff.h:2721
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b202)
Location: include/linux/skbuff.h:2721
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b89200)
Location: include/linux/skbuff.h:2721
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff81910d0a)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81a8962d)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81ac5a3d)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81b4f0da)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81b5b206)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2693)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81be3f5c)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81bf1325)
Location: include/linux/skbuff.h:2750
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c55318)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff81a60b1f)
Location: include/linux/skbuff.h:3119
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81bfe97e)
Location: include/linux/skbuff.h:3119
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81c3ca98)
Location: include/linux/skbuff.h:3119
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81cdca34)
Location: include/linux/skbuff.h:3119
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45e5d)
Location: include/linux/skbuff.h:3119
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81d7af02)
Location: include/linux/skbuff.h:3119
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81d89bcd)
Location: include/linux/skbuff.h:3119
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df4aa7)
Location: include/linux/skbuff.h:3119
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff81bed105)
Location: include/linux/skbuff.h:3013
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81dad3ae)
Location: include/linux/skbuff.h:3013
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81dfa491)
Location: include/linux/skbuff.h:3013
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81e9d494)
Location: include/linux/skbuff.h:3013
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f224)
Location: include/linux/skbuff.h:3013
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81f4816f)
Location: include/linux/skbuff.h:3013
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81f57b33)
Location: include/linux/skbuff.h:3013
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc9d37)
Location: include/linux/skbuff.h:3013
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff81c455fe)
Location: include/linux/skbuff.h:3067
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81e1d2ae)
Location: include/linux/skbuff.h:3067
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81e6b83e)
Location: include/linux/skbuff.h:3067
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81efaa4e)
Location: include/linux/skbuff.h:3067
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6ef23)
Location: include/linux/skbuff.h:3067
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81fa7c6f)
Location: include/linux/skbuff.h:3067
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81fb75aa)
Location: include/linux/skbuff.h:3067
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202a66b)
Location: include/linux/skbuff.h:3067
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff81cfaf2c)
Location: include/linux/skbuff.h:3074
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81eda99e)
Location: include/linux/skbuff.h:3074
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81f2a9ee)
Location: include/linux/skbuff.h:3074
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81fbe99d)
Location: include/linux/skbuff.h:3074
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035655)
Location: include/linux/skbuff.h:3074
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff82074f2f)
Location: include/linux/skbuff.h:3074
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff82084c5d)
Location: include/linux/skbuff.h:3074
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fa156)
Location: include/linux/skbuff.h:3074
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffff8000109df128)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffff800010bba8ac)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffff800010c02188)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffff800010c65200)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffff800010c740d0)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv6/ip6_output.c (ffff800010cf99b0)
Location: include/linux/skbuff.h:2656
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d5b994)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (c0ac2d28)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (c0cd704c)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (c0d104e8)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (c0d74e08)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (c0d82710)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv6/ip6_output.c (c0e012c4)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
```
```
In net/packet/af_packet.c (c0e5b9d0)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (c000000000aa0b30)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (c000000000c93510)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (c000000000cdcfb0)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (c000000000d6960c)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (c000000000d7b0d0)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv6/ip6_output.c (c000000000e218b8)
Location: include/linux/skbuff.h:2656
Inline: True
```
```
In net/packet/af_packet.c (c000000000e95f90)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffe00062835e)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffe000749ae8)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffe0007785d8)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffe0007cca88)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffe0007d7608)
Location: include/linux/skbuff.h:2656
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffe000845764)
Location: include/linux/skbuff.h:2656
Inline: True
```
```
In net/packet/af_packet.c (ffffffe000892918)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff8178813a)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818bfe02)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff818f5610)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81954842)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8196102a)
Location: include/linux/skbuff.h:2656
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819d91c6)
Location: include/linux/skbuff.h:2656
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2db62)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff81767a8a)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81879d42)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff818af440)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff8190e332)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8191ab1a)
Location: include/linux/skbuff.h:2656
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81995f86)
Location: include/linux/skbuff.h:2656
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819ead52)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff817b8325)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81910e02)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81946640)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff81999b36)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
```
```
In net/ipv4/ip_output.c (ffffffff819bf012)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819cb7fa)
Location: include/linux/skbuff.h:2656
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a43c46)
Location: include/linux/skbuff.h:2656
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a99712)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff817d062a)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81931f62)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81967f48)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff819c8995)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819d538a)
Location: include/linux/skbuff.h:2656
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a4f8e6)
Location: include/linux/skbuff.h:2656
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa4520)
Location: include/linux/skbuff.h:2656
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
```
</details>
</li>
</ul>

## Differences

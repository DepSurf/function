# Function: <code>__skb_trim</code>

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
In net/core/skbuff.c (ffffffff81705e6d)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
```
```
In net/core/filter.c (ffffffff81730aff)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter
```
```
In net/ipv4/ip_input.c (ffffffff81759184)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81759eca)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8175d985)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81769c35)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8178a46e)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff817c61ee)
Location: include/linux/skbuff.h:2163
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff817c8ea4)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff817e4b19)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff817ee7f1)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff817f2f7d)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
```
In net/packet/af_packet.c (ffffffff81808d79)
Location: include/linux/skbuff.h:2163
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
In net/core/skbuff.c (ffffffff8177085d)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff8179b7ab)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_input.c (ffffffff817c5543)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817c62b3)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff817cb161)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff817d6479)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/udp.c (ffffffff817f7b84)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff818332a2)
Location: include/linux/skbuff.h:2298
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81836122)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff818529b1)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff8185d033)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81861dcd)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
```
In net/packet/af_packet.c (ffffffff8187a1de)
Location: include/linux/skbuff.h:2298
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
In net/core/skbuff.c (ffffffff8179d9cd)
Location: include/linux/skbuff.h:2325
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff817cb651)
Location: include/linux/skbuff.h:2325
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/ipv4/ip_input.c (ffffffff817f5041)
Location: include/linux/skbuff.h:2325
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817f5db3)
Location: include/linux/skbuff.h:2325
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff817fadb6)
Location: include/linux/skbuff.h:2325
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81806453)
Location: include/linux/skbuff.h:2325
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81828a6c)
Location: include/linux/skbuff.h:2325
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81864d6c)
Location: include/linux/skbuff.h:2325
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81867c30)
Location: include/linux/skbuff.h:2325
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff818846b1)
Location: include/linux/skbuff.h:2325
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff8188ef8f)
Location: include/linux/skbuff.h:2325
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81893d3d)
Location: include/linux/skbuff.h:2325
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
```
In net/packet/af_packet.c (ffffffff818aea4e)
Location: include/linux/skbuff.h:2325
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
In net/core/skbuff.c (ffffffff817be77d)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff817eaebb)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/ipv4/ip_input.c (ffffffff818154d0)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81816388)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8181b193)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81826b05)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81849d6a)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff8188874e)
Location: include/linux/skbuff.h:2374
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff8188c449)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff818aaa67)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff818b5556)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818ba2a7)
Location: include/linux/skbuff.h:2374
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
```
In net/packet/af_packet.c (ffffffff818d3799)
Location: include/linux/skbuff.h:2374
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
In net/core/skbuff.c (ffffffff81837ef9)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/filter.c (ffffffff8186799d)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/ipv4/ip_input.c (ffffffff8189469c)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81895541)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8189a156)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818a4a59)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/udp.c (ffffffff818c987d)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff8190a829)
Location: include/linux/skbuff.h:2461
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff8190d74c)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff8192d584)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff819382cc)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193d290)
Location: include/linux/skbuff.h:2461
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
```
In net/packet/af_packet.c (ffffffff8195890b)
Location: include/linux/skbuff.h:2461
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
In drivers/net/tun.c (ffffffff8173d68e)
Location: include/linux/skbuff.h:2473
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818825c9)
Location: include/linux/skbuff.h:2473
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/filter.c (ffffffff818b5912)
Location: include/linux/skbuff.h:2473
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/ipv4/ip_output.c (ffffffff818ee60c)
Location: include/linux/skbuff.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818faaef)
Location: include/linux/skbuff.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81961f00)
Location: include/linux/skbuff.h:2473
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819b2369)
Location: include/linux/skbuff.h:2473
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
In drivers/net/tun.c (ffffffff81761297)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818a3083)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/filter.c (ffffffff818dc485)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff8191bdc3)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819289ae)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81996986)
Location: include/linux/skbuff.h:2549
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e926b)
Location: include/linux/skbuff.h:2549
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
In drivers/net/tun.c (ffffffff8179ef4b)
Location: include/linux/skbuff.h:2635
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818edd18)
Location: include/linux/skbuff.h:2635
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/filter.c (ffffffff8192961d)
Location: include/linux/skbuff.h:2635
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff8197e0c8)
Location: include/linux/skbuff.h:2635
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8198b3ed)
Location: include/linux/skbuff.h:2635
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv6/ip6_output.c (ffffffff81a02ecc)
Location: include/linux/skbuff.h:2635
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a57749)
Location: include/linux/skbuff.h:2635
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
In drivers/net/tun.c (ffffffff817c34b2)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8191fe0b)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff8195bcf4)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff819b49df)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819c2693)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81a39aa1)
Location: include/linux/skbuff.h:2649
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a8e4df)
Location: include/linux/skbuff.h:2649
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
In drivers/net/tun.c (ffffffff8188e9dc)
Location: include/linux/skbuff.h:2672
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff819f33e6)
Location: include/linux/skbuff.h:2672
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/filter.c (ffffffff81a2ee4d)
Location: include/linux/skbuff.h:2672
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81a9ec44)
Location: include/linux/skbuff.h:2672
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aad8c3)
Location: include/linux/skbuff.h:2672
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/xfrm/espintcp.c (ffffffff81b2299e)
Location: include/linux/skbuff.h:2672
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f26f)
Location: include/linux/skbuff.h:2672
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b8b2df)
Location: include/linux/skbuff.h:2672
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
In drivers/net/tun.c (ffffffff8189d34d)
Location: include/linux/skbuff.h:2698
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff819f3416)
Location: include/linux/skbuff.h:2698
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/filter.c (ffffffff81a30963)
Location: include/linux/skbuff.h:2698
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81aa8b85)
Location: include/linux/skbuff.h:2698
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ab4ca7)
Location: include/linux/skbuff.h:2698
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06a7b)
Location: include/linux/skbuff.h:2698
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81b3164e)
Location: include/linux/skbuff.h:2698
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b3dcbf)
Location: include/linux/skbuff.h:2698
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b9a2b2)
Location: include/linux/skbuff.h:2698
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
In drivers/net/tun.c (ffffffff8187fb93)
Location: include/linux/skbuff.h:2714
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff819d9676)
Location: include/linux/skbuff.h:2714
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/filter.c (ffffffff81a1417a)
Location: include/linux/skbuff.h:2714
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81a93ca1)
Location: include/linux/skbuff.h:2714
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81a9fef2)
Location: include/linux/skbuff.h:2714
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af218a)
Location: include/linux/skbuff.h:2714
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81b1f361)
Location: include/linux/skbuff.h:2714
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b17a)
Location: include/linux/skbuff.h:2714
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b8920c)
Location: include/linux/skbuff.h:2714
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
In drivers/net/tun.c (ffffffff81910d17)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81a89636)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/filter.c (ffffffff81ac5a4a)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81b4f0ea)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81b5bcab)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb269a)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81be3f69)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81bf129d)
Location: include/linux/skbuff.h:2743
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c55324)
Location: include/linux/skbuff.h:2743
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
In drivers/net/tun.c (ffffffff81a60b2b)
Location: include/linux/skbuff.h:3112
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81bfe985)
Location: include/linux/skbuff.h:3112
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/filter.c (ffffffff81c3ca9f)
Location: include/linux/skbuff.h:3112
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81cdca43)
Location: include/linux/skbuff.h:3112
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45e65)
Location: include/linux/skbuff.h:3112
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81d7af09)
Location: include/linux/skbuff.h:3112
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81d89a9d)
Location: include/linux/skbuff.h:3112
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df4ab3)
Location: include/linux/skbuff.h:3112
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
In drivers/net/tun.c (ffffffff81bed111)
Location: include/linux/skbuff.h:3006
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81dad3b5)
Location: include/linux/skbuff.h:3006
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/filter.c (ffffffff81dfa498)
Location: include/linux/skbuff.h:3006
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81e9d4a3)
Location: include/linux/skbuff.h:3006
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f22c)
Location: include/linux/skbuff.h:3006
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81f48176)
Location: include/linux/skbuff.h:3006
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81f57949)
Location: include/linux/skbuff.h:3006
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc9d43)
Location: include/linux/skbuff.h:3006
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
In drivers/net/tun.c (ffffffff81c4560a)
Location: include/linux/skbuff.h:3060
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81e1d2b5)
Location: include/linux/skbuff.h:3060
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81e6b845)
Location: include/linux/skbuff.h:3060
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81efaa5b)
Location: include/linux/skbuff.h:3060
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6ef2a)
Location: include/linux/skbuff.h:3060
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81fa7c76)
Location: include/linux/skbuff.h:3060
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81fb7437)
Location: include/linux/skbuff.h:3060
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202a678)
Location: include/linux/skbuff.h:3060
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
In drivers/net/tun.c (ffffffff81cfaf37)
Location: include/linux/skbuff.h:3067
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81eda9a5)
Location: include/linux/skbuff.h:3067
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81f2a9f5)
Location: include/linux/skbuff.h:3067
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81fbe9aa)
Location: include/linux/skbuff.h:3067
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8203565c)
Location: include/linux/skbuff.h:3067
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff82074f36)
Location: include/linux/skbuff.h:3067
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff82084bcb)
Location: include/linux/skbuff.h:3067
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fa163)
Location: include/linux/skbuff.h:3067
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
In drivers/net/tun.c (ffff8000109df130)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffff800010bba8b4)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/filter.c (ffff800010bfd074)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffff800010c65208)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffff800010c74fbc)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv6/ip6_output.c (ffff800010cf9a2c)
Location: include/linux/skbuff.h:2649
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d5b99c)
Location: include/linux/skbuff.h:2649
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
In drivers/net/tun.c (c0ac2d34)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (c0cd7058)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/filter.c (c0d17674)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (c0d74e14)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (c0d8366c)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv6/ip6_output.c (c0e012d0)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
```
```
In net/packet/af_packet.c (c0e5b9dc)
Location: include/linux/skbuff.h:2649
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
In drivers/net/tun.c (c000000000aa0b3c)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (c000000000c9351c)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/filter.c (c000000000ce5470)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (c000000000d69618)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (c000000000d7bddc)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv6/ip6_output.c (c000000000e2180c)
Location: include/linux/skbuff.h:2649
Inline: True
```
```
In net/packet/af_packet.c (c000000000e95f9c)
Location: include/linux/skbuff.h:2649
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
In drivers/net/tun.c (ffffffe000628362)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffe000749aec)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/filter.c (ffffffe00077faae)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffe0007cca8e)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffe0007d8342)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffe0008456e4)
Location: include/linux/skbuff.h:2649
Inline: True
```
```
In net/packet/af_packet.c (ffffffe0008929a8)
Location: include/linux/skbuff.h:2649
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
In drivers/net/tun.c (ffffffff81788147)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818bfe0b)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff818fbcc4)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff8195484f)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81962503)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff819d9131)
Location: include/linux/skbuff.h:2649
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2db6f)
Location: include/linux/skbuff.h:2649
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
In drivers/net/tun.c (ffffffff81767a97)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81879d4b)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff818b5af4)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff8190e33f)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8191bff3)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81995ef1)
Location: include/linux/skbuff.h:2649
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819ead5f)
Location: include/linux/skbuff.h:2649
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
In drivers/net/tun.c (ffffffff817b8332)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81910e0b)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff8194ccf4)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff81999b3e)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
```
```
In net/ipv4/ip_output.c (ffffffff819bf01f)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819cccd3)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81a43bb1)
Location: include/linux/skbuff.h:2649
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a9971f)
Location: include/linux/skbuff.h:2649
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
In drivers/net/tun.c (ffffffff817d0637)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81931f6b)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff8196e6b4)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff819c89a2)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819d6863)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81a4f851)
Location: include/linux/skbuff.h:2649
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa452c)
Location: include/linux/skbuff.h:2649
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
```
</details>
</li>
</ul>

## Differences

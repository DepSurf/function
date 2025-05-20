# Function: <code>skb_set_tail_pointer</code>

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
In net/core/skbuff.c (ffffffff81705e77)
Location: include/linux/skbuff.h:1776
Inline: True
Inline callers:
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_segment
```
```
In net/core/filter.c (ffffffff81730aff)
Location: include/linux/skbuff.h:1776
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter
```
```
In net/ipv4/ip_input.c (ffffffff81759184)
Location: include/linux/skbuff.h:1776
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81759eca)
Location: include/linux/skbuff.h:1776
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8175d998)
Location: include/linux/skbuff.h:1776
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81769c43)
Location: include/linux/skbuff.h:1776
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8178a46e)
Location: include/linux/skbuff.h:1776
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff817c6201)
Location: include/linux/skbuff.h:1776
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff817c8eaa)
Location: include/linux/skbuff.h:1776
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff817e4b1f)
Location: include/linux/skbuff.h:1776
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff817ee7f1)
Location: include/linux/skbuff.h:1776
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff817f2f7d)
Location: include/linux/skbuff.h:1776
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
```
In net/packet/af_packet.c (ffffffff81808d79)
Location: include/linux/skbuff.h:1776
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
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff8179b7ab)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_input.c (ffffffff817c5543)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817c62b3)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff817cb161)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff817d6488)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/udp.c (ffffffff817f7b84)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff818332b5)
Location: include/linux/skbuff.h:1877
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81836122)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff818529b8)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff8185d033)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81861dcd)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
```
In net/packet/af_packet.c (ffffffff8187a1de)
Location: include/linux/skbuff.h:1877
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
Location: include/linux/skbuff.h:1892
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff817cb609)
Location: include/linux/skbuff.h:1892
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/ipv4/ip_input.c (ffffffff817f5041)
Location: include/linux/skbuff.h:1892
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817f5db3)
Location: include/linux/skbuff.h:1892
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff817fadb6)
Location: include/linux/skbuff.h:1892
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81806462)
Location: include/linux/skbuff.h:1892
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81828a6c)
Location: include/linux/skbuff.h:1892
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81864d7f)
Location: include/linux/skbuff.h:1892
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81867c30)
Location: include/linux/skbuff.h:1892
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff818846b8)
Location: include/linux/skbuff.h:1892
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff8188ef8f)
Location: include/linux/skbuff.h:1892
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81893d3d)
Location: include/linux/skbuff.h:1892
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
```
In net/packet/af_packet.c (ffffffff818aea4e)
Location: include/linux/skbuff.h:1892
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
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff817eae39)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/ipv4/ip_input.c (ffffffff818154d0)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81816388)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8181b193)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81826b19)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81849d6a)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81888765)
Location: include/linux/skbuff.h:1885
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff8188c449)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff818aaa6e)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff818b5556)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818ba2a7)
Location: include/linux/skbuff.h:1885
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
```
In net/packet/af_packet.c (ffffffff818d3799)
Location: include/linux/skbuff.h:1885
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
In drivers/net/tun.c (ffffffff816ff2b4)
Location: include/linux/skbuff.h:1972
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81837ef9)
Location: include/linux/skbuff.h:1972
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/filter.c (ffffffff81867918)
Location: include/linux/skbuff.h:1972
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/ipv4/ip_input.c (ffffffff8189469c)
Location: include/linux/skbuff.h:1972
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81895541)
Location: include/linux/skbuff.h:1972
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8189a156)
Location: include/linux/skbuff.h:1972
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818a4a69)
Location: include/linux/skbuff.h:1972
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/udp.c (ffffffff818c987d)
Location: include/linux/skbuff.h:1972
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff8190a83c)
Location: include/linux/skbuff.h:1972
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff8190d74c)
Location: include/linux/skbuff.h:1972
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff8192d58b)
Location: include/linux/skbuff.h:1972
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff819382cc)
Location: include/linux/skbuff.h:1972
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193d290)
Location: include/linux/skbuff.h:1972
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
```
In net/packet/af_packet.c (ffffffff8195890b)
Location: include/linux/skbuff.h:1972
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
In drivers/net/tun.c (ffffffff8173ea0c)
Location: include/linux/skbuff.h:1983
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818825de)
Location: include/linux/skbuff.h:1983
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/dev.c (ffffffff81894a41)
Location: include/linux/skbuff.h:1983
Inline: True
```
```
In net/core/filter.c (ffffffff818b592a)
Location: include/linux/skbuff.h:1983
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_grow_rcsum
```
```
In net/ipv4/ip_output.c (ffffffff818ee620)
Location: include/linux/skbuff.h:1983
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818fab1d)
Location: include/linux/skbuff.h:1983
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81961f20)
Location: include/linux/skbuff.h:1983
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819b237d)
Location: include/linux/skbuff.h:1983
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
In drivers/net/tun.c (ffffffff8176266e)
Location: include/linux/skbuff.h:2061
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818a3095)
Location: include/linux/skbuff.h:2061
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/dev.c (ffffffff818b54c2)
Location: include/linux/skbuff.h:2061
Inline: True
```
```
In net/core/filter.c (ffffffff818dc49b)
Location: include/linux/skbuff.h:2061
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff8191bdd4)
Location: include/linux/skbuff.h:2061
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819289d6)
Location: include/linux/skbuff.h:2061
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff819969a3)
Location: include/linux/skbuff.h:2061
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e927c)
Location: include/linux/skbuff.h:2061
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
In drivers/net/tun.c (ffffffff817a03b6)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818edd25)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/dev.c (ffffffff818fac43)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (ffffffff819296ac)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff8197e0e2)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8198b419)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv6/ip6_output.c (ffffffff81a02ee6)
Location: include/linux/skbuff.h:2149
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a5775e)
Location: include/linux/skbuff.h:2149
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
In drivers/net/tun.c (ffffffff817c5367)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8191fe20)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/dev.c (ffffffff8192cd67)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (ffffffff8195bd06)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_grow_rcsum
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff819b49f9)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819c26bf)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81a39abb)
Location: include/linux/skbuff.h:2163
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a8e4f4)
Location: include/linux/skbuff.h:2163
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
In drivers/net/tun.c (ffffffff8188b54f)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff819f33fb)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/dev.c (ffffffff81a068be)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (ffffffff81a2ee63)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_grow_rcsum
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81a9ec5e)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aad8e8)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/xfrm/espintcp.c (ffffffff81b229ae)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f289)
Location: include/linux/skbuff.h:2186
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b8b2f4)
Location: include/linux/skbuff.h:2186
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
In drivers/net/tun.c (ffffffff818996f3)
Location: include/linux/skbuff.h:2207
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff819f342b)
Location: include/linux/skbuff.h:2207
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/dev.c (ffffffff81a07ea8)
Location: include/linux/skbuff.h:2207
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (ffffffff81a30979)
Location: include/linux/skbuff.h:2207
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_grow_rcsum
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81aa8b9a)
Location: include/linux/skbuff.h:2207
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ab4ccc)
Location: include/linux/skbuff.h:2207
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06a89)
Location: include/linux/skbuff.h:2207
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81b3165e)
Location: include/linux/skbuff.h:2207
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b3dcd9)
Location: include/linux/skbuff.h:2207
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b9a2c4)
Location: include/linux/skbuff.h:2207
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
In drivers/net/tun.c (ffffffff8187bb63)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff819d968b)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/dev.c (ffffffff819ea819)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (ffffffff81a1418f)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81a93cb6)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81a9ff17)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af2198)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81b1f371)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b194)
Location: include/linux/skbuff.h:2223
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b8921e)
Location: include/linux/skbuff.h:2223
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
In drivers/net/tun.c (ffffffff8190d093)
Location: include/linux/skbuff.h:2252
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81a8964b)
Location: include/linux/skbuff.h:2252
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/dev.c (ffffffff81aa1cef)
Location: include/linux/skbuff.h:2252
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81ac5a5f)
Location: include/linux/skbuff.h:2252
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81b4f0ff)
Location: include/linux/skbuff.h:2252
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81b5bcd0)
Location: include/linux/skbuff.h:2252
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb26a8)
Location: include/linux/skbuff.h:2252
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81be3f79)
Location: include/linux/skbuff.h:2252
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81bf12b7)
Location: include/linux/skbuff.h:2252
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c55336)
Location: include/linux/skbuff.h:2252
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
In drivers/net/tun.c (ffffffff81a62a85)
Location: include/linux/skbuff.h:2603
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81bfe997)
Location: include/linux/skbuff.h:2603
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/dev.c (ffffffff81c19ecc)
Location: include/linux/skbuff.h:2603
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81c3cab0)
Location: include/linux/skbuff.h:2603
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81cdca55)
Location: include/linux/skbuff.h:2603
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45e79)
Location: include/linux/skbuff.h:2603
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81d7af16)
Location: include/linux/skbuff.h:2603
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81d89aba)
Location: include/linux/skbuff.h:2603
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df4ac5)
Location: include/linux/skbuff.h:2603
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
In drivers/net/tun.c (ffffffff81beef4e)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81dad3c7)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/dev.c (ffffffff81dcaf4c)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81dfa4a9)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81e9d4b5)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f240)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81f48183)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81f57966)
Location: include/linux/skbuff.h:2500
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc9d55)
Location: include/linux/skbuff.h:2500
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
In drivers/net/tun.c (ffffffff81c46fdd)
Location: include/linux/skbuff.h:2543
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81e1d2c7)
Location: include/linux/skbuff.h:2543
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/dev.c (ffffffff81e3bad8)
Location: include/linux/skbuff.h:2543
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81e6b857)
Location: include/linux/skbuff.h:2543
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81efaa75)
Location: include/linux/skbuff.h:2543
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6ef38)
Location: include/linux/skbuff.h:2543
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81fa7c83)
Location: include/linux/skbuff.h:2543
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81fb7451)
Location: include/linux/skbuff.h:2543
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202a68d)
Location: include/linux/skbuff.h:2543
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
In drivers/net/tun.c (ffffffff81cfc8f9)
Location: include/linux/skbuff.h:2550
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81eda9b7)
Location: include/linux/skbuff.h:2550
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/dev.c (ffffffff81efa018)
Location: include/linux/skbuff.h:2550
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81f2aa07)
Location: include/linux/skbuff.h:2550
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81fbe9c4)
Location: include/linux/skbuff.h:2550
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8203566a)
Location: include/linux/skbuff.h:2550
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff82074f43)
Location: include/linux/skbuff.h:2550
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff82084be8)
Location: include/linux/skbuff.h:2550
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fa178)
Location: include/linux/skbuff.h:2550
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
In drivers/net/tun.c (ffff8000109e05d0)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffff800010bba8bc)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/dev.c (ffff800010bcf650)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (ffff800010bfd084)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffff800010c65210)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffff800010c74fdc)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv6/ip6_output.c (ffff800010cf9a40)
Location: include/linux/skbuff.h:2163
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d5b9a4)
Location: include/linux/skbuff.h:2163
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
In drivers/net/tun.c (c0ac4740)
Location: include/linux/skbuff.h:2180
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (c0cd7064)
Location: include/linux/skbuff.h:2180
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/dev.c (c0ce5a24)
Location: include/linux/skbuff.h:2180
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (c0d17688)
Location: include/linux/skbuff.h:2180
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (c0d74e20)
Location: include/linux/skbuff.h:2180
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (c0d83694)
Location: include/linux/skbuff.h:2180
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv6/ip6_output.c (c0e012dc)
Location: include/linux/skbuff.h:2180
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
```
```
In net/packet/af_packet.c (c0e5b9e4)
Location: include/linux/skbuff.h:2180
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
In drivers/net/tun.c (c000000000aa19c0)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (c000000000c93528)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/dev.c (c000000000ca6488)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (c000000000ce5494)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (c000000000d69624)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (c000000000d7be10)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv6/ip6_output.c (c000000000e21834)
Location: include/linux/skbuff.h:2163
Inline: True
```
```
In net/packet/af_packet.c (c000000000e95fa8)
Location: include/linux/skbuff.h:2163
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
In drivers/net/tun.c (ffffffe00062a49a)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffe000749aec)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_trim
```
```
In net/core/dev.c (ffffffe000755b5a)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (ffffffe00077fab4)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffe0007cca8e)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffe0007d8356)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffe0008456f0)
Location: include/linux/skbuff.h:2163
Inline: True
```
```
In net/packet/af_packet.c (ffffffe0008929a8)
Location: include/linux/skbuff.h:2163
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
In drivers/net/tun.c (ffffffff81789e47)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818bfe20)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/dev.c (ffffffff818ccd67)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (ffffffff818fbcd6)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_grow_rcsum
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81954869)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8196252f)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff819d914b)
Location: include/linux/skbuff.h:2163
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2db84)
Location: include/linux/skbuff.h:2163
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
In drivers/net/tun.c (ffffffff81769797)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81879d60)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/dev.c (ffffffff81886df7)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (ffffffff818b5b06)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_grow_rcsum
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff8190e359)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8191c01f)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81995f0b)
Location: include/linux/skbuff.h:2163
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819ead74)
Location: include/linux/skbuff.h:2163
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
In drivers/net/tun.c (ffffffff817ba1e7)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81910e20)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/dev.c (ffffffff8191dd67)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (ffffffff8194cd06)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_grow_rcsum
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff81999b50)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
```
```
In net/ipv4/ip_output.c (ffffffff819bf039)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819cccff)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81a43bcb)
Location: include/linux/skbuff.h:2163
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a99734)
Location: include/linux/skbuff.h:2163
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
In drivers/net/tun.c (ffffffff817d26e7)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81931f80)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/dev.c (ffffffff8193f3d7)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/filter.c (ffffffff8196e6c6)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_grow_rcsum
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff819c89bc)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819d688f)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81a4f86b)
Location: include/linux/skbuff.h:2163
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa453e)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
```
</details>
</li>
</ul>

## Differences

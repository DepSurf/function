# Function: <code>pskb_trim</code>

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
In net/core/skbuff.c (ffffffff81708db8)
Location: include/linux/skbuff.h:2183
Inline: True
Inline callers:
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_segment
```
```
In net/core/filter.c (ffffffff81730acf)
Location: include/linux/skbuff.h:2183
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter
```
```
In net/ipv4/ip_output.c (ffffffff8175dc78)
Location: include/linux/skbuff.h:2183
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv6/ip6_output.c (ffffffff817c651d)
Location: include/linux/skbuff.h:2183
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81808b9f)
Location: include/linux/skbuff.h:2183
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
In net/core/skbuff.c (ffffffff8177084a)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff8179b795)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff817cb144)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv6/ip6_output.c (ffffffff81833608)
Location: include/linux/skbuff.h:2318
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8187a1c8)
Location: include/linux/skbuff.h:2318
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
In net/core/skbuff.c (ffffffff8179d9ba)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff817ca944)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817fad99)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv6/ip6_output.c (ffffffff81865098)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818aea38)
Location: include/linux/skbuff.h:2340
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
In net/core/skbuff.c (ffffffff817be76a)
Location: include/linux/skbuff.h:2389
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff817e9b12)
Location: include/linux/skbuff.h:2389
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8181b173)
Location: include/linux/skbuff.h:2389
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv6/ip6_output.c (ffffffff8188884a)
Location: include/linux/skbuff.h:2389
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d3784)
Location: include/linux/skbuff.h:2389
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
In net/core/skbuff.c (ffffffff81837eda)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81865187)
Location: include/linux/skbuff.h:2476
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8189a13a)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv6/ip6_output.c (ffffffff8190ab8d)
Location: include/linux/skbuff.h:2476
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819586cd)
Location: include/linux/skbuff.h:2476
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
In drivers/net/tun.c (ffffffff8173d677)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818825aa)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff818b2ca9)
Location: include/linux/skbuff.h:2488
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff818ee5ee)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv6/ip6_output.c (ffffffff81961fe8)
Location: include/linux/skbuff.h:2488
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819b2114)
Location: include/linux/skbuff.h:2488
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
In drivers/net/tun.c (ffffffff8176105a)
Location: include/linux/skbuff.h:2564
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818a306a)
Location: include/linux/skbuff.h:2564
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff818d5bd2)
Location: include/linux/skbuff.h:2564
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff8191bdaf)
Location: include/linux/skbuff.h:2564
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv6/ip6_output.c (ffffffff81996a0e)
Location: include/linux/skbuff.h:2564
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e903b)
Location: include/linux/skbuff.h:2564
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
In drivers/net/tun.c (ffffffff8179ecdb)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818edcfb)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81923378)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff8197e0b0)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8198a833)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv6/ip6_output.c (ffffffff81a02f57)
Location: include/linux/skbuff.h:2650
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a574ae)
Location: include/linux/skbuff.h:2650
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
In drivers/net/tun.c (ffffffff817c349e)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8191fdfb)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81955635)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff819b49cb)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819c11b1)
Location: include/linux/skbuff.h:2664
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a39b2c)
Location: include/linux/skbuff.h:2664
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a8e4ce)
Location: include/linux/skbuff.h:2664
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
In drivers/net/tun.c (ffffffff8188e772)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff819f33d6)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81a2bb30)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81a9ec2c)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aac8e1)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/xfrm/espintcp.c (ffffffff81b228eb)
Location: include/linux/skbuff.h:2687
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f2f0)
Location: include/linux/skbuff.h:2687
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b8b06a)
Location: include/linux/skbuff.h:2687
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
In drivers/net/tun.c (ffffffff8189d0dc)
Location: include/linux/skbuff.h:2713
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff819f3406)
Location: include/linux/skbuff.h:2713
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81a2d0cf)
Location: include/linux/skbuff.h:2713
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81aa8b6a)
Location: include/linux/skbuff.h:2713
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ab4237)
Location: include/linux/skbuff.h:2713
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b068b9)
Location: include/linux/skbuff.h:2713
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81b3159b)
Location: include/linux/skbuff.h:2713
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b3dd3d)
Location: include/linux/skbuff.h:2713
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b9a089)
Location: include/linux/skbuff.h:2713
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
In drivers/net/tun.c (ffffffff8187f90c)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff819d9666)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81a14166)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81a93c86)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81a9f3a7)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af1fcc)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81b1f211)
Location: include/linux/skbuff.h:2729
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b1f8)
Location: include/linux/skbuff.h:2729
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b88ffb)
Location: include/linux/skbuff.h:2729
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
In drivers/net/tun.c (ffffffff81910a95)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81a89626)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81ac5a36)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81b4f0cf)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81b5b157)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb24dc)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81be3d51)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81bf131b)
Location: include/linux/skbuff.h:2758
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c5510b)
Location: include/linux/skbuff.h:2758
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
In drivers/net/tun.c (ffffffff81a6086a)
Location: include/linux/skbuff.h:3127
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81bfe959)
Location: include/linux/skbuff.h:3127
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81c3ca05)
Location: include/linux/skbuff.h:3127
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81cdca2a)
Location: include/linux/skbuff.h:3127
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45ca4)
Location: include/linux/skbuff.h:3127
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81d7adad)
Location: include/linux/skbuff.h:3127
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81d89b38)
Location: include/linux/skbuff.h:3127
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df4840)
Location: include/linux/skbuff.h:3127
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
In drivers/net/tun.c (ffffffff81bece2b)
Location: include/linux/skbuff.h:3021
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81dad389)
Location: include/linux/skbuff.h:3021
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81dfa437)
Location: include/linux/skbuff.h:3021
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81e9d48a)
Location: include/linux/skbuff.h:3021
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f06b)
Location: include/linux/skbuff.h:3021
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81f480cd)
Location: include/linux/skbuff.h:3021
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81f579ee)
Location: include/linux/skbuff.h:3021
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc9ad0)
Location: include/linux/skbuff.h:3021
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
In drivers/net/tun.c (ffffffff81c4532c)
Location: include/linux/skbuff.h:3075
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81e1d289)
Location: include/linux/skbuff.h:3075
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81e6b7e8)
Location: include/linux/skbuff.h:3075
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81efa9d4)
Location: include/linux/skbuff.h:3075
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6ed69)
Location: include/linux/skbuff.h:3075
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff81fa7bcd)
Location: include/linux/skbuff.h:3075
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81fb74b8)
Location: include/linux/skbuff.h:3075
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202a3fa)
Location: include/linux/skbuff.h:3075
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
In drivers/net/tun.c (ffffffff81cfac5c)
Location: include/linux/skbuff.h:3082
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81eda979)
Location: include/linux/skbuff.h:3082
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81f2a998)
Location: include/linux/skbuff.h:3082
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81fbe921)
Location: include/linux/skbuff.h:3082
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035489)
Location: include/linux/skbuff.h:3082
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/xfrm/espintcp.c (ffffffff82074e8d)
Location: include/linux/skbuff.h:3082
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff82084b15)
Location: include/linux/skbuff.h:3082
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820f9efc)
Location: include/linux/skbuff.h:3082
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
In drivers/net/tun.c (ffff8000109dee8c)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffff800010bba88c)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffff800010c02094)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffff800010c651f8)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffff800010c73f58)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv6/ip6_output.c (ffff800010cf99a8)
Location: include/linux/skbuff.h:2664
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d5b698)
Location: include/linux/skbuff.h:2664
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
In drivers/net/tun.c (c0ac2a90)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (c0cd7038)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (c0d104e0)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (c0d74e04)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (c0d82594)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv6/ip6_output.c (c0e012c0)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
```
```
In net/packet/af_packet.c (c0e5b7ac)
Location: include/linux/skbuff.h:2664
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
In drivers/net/tun.c (c000000000aa07d0)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (c000000000c934e4)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (c000000000cdce6c)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (c000000000d69608)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (c000000000d7aecc)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv6/ip6_output.c (c000000000e218b4)
Location: include/linux/skbuff.h:2664
Inline: True
```
```
In net/packet/af_packet.c (c000000000e95c3c)
Location: include/linux/skbuff.h:2664
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
In drivers/net/tun.c (ffffffe0006280f8)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffe000749acc)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffe0007785d2)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffe0007cca72)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffe0007d7522)
Location: include/linux/skbuff.h:2664
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffe000845742)
Location: include/linux/skbuff.h:2664
Inline: True
```
```
In net/packet/af_packet.c (ffffffe0008927fe)
Location: include/linux/skbuff.h:2664
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
In drivers/net/tun.c (ffffffff81787f6e)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818bfdfb)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff818f5605)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff8195483b)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81961021)
Location: include/linux/skbuff.h:2664
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819d91bc)
Location: include/linux/skbuff.h:2664
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2db5e)
Location: include/linux/skbuff.h:2664
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
In drivers/net/tun.c (ffffffff817678be)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81879d3b)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff818af435)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff8190e32b)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8191ab11)
Location: include/linux/skbuff.h:2664
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81995f7c)
Location: include/linux/skbuff.h:2664
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819ead4e)
Location: include/linux/skbuff.h:2664
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
In drivers/net/tun.c (ffffffff817b831e)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81910dfb)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81946635)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff81999b31)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
```
```
In net/ipv4/ip_output.c (ffffffff819bf00b)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819cb7f1)
Location: include/linux/skbuff.h:2664
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a43c3c)
Location: include/linux/skbuff.h:2664
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a9970e)
Location: include/linux/skbuff.h:2664
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
In drivers/net/tun.c (ffffffff817d0623)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81931f5b)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/filter.c (ffffffff81967f3e)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff819c898e)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819d5381)
Location: include/linux/skbuff.h:2664
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a4f8dc)
Location: include/linux/skbuff.h:2664
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa451c)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
```
</details>
</li>
</ul>

## Differences

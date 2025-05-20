# Function: <code>___pskb_trim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81708b20)
Location: net/core/skbuff.c:1491
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/filter.c:sk_filter
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff81708b20-ffffffff81708e0b: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817704d0)
Location: net/core/skbuff.c:1496
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff817704d0-ffffffff81770810: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179d640)
Location: net/core/skbuff.c:1496
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff8179d640-ffffffff8179d980: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817be270)
Location: net/core/skbuff.c:1509
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff817be270-ffffffff817be591: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81837980)
Location: net/core/skbuff.c:1754
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff81837980-ffffffff81837ce2: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81881e50)
Location: net/core/skbuff.c:1756
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/ipv4/ip_output.c:ip_append_page
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff81881e50-ffffffff818821ce: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818a2950)
Location: net/core/skbuff.c:1766
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_append_page
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff818a2950-ffffffff818a2ca3: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818ed5a0)
Location: net/core/skbuff.c:1925
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff818ed5a0-ffffffff818ed8f6: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191f6a0)
Location: net/core/skbuff.c:1925
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_append_page
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff8191f6a0-ffffffff8191f9f6: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f2c20)
Location: net/core/skbuff.c:1924
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff819f2c20-ffffffff819f2f6a: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f2c00)
Location: net/core/skbuff.c:1935
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff819f2c00-ffffffff819f2f47: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d8e40)
Location: net/core/skbuff.c:1977
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff819d8e40-ffffffff819d9187: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a88de0)
Location: net/core/skbuff.c:2049
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff81a88de0-ffffffff81a8914f: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfe140)
Location: net/core/skbuff.c:2098
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff81bfe140-ffffffff81bfe4f4: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81dacae0)
Location: net/core/skbuff.c:2301
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff81dacae0-ffffffff81daced3: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1c910)
Location: net/core/skbuff.c:2465
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff81e1c910-ffffffff81e1cdd2: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81eda010)
Location: net/core/skbuff.c:2553
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff81eda010-ffffffff81eda4cf: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bba0c0)
Location: net/core/skbuff.c:1925
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffff800010bba0c0-ffff800010bba420: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd6964)
Location: net/core/skbuff.c:1925
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
c0cd6964-c0cd6c48: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c92a30)
Location: net/core/skbuff.c:1925
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
c000000000c92a30-c000000000c92ea8: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000749482)
Location: net/core/skbuff.c:1925
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_append_page
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffe000749482-ffffffe000749734: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bf6a0)
Location: net/core/skbuff.c:1925
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_append_page
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff818bf6a0-ffffffff818bf9f6: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818795e0)
Location: net/core/skbuff.c:1925
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_append_page
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff818795e0-ffffffff81879936: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819106a0)
Location: net/core/skbuff.c:1925
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
  - net/ipv4/ip_output.c:ip_append_page
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff819106a0-ffffffff819109f6: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81931800)
Location: net/core/skbuff.c:1925
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_append_page
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff81931800-ffffffff81931b56: ___pskb_trim (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

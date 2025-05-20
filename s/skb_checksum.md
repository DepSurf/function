# Function: <code>skb_checksum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81707ab0)
Location: net/core/skbuff.c:2176
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
Direct callers:
  - net/core/datagram.c:__skb_checksum_complete_head
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff81707ab0-ffffffff81707afb: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81772d9f)
Location: net/core/skbuff.c:2174
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
Direct callers:
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
**Symbols:**

```
ffffffff8176de50-ffffffff8176de9b: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179ff50)
Location: net/core/skbuff.c:2150
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
Direct callers:
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
**Symbols:**

```
ffffffff8179b290-ffffffff8179b2db: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817be941)
Location: net/core/skbuff.c:2164
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
Direct callers:
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
**Symbols:**

```
ffffffff817b7db0-ffffffff817b7dfb: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81838288)
Location: net/core/skbuff.c:2532
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
Direct callers:
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
**Symbols:**

```
ffffffff81830510-ffffffff8183055b: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81882b57)
Location: net/core/skbuff.c:2548
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
**Symbols:**

```
ffffffff8187a9e0-ffffffff8187aa2b: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818a35c2)
Location: net/core/skbuff.c:2544
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff8189b5e0-ffffffff8189b62b: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818ee2f3)
Location: net/core/skbuff.c:2710
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff818e6100-ffffffff818e614b: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819203e7)
Location: net/core/skbuff.c:2712
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81918270-ffffffff819182bb: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f3a03)
Location: net/core/skbuff.c:2711
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff819eb3e0-ffffffff819eb42b: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f3a2a)
Location: net/core/skbuff.c:2728
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884_validate
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff819eb100-ffffffff819eb14b: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d9c18)
Location: net/core/skbuff.c:2811
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff819d1610-ffffffff819d165b: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a89c0d)
Location: net/core/skbuff.c:2883
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/mptcp/protocol.c:mptcp_update_data_checksum
  - net/mptcp/subflow.c:validate_data_csum
```
**Symbols:**

```
ffffffff81a810d0-ffffffff81a8111b: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfef94)
Location: net/core/skbuff.c:2932
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/gro.c:__skb_gro_checksum_complete
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/mptcp/protocol.c:mptcp_update_data_checksum
  - net/mptcp/subflow.c:validate_data_csum
```
**Symbols:**

```
ffffffff81bf5bb0-ffffffff81bf5c0a: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81dada7f)
Location: net/core/skbuff.c:3138
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/gro.c:__skb_gro_checksum_complete
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/mptcp/protocol.c:mptcp_update_data_checksum
  - net/mptcp/subflow.c:validate_data_csum
```
**Symbols:**

```
ffffffff81da3df0-ffffffff81da3e4a: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1da0c)
Location: net/core/skbuff.c:3308
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/gro.c:__skb_gro_checksum_complete
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/mptcp/protocol.c:mptcp_update_data_checksum
  - net/mptcp/subflow.c:validate_data_csum
```
**Symbols:**

```
ffffffff81e12a60-ffffffff81e12aba: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81edb116)
Location: net/core/skbuff.c:3396
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/gro.c:__skb_gro_checksum_complete
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/mptcp/protocol.c:mptcp_update_data_checksum
  - net/mptcp/subflow.c:validate_data_csum
```
**Symbols:**

```
ffffffff81ecfc20-ffffffff81ecfc7a: skb_checksum (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bbadc0)
Location: net/core/skbuff.c:2712
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffff800010bb1298-ffff800010bb1328: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd75e8)
Location: net/core/skbuff.c:2712
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
c0cced98-c0ccee14: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c93b78)
Location: net/core/skbuff.c:2712
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
c000000000c88790-c000000000c88804: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000749f58)
Location: net/core/skbuff.c:2712
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffe000742ce6-ffffffe000742d46: skb_checksum (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818c03e7)
Location: net/core/skbuff.c:2712
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff818b8270-ffffffff818b82bb: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187a327)
Location: net/core/skbuff.c:2712
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff818721c0-ffffffff8187220b: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819113e7)
Location: net/core/skbuff.c:2712
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81909270-ffffffff819092bb: skb_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
__wsum skb_checksum(const struct sk_buff *skb, int offset, int len, __wsum csum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81932547)
Location: net/core/skbuff.c:2712
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:pskb_trim_rcsum_slow
Direct callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff8192a340-ffffffff8192a38b: skb_checksum (STB_GLOBAL)
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

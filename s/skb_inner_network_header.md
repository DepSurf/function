# Function: <code>skb_inner_network_header</code>

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
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:1958
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/skbuff.h:1958
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:1958
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff817b03ca)
Location: include/linux/skbuff.h:1958
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (ffffffff817fd24a)
Location: include/linux/skbuff.h:1958
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff81784cce)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_csum_offload_chk
```
```
In net/ipv4/udp_offload.c (ffffffff817f8755)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81812438)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81812ab3)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff8181d31a)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (ffffffff8186cb7a)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff817b2300)
Location: include/linux/skbuff.h:2105
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff81829606)
Location: include/linux/skbuff.h:2105
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81843948)
Location: include/linux/skbuff.h:2105
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81843fba)
Location: include/linux/skbuff.h:2105
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff8184ebca)
Location: include/linux/skbuff.h:2105
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (ffffffff8189f96a)
Location: include/linux/skbuff.h:2105
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff817cfb26)
Location: include/linux/skbuff.h:2144
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff8184a614)
Location: include/linux/skbuff.h:2144
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818651a8)
Location: include/linux/skbuff.h:2144
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81865835)
Location: include/linux/skbuff.h:2144
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff8187276d)
Location: include/linux/skbuff.h:2144
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (ffffffff818c5eae)
Location: include/linux/skbuff.h:2144
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff81849476)
Location: include/linux/skbuff.h:2231
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff818ca2b9)
Location: include/linux/skbuff.h:2231
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e5308)
Location: include/linux/skbuff.h:2231
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff818e5985)
Location: include/linux/skbuff.h:2231
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff818f316d)
Location: include/linux/skbuff.h:2231
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (ffffffff8194923e)
Location: include/linux/skbuff.h:2231
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff81893436)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff81920610)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193bb95)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff8193c26b)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81949a5c)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (ffffffff819a2326)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff818b3e66)
Location: include/linux/skbuff.h:2320
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff8194f446)
Location: include/linux/skbuff.h:2320
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196b9f5)
Location: include/linux/skbuff.h:2320
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff8196bf6f)
Location: include/linux/skbuff.h:2320
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b71c)
Location: include/linux/skbuff.h:2320
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (ffffffff819d8f96)
Location: include/linux/skbuff.h:2320
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff81900809)
Location: include/linux/skbuff.h:2408
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff819b3c7c)
Location: include/linux/skbuff.h:2408
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d275f)
Location: include/linux/skbuff.h:2408
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff819d2cbe)
Location: include/linux/skbuff.h:2408
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e4c5c)
Location: include/linux/skbuff.h:2408
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a47803)
Location: include/linux/skbuff.h:2408
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff81932b39)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff819ea9ac)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a0915f)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81a0982d)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1bc7c)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a7e3b3)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff81a07a94)
Location: include/linux/skbuff.h:2445
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff81ad85c9)
Location: include/linux/skbuff.h:2445
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8bd9)
Location: include/linux/skbuff.h:2445
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81af9f9d)
Location: include/linux/skbuff.h:2445
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b0cb3c)
Location: include/linux/skbuff.h:2445
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b79033)
Location: include/linux/skbuff.h:2445
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff81a09179)
Location: include/linux/skbuff.h:2466
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff81ae4a6a)
Location: include/linux/skbuff.h:2466
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b059a9)
Location: include/linux/skbuff.h:2466
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81b076fd)
Location: include/linux/skbuff.h:2466
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b1ae7c)
Location: include/linux/skbuff.h:2466
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b87fb3)
Location: include/linux/skbuff.h:2466
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff819efadc)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff81acfcbf)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af1229)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81af2e99)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b08b2c)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b76ce3)
Location: include/linux/skbuff.h:2482
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff81aa0efc)
Location: include/linux/skbuff.h:2511
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e6df)
Location: include/linux/skbuff.h:2511
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1439)
Location: include/linux/skbuff.h:2511
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81bb33a9)
Location: include/linux/skbuff.h:2511
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81bcba1c)
Location: include/linux/skbuff.h:2511
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_output.c (ffffffff81be149e)
Location: include/linux/skbuff.h:2511
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c41793)
Location: include/linux/skbuff.h:2511
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff81c18c86)
Location: include/linux/skbuff.h:2879
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff81d1fe7e)
Location: include/linux/skbuff.h:2879
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d44b09)
Location: include/linux/skbuff.h:2879
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81d46bc4)
Location: include/linux/skbuff.h:2879
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81d6153c)
Location: include/linux/skbuff.h:2879
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_output.c (ffffffff81d783c2)
Location: include/linux/skbuff.h:2879
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81ddff83)
Location: include/linux/skbuff.h:2879
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff81dc9c52)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff81ee707e)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0dda9)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81f10414)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81f2be6c)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44d02)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb22b3)
Location: include/linux/skbuff.h:2771
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff81e3a7c2)
Location: include/linux/skbuff.h:2825
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff81f4691e)
Location: include/linux/skbuff.h:2825
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6da59)
Location: include/linux/skbuff.h:2825
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81f70104)
Location: include/linux/skbuff.h:2825
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81f8bb0c)
Location: include/linux/skbuff.h:2825
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa4485)
Location: include/linux/skbuff.h:2825
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff820129c3)
Location: include/linux/skbuff.h:2825
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff81ef8baf)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff8200ca5e)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff820341a9)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff82036834)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff8205340c)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_output.c (ffffffff820717f8)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff820e1b23)
Location: include/linux/skbuff.h:2832
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffff800010bd0a7c)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffff800010ca0548)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc24b0)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffff800010cc2be4)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7f48)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (ffff800010d49808)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (c0ceb62c)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (c0dad780)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (c0dcdd60)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (c0dce404)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (c0de1a24)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (c0e4ab68)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (c000000000caeb74)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (c000000000db2d08)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dddbb4)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (c000000000ddea8c)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (c000000000df8080)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (c000000000e7ee84)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffe00075b148)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffe0007fcbde)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817918)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffe000817fe0)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffe0008284ec)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (ffffffe000882c20)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff818d2b39)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff8198a81c)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8eff)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff819a95cd)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb30c)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a1da43)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff8188c9c9)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff819442dc)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819629bf)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff8196308d)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ip_tunnel.c (ffffffff8196733e)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff819780fc)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (ffffffff819da803)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
```
```
In net/ipv6/ip6_udp_tunnel.c (ffffffff819e5b44)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv6/ip6_udp_tunnel.c:udp_tunnel6_xmit_skb
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
In net/core/dev.c (ffffffff81923b39)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff819f4fec)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1379f)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81a13e6d)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25d8c)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a884c3)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/core/dev.c (ffffffff81944fa9)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/ipv4/udp_offload.c (ffffffff819ff1f3)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e16f)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81a1e85d)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a3123c)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a95113)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
```
</details>
</li>
</ul>

## Differences

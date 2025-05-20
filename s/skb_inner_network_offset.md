# Function: <code>skb_inner_network_offset</code>

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
Location: include/linux/skbuff.h:2103
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/skbuff.h:2103
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:2103
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
In net/ipv4/udp_offload.c (ffffffff817f8755)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81812438)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81812ab3)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff81829606)
Location: include/linux/skbuff.h:2255
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81843948)
Location: include/linux/skbuff.h:2255
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81843fba)
Location: include/linux/skbuff.h:2255
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff8184a614)
Location: include/linux/skbuff.h:2304
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818651a8)
Location: include/linux/skbuff.h:2304
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81865835)
Location: include/linux/skbuff.h:2304
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff818ca2b9)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e5308)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff818e5985)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff81920610)
Location: include/linux/skbuff.h:2403
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193bb95)
Location: include/linux/skbuff.h:2403
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff8193c26b)
Location: include/linux/skbuff.h:2403
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff8194f446)
Location: include/linux/skbuff.h:2481
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196b9f5)
Location: include/linux/skbuff.h:2481
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff8196bf6f)
Location: include/linux/skbuff.h:2481
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff819b3c7c)
Location: include/linux/skbuff.h:2567
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2749)
Location: include/linux/skbuff.h:2567
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff819d2cbe)
Location: include/linux/skbuff.h:2567
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff819ea9ac)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a09149)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81a0982d)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff81ad85c9)
Location: include/linux/skbuff.h:2604
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8bd9)
Location: include/linux/skbuff.h:2604
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81af9f9d)
Location: include/linux/skbuff.h:2604
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff81ae4a6a)
Location: include/linux/skbuff.h:2630
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b059a9)
Location: include/linux/skbuff.h:2630
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81b076fd)
Location: include/linux/skbuff.h:2630
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff81acfcbf)
Location: include/linux/skbuff.h:2646
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af1229)
Location: include/linux/skbuff.h:2646
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81af2e99)
Location: include/linux/skbuff.h:2646
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff81b8e6df)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1439)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81bb33a9)
Location: include/linux/skbuff.h:2675
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff81d1fe7e)
Location: include/linux/skbuff.h:3044
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d44b09)
Location: include/linux/skbuff.h:3044
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81d46bc4)
Location: include/linux/skbuff.h:3044
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff81ee707e)
Location: include/linux/skbuff.h:2938
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0dda9)
Location: include/linux/skbuff.h:2938
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81f10414)
Location: include/linux/skbuff.h:2938
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff81f4691e)
Location: include/linux/skbuff.h:2992
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6da59)
Location: include/linux/skbuff.h:2992
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81f70104)
Location: include/linux/skbuff.h:2992
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff8200ca5e)
Location: include/linux/skbuff.h:2999
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff820341a9)
Location: include/linux/skbuff.h:2999
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff82036834)
Location: include/linux/skbuff.h:2999
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffff800010ca0548)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffff800010cc2be4)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (c0dad780)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (c0dcdd60)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (c0dce404)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (c000000000db2d08)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dddbac)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (c000000000ddea8c)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffe0007fcbde)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe0008178fe)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffe000817fe0)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff8198a81c)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8ee9)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff819a95cd)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff819442dc)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819629a9)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff8196308d)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/ip6_udp_tunnel.c (ffffffff819e5b44)
Location: include/linux/skbuff.h:2581
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
In net/ipv4/udp_offload.c (ffffffff819f4fec)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13789)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81a13e6d)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff819ff1f3)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e159)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81a1e85d)
Location: include/linux/skbuff.h:2581
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
</details>
</li>
</ul>

## Differences

# Function: <code>gso_make_checksum</code>

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
In net/ipv4/tcp_offload.c (ffffffff8178335c)
Location: include/linux/skbuff.h:3485
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8178b1af)
Location: include/linux/skbuff.h:3485
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff817a5292)
Location: include/linux/skbuff.h:3485
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/tcp_offload.c (ffffffff817f09ca)
Location: include/linux/skbuff.h:3706
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff817f8a3f)
Location: include/linux/skbuff.h:3706
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81812c5e)
Location: include/linux/skbuff.h:3706
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
In net/ipv4/tcp_offload.c (ffffffff8182174f)
Location: include/linux/skbuff.h:3758
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8182991b)
Location: include/linux/skbuff.h:3758
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8184416a)
Location: include/linux/skbuff.h:3758
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
In net/ipv4/tcp_offload.c (ffffffff8184242e)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8184a8f8)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8186597b)
Location: include/linux/skbuff.h:3822
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
In net/ipv4/tcp_offload.c (ffffffff818c1cfa)
Location: include/linux/skbuff.h:4013
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff818ca578)
Location: include/linux/skbuff.h:4013
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff818e5abf)
Location: include/linux/skbuff.h:4013
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
In net/ipv4/tcp_offload.c (ffffffff819179ca)
Location: include/linux/skbuff.h:4023
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81920e59)
Location: include/linux/skbuff.h:4023
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8193c415)
Location: include/linux/skbuff.h:4023
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
In net/ipv4/tcp_offload.c (ffffffff81946101)
Location: include/linux/skbuff.h:4186
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8194f9c6)
Location: include/linux/skbuff.h:4186
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8196c10c)
Location: include/linux/skbuff.h:4186
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
In net/ipv4/tcp_offload.c (ffffffff819aa740)
Location: include/linux/skbuff.h:4293
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819b423f)
Location: include/linux/skbuff.h:4293
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff819d2e5d)
Location: include/linux/skbuff.h:4293
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
In net/ipv4/tcp_offload.c (ffffffff819e1416)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819eaf6f)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81a099cf)
Location: include/linux/skbuff.h:4377
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
In net/ipv4/tcp_offload.c (ffffffff81acea56)
Location: include/linux/skbuff.h:4417
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81ad8bee)
Location: include/linux/skbuff.h:4417
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81afa13f)
Location: include/linux/skbuff.h:4417
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
In net/ipv4/tcp_offload.c (ffffffff81adaa76)
Location: include/linux/skbuff.h:4446
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5108)
Location: include/linux/skbuff.h:4446
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81b077cf)
Location: include/linux/skbuff.h:4446
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
In net/ipv4/tcp_offload.c (ffffffff81ac5a33)
Location: include/linux/skbuff.h:4510
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81ad02bd)
Location: include/linux/skbuff.h:4510
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81af30cb)
Location: include/linux/skbuff.h:4510
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
In net/ipv4/tcp_offload.c (ffffffff81b84243)
Location: include/linux/skbuff.h:4549
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81b8ecdb)
Location: include/linux/skbuff.h:4549
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81bb35db)
Location: include/linux/skbuff.h:4549
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
In net/ipv4/tcp_offload.c (ffffffff81d14a85)
Location: include/linux/skbuff.h:4971
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81d1f9ea)
Location: include/linux/skbuff.h:4971
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81d46dfb)
Location: include/linux/skbuff.h:4971
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
In net/ipv4/tcp_offload.c (ffffffff81edabc5)
Location: include/linux/skbuff.h:4867
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81ee6bda)
Location: include/linux/skbuff.h:4867
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81f1064b)
Location: include/linux/skbuff.h:4867
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
In net/ipv4/tcp_offload.c (ffffffff81f39ca2)
Location: include/net/gso.h:65
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81f4642f)
Location: include/net/gso.h:65
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81f70337)
Location: include/net/gso.h:65
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
In net/ipv4/tcp_offload.c (ffffffff81fffd92)
Location: include/net/gso.h:65
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8200c56f)
Location: include/net/gso.h:65
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff82036a67)
Location: include/net/gso.h:65
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
In net/ipv4/tcp_offload.c (ffff800010c953f0)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffff800010ca0af8)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffff800010cc2c8c)
Location: include/linux/skbuff.h:4377
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
In net/ipv4/tcp_offload.c (c0da3b50)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (c0dadca8)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (c0dce54c)
Location: include/linux/skbuff.h:4377
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
In net/ipv4/tcp_offload.c (c000000000da63dc)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (c000000000db3450)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (c000000000ddebf0)
Location: include/linux/skbuff.h:4377
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
In net/ipv4/tcp_offload.c (ffffffe0007f4694)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd17a)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffe00081807a)
Location: include/linux/skbuff.h:4377
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
In net/ipv4/tcp_offload.c (ffffffff81981286)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8198addf)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff819a976f)
Location: include/linux/skbuff.h:4377
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
In net/ipv4/tcp_offload.c (ffffffff8193ad46)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8194489f)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8196322f)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/ipv4/tcp_offload.c (ffffffff819eba56)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819f55af)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81a1400f)
Location: include/linux/skbuff.h:4377
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
In net/ipv4/tcp_offload.c (ffffffff819f5906)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819ff7af)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81a1e9ff)
Location: include/linux/skbuff.h:4377
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
</details>
</li>
</ul>

## Differences

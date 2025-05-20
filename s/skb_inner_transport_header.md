# Function: <code>skb_inner_transport_header</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81705362)
Location: include/linux/skbuff.h:1940
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
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
In net/core/skbuff.c (ffffffff8176bf32)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/dev.c (ffffffff81780790)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/core/dev.c:__skb_csum_offload_chk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81799112)
Location: include/linux/skbuff.h:2082
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b76ec)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8182fdac)
Location: include/linux/skbuff.h:2208
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187a42c)
Location: include/linux/skbuff.h:2219
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189b03c)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e571c)
Location: include/linux/skbuff.h:2385
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191786c)
Location: include/linux/skbuff.h:2399
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819e9eac)
Location: include/linux/skbuff.h:2422
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
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
In net/core/skbuff.c (ffffffff819e9c4c)
Location: include/linux/skbuff.h:2443
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/ipv4/udp_offload.c (ffffffff81ae4a7a)
Location: include/linux/skbuff.h:2443
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
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
In net/core/skbuff.c (ffffffff819cfd8c)
Location: include/linux/skbuff.h:2459
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/ipv4/udp_offload.c (ffffffff81acfccf)
Location: include/linux/skbuff.h:2459
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
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
In net/core/skbuff.c (ffffffff81a7f7bc)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e6ef)
Location: include/linux/skbuff.h:2488
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
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
In net/core/skbuff.c (ffffffff81bf3bfc)
Location: include/linux/skbuff.h:2856
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/ipv4/udp_offload.c (ffffffff81d1fe91)
Location: include/linux/skbuff.h:2856
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
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
In net/core/skbuff.c (ffffffff81da195c)
Location: include/linux/skbuff.h:2748
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7091)
Location: include/linux/skbuff.h:2748
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
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
In net/core/gso.c (ffffffff81e7d41c)
Location: include/linux/skbuff.h:2802
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_transport_seglen
```
```
In net/ipv4/udp_offload.c (ffffffff81f46931)
Location: include/linux/skbuff.h:2802
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
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
In net/core/gso.c (ffffffff81f3e39c)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_transport_seglen
```
```
In net/ipv4/udp_offload.c (ffffffff8200ca71)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb0c08)
Location: include/linux/skbuff.h:2399
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccdf94)
Location: include/linux/skbuff.h:2399
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c86e10)
Location: include/linux/skbuff.h:2399
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000741dce)
Location: include/linux/skbuff.h:2399
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b786c)
Location: include/linux/skbuff.h:2399
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818717bc)
Location: include/linux/skbuff.h:2399
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190886c)
Location: include/linux/skbuff.h:2399
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192991c)
Location: include/linux/skbuff.h:2399
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
</ul>

## Differences

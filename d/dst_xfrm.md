# Function: <code>dst_xfrm</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (0)
Location: include/net/dst.h:529
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/net/dst.h:529
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/net/dst.h:529
Inline: True
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
In net/ipv4/udp_offload.c (0)
Location: include/net/dst.h:518
Inline: True
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
In net/ipv4/udp.c (0)
Location: include/net/dst.h:502
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/net/dst.h:502
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/dst.h:502
Inline: True
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
In net/ipv4/udp.c (0)
Location: include/net/dst.h:516
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/net/dst.h:516
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/dst.h:516
Inline: True
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
In net/ipv4/udp.c (0)
Location: include/net/dst.h:508
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/net/dst.h:508
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/dst.h:508
Inline: True
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
In net/ipv4/udp.c (0)
Location: include/net/dst.h:508
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/net/dst.h:508
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/dst.h:508
Inline: True
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
In net/ipv4/udp.c (ffffffff81ad1e4c)
Location: include/net/dst.h:515
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ad8638)
Location: include/net/dst.h:515
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff81b578d7)
Location: include/net/dst.h:515
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv4/udp.c (ffffffff81addf8c)
Location: include/net/dst.h:513
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ae4ae3)
Location: include/net/dst.h:513
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff81b65de7)
Location: include/net/dst.h:513
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv4/udp.c (ffffffff81ac8f9f)
Location: include/net/dst.h:530
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81acfd38)
Location: include/net/dst.h:530
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81af3153)
Location: include/net/dst.h:530
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff81b53e91)
Location: include/net/dst.h:530
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv4/udp.c (ffffffff81b87831)
Location: include/net/dst.h:532
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e758)
Location: include/net/dst.h:532
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81bb3663)
Location: include/net/dst.h:532
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff81c1d343)
Location: include/net/dst.h:532
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv4/udp.c (ffffffff81d186a0)
Location: include/net/dst.h:533
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81d1fefb)
Location: include/net/dst.h:533
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81d46e9a)
Location: include/net/dst.h:533
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff81db99a3)
Location: include/net/dst.h:533
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv4/udp.c (ffffffff81edf000)
Location: include/net/dst.h:526
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ee70f8)
Location: include/net/dst.h:526
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81f106ea)
Location: include/net/dst.h:526
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff81f89a33)
Location: include/net/dst.h:526
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv4/udp.c (ffffffff81f3e43f)
Location: include/net/dst.h:540
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81f4699b)
Location: include/net/dst.h:540
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81f703d6)
Location: include/net/dst.h:540
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff81fe92e1)
Location: include/net/dst.h:540
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv4/udp.c (ffffffff820046df)
Location: include/net/dst.h:533
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8200cadb)
Location: include/net/dst.h:533
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff82036b06)
Location: include/net/dst.h:533
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp.c (ffffffff820b5df3)
Location: include/net/dst.h:533
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv4/udp.c (0)
Location: include/net/dst.h:508
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/net/dst.h:508
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/dst.h:508
Inline: True
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
In net/ipv4/udp.c (c0da7114)
Location: include/net/dst.h:508
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/udp_offload.c (c0dad828)
Location: include/net/dst.h:508
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (c0e28354)
Location: include/net/dst.h:508
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv4/udp.c (0)
Location: include/net/dst.h:508
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/net/dst.h:508
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/dst.h:508
Inline: True
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
In net/ipv4/udp.c (0)
Location: include/net/dst.h:508
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/net/dst.h:508
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/dst.h:508
Inline: True
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
In net/ipv4/udp.c (0)
Location: include/net/dst.h:508
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/net/dst.h:508
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/dst.h:508
Inline: True
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
In net/ipv4/udp.c (0)
Location: include/net/dst.h:508
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/net/dst.h:508
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/dst.h:508
Inline: True
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
In net/ipv4/udp.c (0)
Location: include/net/dst.h:508
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/net/dst.h:508
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/dst.h:508
Inline: True
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
In net/ipv4/udp.c (0)
Location: include/net/dst.h:508
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/net/dst.h:508
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/dst.h:508
Inline: True
```
</details>
</li>
</ul>

## Differences

# Function: <code>ip6_route_get_saddr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip6_route_get_saddr(struct net *net, struct rt6_info *rt, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d8550)
Location: net/ipv6/route.c:2527
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
**Symbols:**

```
ffffffff817d8550-ffffffff817d859b: ip6_route_get_saddr (STB_GLOBAL)
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
In net/ipv6/ip6_output.c (ffffffff8183167d)
Location: include/net/ip6_route.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff818420b7)
Location: include/net/ip6_route.h:92
Inline: True
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
In net/ipv6/ip6_output.c (ffffffff818630d3)
Location: include/net/ip6_route.h:96
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81873e07)
Location: include/net/ip6_route.h:96
Inline: True
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
In net/ipv6/ip6_output.c (ffffffff81887886)
Location: include/net/ip6_route.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81898ee6)
Location: include/net/ip6_route.h:98
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffffffff81908b36)
Location: include/net/ip6_route.h:104
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff8191a1ec)
Location: include/net/ip6_route.h:104
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffffffff8195fcf9)
Location: include/net/ip6_route.h:112
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff819722ed)
Location: include/net/ip6_route.h:112
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffffffff81994a98)
Location: include/net/ip6_route.h:112
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff819a7a45)
Location: include/net/ip6_route.h:112
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffffffff81a00651)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81a14128)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffffffff81a37221)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81a4ad18)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffffffff81b2c751)
Location: include/net/ip6_route.h:133
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81b45217)
Location: include/net/ip6_route.h:133
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffffffff81b3b161)
Location: include/net/ip6_route.h:133
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81b53bba)
Location: include/net/ip6_route.h:133
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffffffff81b28f74)
Location: include/net/ip6_route.h:133
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b4117d)
Location: include/net/ip6_route.h:133
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffffffff81bf015c)
Location: include/net/ip6_route.h:133
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c08e53)
Location: include/net/ip6_route.h:133
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffffffff81d887fa)
Location: include/net/ip6_route.h:133
Inline: True
```
```
In net/ipv6/route.c (ffffffff81da36ed)
Location: include/net/ip6_route.h:133
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffffffff81f565da)
Location: include/net/ip6_route.h:133
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f72b2d)
Location: include/net/ip6_route.h:133
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffffffff81fb5f20)
Location: include/net/ip6_route.h:129
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fd2c20)
Location: include/net/ip6_route.h:129
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffffffff820835f0)
Location: include/net/ip6_route.h:128
Inline: True
```
```
In net/ipv6/route.c (ffffffff820a0530)
Location: include/net/ip6_route.h:128
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffff800010cf9e2c)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffff800010d0dcfc)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (c0dfe6a8)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (c0e14660)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (c000000000e1ebe4)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (c000000000e39be4)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffffffe00084329a)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffe00085599e)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffffffff819d68b1)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff819ea3a8)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffffffff81993671)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff819a7168)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffffffff81a41331)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81a54e28)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv6/ip6_output.c (ffffffff81a4cf28)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81a60e18)
Location: include/net/ip6_route.h:132
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>

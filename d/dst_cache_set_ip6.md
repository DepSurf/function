# Function: <code>dst_cache_set_ip6</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff817aae10)
Location: net/core/dst_cache.c:109
Inline: False
```
**Symbols:**

```
ffffffff817aae10-ffffffff817aaec1: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff817da430)
Location: net/core/dst_cache.c:109
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
ffffffff817da430-ffffffff817da4e1: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff817f9540)
Location: net/core/dst_cache.c:109
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
**Symbols:**

```
ffffffff817f9540-ffffffff817f9630: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81876e50)
Location: net/core/dst_cache.c:109
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
**Symbols:**

```
ffffffff81876e50-ffffffff81876f42: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff818c8590)
Location: net/core/dst_cache.c:109
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
**Symbols:**

```
ffffffff818c8590-ffffffff818c8661: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff818f34c0)
Location: net/core/dst_cache.c:109
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
**Symbols:**

```
ffffffff818f34c0-ffffffff818f3598: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst_cache.c (0)
Location: net/core/dst_cache.c:105
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
**Symbols:**

```
ffffffff81945c75-ffffffff81945c7f: dst_cache_set_ip6.cold (STB_LOCAL)
ffffffff81945990-ffffffff81945a24: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff8197a9b0)
Location: net/core/dst_cache.c:105
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
**Symbols:**

```
ffffffff8197a9b0-ffffffff8197aa44: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81a4fe60)
Location: net/core/dst_cache.c:105
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tunnel
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
**Symbols:**

```
ffffffff81a4fe60-ffffffff81a4ff03: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81a55e80)
Location: net/core/dst_cache.c:105
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tunnel
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
**Symbols:**

```
ffffffff81a55e80-ffffffff81a55f43: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81a38e90)
Location: net/core/dst_cache.c:105
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tunnel
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
**Symbols:**

```
ffffffff81a38e90-ffffffff81a38f53: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81aeed60)
Location: net/core/dst_cache.c:105
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tunnel
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
**Symbols:**

```
ffffffff81aeed60-ffffffff81aeee23: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81c71cf0)
Location: net/core/dst_cache.c:105
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tunnel
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
**Symbols:**

```
ffffffff81c71cf0-ffffffff81c71dc5: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81e29df0)
Location: net/core/dst_cache.c:105
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tunnel
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
**Symbols:**

```
ffffffff81e29df0-ffffffff81e29ec5: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81e9f7a0)
Location: net/core/dst_cache.c:105
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tunnel
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
**Symbols:**

```
ffffffff81e9f7a0-ffffffff81e9f855: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81f61f10)
Location: net/core/dst_cache.c:105
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
**Symbols:**

```
ffffffff81f61f10-ffffffff81f61fc5: dst_cache_set_ip6 (STB_GLOBAL)
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
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffff800010c220f0)
Location: net/core/dst_cache.c:105
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
**Symbols:**

```
ffff800010c220f0-ffff800010c221c0: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (c0d393b8)
Location: net/core/dst_cache.c:105
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
**Symbols:**

```
c0d393b8-c0d39484: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (c000000000d143f0)
Location: net/core/dst_cache.c:105
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
**Symbols:**

```
c000000000d143f0-c000000000d144d8: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffe00079ab52)
Location: net/core/dst_cache.c:105
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
**Symbols:**

```
ffffffe00079ab52-ffffffe00079ac04: dst_cache_set_ip6 (STB_GLOBAL)
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
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff8191a820)
Location: net/core/dst_cache.c:105
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
**Symbols:**

```
ffffffff8191a820-ffffffff8191a8b4: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff818d45d0)
Location: net/core/dst_cache.c:105
Inline: False
Direct callers:
  - drivers/net/vxlan.c:vxlan6_get_route
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
**Symbols:**

```
ffffffff818d45d0-ffffffff818d4664: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff8196b9b0)
Location: net/core/dst_cache.c:105
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
**Symbols:**

```
ffffffff8196b9b0-ffffffff8196ba44: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dst_cache_set_ip6(struct dst_cache *dst_cache, struct dst_entry *dst, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff8198de20)
Location: net/core/dst_cache.c:105
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
**Symbols:**

```
ffffffff8198de20-ffffffff8198dec2: dst_cache_set_ip6 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct in6_addr *saddr</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct in6_addr *addr</code>
</li>
</ul>
</details>
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

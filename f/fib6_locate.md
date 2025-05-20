# Function: <code>fib6_locate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff817dbb20)
Location: net/ipv6/ip6_fib.c:1227
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff817dbb20-ffffffff817dbba0: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81849ac0)
Location: net/ipv6/ip6_fib.c:1229
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81849ac0-ffffffff81849b40: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8187b950)
Location: net/ipv6/ip6_fib.c:1235
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff8187b950-ffffffff8187b9d0: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff818a1380)
Location: net/ipv6/ip6_fib.c:1273
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff818a1380-ffffffff818a13dd: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81923ca0)
Location: net/ipv6/ip6_fib.c:1469
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81923ca0-ffffffff81923d0d: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8197c060)
Location: net/ipv6/ip6_fib.c:1528
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff8197c060-ffffffff8197c0cd: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b1d40)
Location: net/ipv6/ip6_fib.c:1562
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff819b1d40-ffffffff819b1dad: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1634
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81a20a3f-ffffffff81a20a52: fib6_locate.cold (STB_LOCAL)
ffffffff81a20230-ffffffff81a202b5: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a56ea0)
Location: net/ipv6/ip6_fib.c:1635
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81a56ea0-ffffffff81a56f08: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4f1c0)
Location: net/ipv6/ip6_fib.c:1702
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81b4f1c0-ffffffff81b4f228: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b5de40)
Location: net/ipv6/ip6_fib.c:1705
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81b5de40-ffffffff81b5dea8: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4c0c0)
Location: net/ipv6/ip6_fib.c:1706
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81b4c0c0-ffffffff81b4c128: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81c133c0)
Location: net/ipv6/ip6_fib.c:1707
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81c133c0-ffffffff81c13428: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81dae990)
Location: net/ipv6/ip6_fib.c:1708
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81dae990-ffffffff81daea21: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81f7e4b0)
Location: net/ipv6/ip6_fib.c:1707
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81f7e4b0-ffffffff81f7e541: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81fde6c0)
Location: net/ipv6/ip6_fib.c:1707
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81fde6c0-ffffffff81fde751: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff820ac240)
Location: net/ipv6/ip6_fib.c:1703
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff820ac240-ffffffff820ac2d1: fib6_locate (STB_GLOBAL)
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
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffff800010d1b970)
Location: net/ipv6/ip6_fib.c:1635
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffff800010d1b970-ffff800010d1ba18: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c0e20dc8)
Location: net/ipv6/ip6_fib.c:1635
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
c0e20dc8-c0e20e78: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c000000000e4a230)
Location: net/ipv6/ip6_fib.c:1635
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
c000000000e4a230-c000000000e4a2dc: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffe00085fa04)
Location: net/ipv6/ip6_fib.c:1635
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffe00085fa04-ffffffe00085fa88: fib6_locate (STB_GLOBAL)
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
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819f6530)
Location: net/ipv6/ip6_fib.c:1635
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff819f6530-ffffffff819f6598: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b32f0)
Location: net/ipv6/ip6_fib.c:1635
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff819b32f0-ffffffff819b3358: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a60fb0)
Location: net/ipv6/ip6_fib.c:1635
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81a60fb0-ffffffff81a61018: fib6_locate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fib6_node *fib6_locate(struct fib6_node *root, const struct in6_addr *daddr, int dst_len, const struct in6_addr *saddr, int src_len, bool exact_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a6d470)
Location: net/ipv6/ip6_fib.c:1635
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81a6d470-ffffffff81a6d4d8: fib6_locate (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool exact_match</code>
</li>
</ul>
</details>
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

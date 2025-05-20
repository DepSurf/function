# Function: <code>fib6_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fib6_del(struct rt6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff817dbba0)
Location: net/ipv6/ip6_fib.c:1440
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff817dbba0-ffffffff817dbe35: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fib6_del(struct rt6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81849b40)
Location: net/ipv6/ip6_fib.c:1442
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff81849b40-ffffffff81849dd4: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fib6_del(struct rt6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8187b9d0)
Location: net/ipv6/ip6_fib.c:1448
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff8187b9d0-ffffffff8187bc64: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fib6_del(struct rt6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff818a13e0)
Location: net/ipv6/ip6_fib.c:1487
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff818a13e0-ffffffff818a1652: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fib6_del(struct rt6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81923d10)
Location: net/ipv6/ip6_fib.c:1730
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff81923d10-ffffffff81923fc8: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8197c0d0)
Location: net/ipv6/ip6_fib.c:1788
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff8197c0d0-ffffffff8197c361: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b1db0)
Location: net/ipv6/ip6_fib.c:1822
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff819b1db0-ffffffff819b2046: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1896
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff81a20a52-ffffffff81a20a65: fib6_del.cold (STB_LOCAL)
ffffffff81a202c0-ffffffff81a20500: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a56f10)
Location: net/ipv6/ip6_fib.c:1897
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff81a56f10-ffffffff81a5714a: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4f230)
Location: net/ipv6/ip6_fib.c:1993
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff81b4f230-ffffffff81b4f2a8: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b5deb0)
Location: net/ipv6/ip6_fib.c:1997
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff81b5deb0-ffffffff81b5df28: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4c130)
Location: net/ipv6/ip6_fib.c:1998
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff81b4c130-ffffffff81b4c1a9: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81c13430)
Location: net/ipv6/ip6_fib.c:1999
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff81c13430-ffffffff81c134a9: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81daea30)
Location: net/ipv6/ip6_fib.c:2000
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff81daea30-ffffffff81daeacd: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81f7e560)
Location: net/ipv6/ip6_fib.c:1999
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff81f7e560-ffffffff81f7e5fd: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81fde770)
Location: net/ipv6/ip6_fib.c:1999
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff81fde770-ffffffff81fde80d: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff820ac2f0)
Location: net/ipv6/ip6_fib.c:1995
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff820ac2f0-ffffffff820ac38d: fib6_del (STB_GLOBAL)
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
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffff800010d1ba18)
Location: net/ipv6/ip6_fib.c:1897
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffff800010d1ba18-ffff800010d1bd20: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c0e20e78)
Location: net/ipv6/ip6_fib.c:1897
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
c0e20e78-c0e21144: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c000000000e4a2e0)
Location: net/ipv6/ip6_fib.c:1897
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
c000000000e4a2e0-c000000000e4a6a0: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffe00085fa88)
Location: net/ipv6/ip6_fib.c:1897
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffe00085fa88-ffffffe00085fc8c: fib6_del (STB_GLOBAL)
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
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819f65a0)
Location: net/ipv6/ip6_fib.c:1897
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff819f65a0-ffffffff819f67da: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b3360)
Location: net/ipv6/ip6_fib.c:1897
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff819b3360-ffffffff819b359a: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a61020)
Location: net/ipv6/ip6_fib.c:1897
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff81a61020-ffffffff81a6125a: fib6_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib6_del(struct fib6_info *rt, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a6d4e0)
Location: net/ipv6/ip6_fib.c:1897
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_clean_node
```
**Symbols:**

```
ffffffff81a6d4e0-ffffffff81a6d71d: fib6_del (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rt6_info *rt</code> ➡️ <code>struct fib6_info *rt</code>
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

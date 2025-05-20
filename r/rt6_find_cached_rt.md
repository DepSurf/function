# Function: <code>rt6_find_cached_rt</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rt6_info *rt6_find_cached_rt(struct rt6_info *rt, struct in6_addr *daddr, struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191ba10)
Location: net/ipv6/route.c:1389
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff8191ba10-ffffffff8191ba8a: rt6_find_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rt6_info *rt6_find_cached_rt(struct fib6_info *rt, struct in6_addr *daddr, struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81973730)
Location: net/ipv6/route.c:1527
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81973730-ffffffff819737a7: rt6_find_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rt6_info *rt6_find_cached_rt(struct fib6_info *rt, struct in6_addr *daddr, struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a9380)
Location: net/ipv6/route.c:1536
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff819a9380-ffffffff819a93f7: rt6_find_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81a161b0)
Location: net/ipv6/route.c:1761
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81a161b0-ffffffff81a16282: rt6_find_cached_rt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4cdf0)
Location: net/ipv6/route.c:1767
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81a4cdf0-ffffffff81a4cec2: rt6_find_cached_rt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rt6_info *rt6_find_cached_rt(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b434e0)
Location: net/ipv6/route.c:1789
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81b434e0-ffffffff81b435b4: rt6_find_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rt6_info *rt6_find_cached_rt(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b51bd0)
Location: net/ipv6/route.c:1772
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81b51bd0-ffffffff81b51ca4: rt6_find_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rt6_info *rt6_find_cached_rt(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3e1f0)
Location: net/ipv6/route.c:1782
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81b3e1f0-ffffffff81b3e2c1: rt6_find_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rt6_info *rt6_find_cached_rt(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c04ad0)
Location: net/ipv6/route.c:1785
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81c04ad0-ffffffff81c04ba1: rt6_find_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rt6_info *rt6_find_cached_rt(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9f5a0)
Location: net/ipv6/route.c:1785
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81d9f5a0-ffffffff81d9f67b: rt6_find_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rt6_info *rt6_find_cached_rt(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6e5e0)
Location: net/ipv6/route.c:1785
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81f6e5e0-ffffffff81f6e6bb: rt6_find_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rt6_info *rt6_find_cached_rt(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fce6a0)
Location: net/ipv6/route.c:1784
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81fce6a0-ffffffff81fce77b: rt6_find_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rt6_info *rt6_find_cached_rt(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209bf00)
Location: net/ipv6/route.c:1786
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff8209bf00-ffffffff8209bfdb: rt6_find_cached_rt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffff800010d0fd70)
Location: net/ipv6/route.c:1767
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffff800010d0fd70-ffff800010d0fe6c: rt6_find_cached_rt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rt6_info *rt6_find_cached_rt(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e173ec)
Location: net/ipv6/route.c:1767
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
c0e173ec-c0e174e4: rt6_find_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (c000000000e3d660)
Location: net/ipv6/route.c:1767
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
c000000000e3d660-c000000000e3d770: rt6_find_cached_rt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffe0008578cc)
Location: net/ipv6/route.c:1767
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffe0008578cc-ffffffe00085795c: rt6_find_cached_rt.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff819ec480)
Location: net/ipv6/route.c:1767
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff819ec480-ffffffff819ec552: rt6_find_cached_rt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff819a9240)
Location: net/ipv6/route.c:1767
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff819a9240-ffffffff819a9312: rt6_find_cached_rt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81a56f00)
Location: net/ipv6/route.c:1767
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81a56f00-ffffffff81a56fd2: rt6_find_cached_rt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81a62fb0)
Location: net/ipv6/route.c:1767
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81a62fb0-ffffffff81a63082: rt6_find_cached_rt.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>

# Function: <code>ip6_redirect_nh_match</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result *res, struct flowi6 *fl6, const struct in6_addr *gw, struct rt6_info **ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a16290)
Location: net/ipv6/route.c:2833
Inline: True
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_nh_redirect_match
```
**Symbols:**

```
ffffffff81a16290-ffffffff81a1631d: ip6_redirect_nh_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result *res, struct flowi6 *fl6, const struct in6_addr *gw, struct rt6_info **ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4ced0)
Location: net/ipv6/route.c:2843
Inline: True
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_nh_redirect_match
```
**Symbols:**

```
ffffffff81a4ced0-ffffffff81a4cf5d: ip6_redirect_nh_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result *res, struct flowi6 *fl6, const struct in6_addr *gw, struct rt6_info **ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b435c0)
Location: net/ipv6/route.c:2867
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_nh_redirect_match
```
**Symbols:**

```
ffffffff81b435c0-ffffffff81b43651: ip6_redirect_nh_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result *res, struct flowi6 *fl6, const struct in6_addr *gw, struct rt6_info **ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b51cb0)
Location: net/ipv6/route.c:2851
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_nh_redirect_match
```
**Symbols:**

```
ffffffff81b51cb0-ffffffff81b51d41: ip6_redirect_nh_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result *res, struct flowi6 *fl6, const struct in6_addr *gw, struct rt6_info **ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3e2d0)
Location: net/ipv6/route.c:2860
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_nh_redirect_match
```
**Symbols:**

```
ffffffff81b3e2d0-ffffffff81b3e361: ip6_redirect_nh_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result *res, struct flowi6 *fl6, const struct in6_addr *gw, struct rt6_info **ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c04bb0)
Location: net/ipv6/route.c:2990
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_nh_redirect_match
```
**Symbols:**

```
ffffffff81c04bb0-ffffffff81c04c41: ip6_redirect_nh_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result *res, struct flowi6 *fl6, const struct in6_addr *gw, struct rt6_info **ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9f680)
Location: net/ipv6/route.c:2986
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_nh_redirect_match
```
**Symbols:**

```
ffffffff81d9f680-ffffffff81d9f73d: ip6_redirect_nh_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result *res, struct flowi6 *fl6, const struct in6_addr *gw, struct rt6_info **ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6e6d0)
Location: net/ipv6/route.c:2986
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_nh_redirect_match
```
**Symbols:**

```
ffffffff81f6e6d0-ffffffff81f6e78d: ip6_redirect_nh_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result *res, struct flowi6 *fl6, const struct in6_addr *gw, struct rt6_info **ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fce790)
Location: net/ipv6/route.c:2986
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_nh_redirect_match
```
**Symbols:**

```
ffffffff81fce790-ffffffff81fce84d: ip6_redirect_nh_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result *res, struct flowi6 *fl6, const struct in6_addr *gw, struct rt6_info **ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209bff0)
Location: net/ipv6/route.c:2988
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_nh_redirect_match
```
**Symbols:**

```
ffffffff8209bff0-ffffffff8209c0ad: ip6_redirect_nh_match (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result *res, struct flowi6 *fl6, const struct in6_addr *gw, struct rt6_info **ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0fe70)
Location: net/ipv6/route.c:2843
Inline: True
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_nh_redirect_match
```
**Symbols:**

```
ffff800010d0fe70-ffff800010d0ff34: ip6_redirect_nh_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result *res, struct flowi6 *fl6, const struct in6_addr *gw, struct rt6_info **ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e174e4)
Location: net/ipv6/route.c:2843
Inline: True
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_nh_redirect_match
```
**Symbols:**

```
c0e174e4-c0e175e8: ip6_redirect_nh_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result *res, struct flowi6 *fl6, const struct in6_addr *gw, struct rt6_info **ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3d770)
Location: net/ipv6/route.c:2843
Inline: True
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_nh_redirect_match
```
**Symbols:**

```
c000000000e3d770-c000000000e3d8a4: ip6_redirect_nh_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result *res, struct flowi6 *fl6, const struct in6_addr *gw, struct rt6_info **ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085795c)
Location: net/ipv6/route.c:2843
Inline: True
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_nh_redirect_match
```
**Symbols:**

```
ffffffe00085795c-ffffffe000857a3c: ip6_redirect_nh_match (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result *res, struct flowi6 *fl6, const struct in6_addr *gw, struct rt6_info **ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ec560)
Location: net/ipv6/route.c:2843
Inline: True
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_nh_redirect_match
```
**Symbols:**

```
ffffffff819ec560-ffffffff819ec5ed: ip6_redirect_nh_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result *res, struct flowi6 *fl6, const struct in6_addr *gw, struct rt6_info **ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a9320)
Location: net/ipv6/route.c:2843
Inline: True
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_nh_redirect_match
```
**Symbols:**

```
ffffffff819a9320-ffffffff819a93ad: ip6_redirect_nh_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result *res, struct flowi6 *fl6, const struct in6_addr *gw, struct rt6_info **ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a56fe0)
Location: net/ipv6/route.c:2843
Inline: True
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_nh_redirect_match
```
**Symbols:**

```
ffffffff81a56fe0-ffffffff81a5706d: ip6_redirect_nh_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result *res, struct flowi6 *fl6, const struct in6_addr *gw, struct rt6_info **ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a63090)
Location: net/ipv6/route.c:2843
Inline: True
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_nh_redirect_match
```
**Symbols:**

```
ffffffff81a63090-ffffffff81a6311d: ip6_redirect_nh_match (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

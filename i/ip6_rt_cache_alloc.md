# Function: <code>ip6_rt_cache_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(struct rt6_info *ort, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d38b0)
Location: net/ipv6/route.c:932
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff817d38b0-ffffffff817d39ce: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(struct rt6_info *ort, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81841350)
Location: net/ipv6/route.c:937
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81841350-ffffffff81841462: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(struct rt6_info *ort, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81873050)
Location: net/ipv6/route.c:940
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81873050-ffffffff81873162: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(struct rt6_info *ort, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189a6e0)
Location: net/ipv6/route.c:962
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff8189a6e0-ffffffff8189a7f7: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(struct rt6_info *ort, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191b040)
Location: net/ipv6/route.c:1048
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff8191b040-ffffffff8191b15f: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(struct fib6_info *ort, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81974860)
Location: net/ipv6/route.c:1169
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81974860-ffffffff819749b2: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(struct fib6_info *ort, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819aa480)
Location: net/ipv6/route.c:1172
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff819aa480-ffffffff819aa5d2: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a177a0)
Location: net/ipv6/route.c:1322
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81a177a0-ffffffff81a17930: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4e3f0)
Location: net/ipv6/route.c:1328
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81a4e3f0-ffffffff81a4e580: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b45db0)
Location: net/ipv6/route.c:1329
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81b45db0-ffffffff81b45f5a: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b548e0)
Location: net/ipv6/route.c:1312
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81b548e0-ffffffff81b54a8a: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b422a0)
Location: net/ipv6/route.c:1315
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81b422a0-ffffffff81b42442: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c07980)
Location: net/ipv6/route.c:1315
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81c07980-ffffffff81c07b22: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da25d0)
Location: net/ipv6/route.c:1315
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81da25d0-ffffffff81da27c3: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f71990)
Location: net/ipv6/route.c:1315
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81f71990-ffffffff81f71b83: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd1a70)
Location: net/ipv6/route.c:1314
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81fd1a70-ffffffff81fd1c62: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209f010)
Location: net/ipv6/route.c:1316
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff8209f010-ffffffff8209f1f5: ip6_rt_cache_alloc (STB_LOCAL)
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
struct rt6_info *ip6_rt_cache_alloc(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0f2e8)
Location: net/ipv6/route.c:1328
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffff800010d0f2e8-ffff800010d0f458: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e16f24)
Location: net/ipv6/route.c:1328
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
c0e16f24-c0e1708c: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3e5d0)
Location: net/ipv6/route.c:1328
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
c000000000e3e5d0-c000000000e3e7d8: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085427e)
Location: net/ipv6/route.c:1328
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffe00085427e-ffffffe00085440c: ip6_rt_cache_alloc (STB_LOCAL)
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
struct rt6_info *ip6_rt_cache_alloc(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819eda80)
Location: net/ipv6/route.c:1328
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff819eda80-ffffffff819edc10: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819aa840)
Location: net/ipv6/route.c:1328
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff819aa840-ffffffff819aa9d0: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a58500)
Location: net/ipv6/route.c:1328
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81a58500-ffffffff81a58690: ip6_rt_cache_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_cache_alloc(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a646b0)
Location: net/ipv6/route.c:1328
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81a646b0-ffffffff81a64840: ip6_rt_cache_alloc (STB_LOCAL)
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
<code>struct rt6_info *ort</code> ➡️ <code>struct fib6_info *ort</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct fib6_result *res</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fib6_info *ort</code>
</li>
</ul>
</details>
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

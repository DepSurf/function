# Function: <code>fib6_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fib6_node *fib6_lookup(struct fib6_node *root, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff817dba90)
Location: net/ipv6/ip6_fib.c:1164
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_backtrack
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff817dba90-ffffffff817dbb1b: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fib6_node *fib6_lookup(struct fib6_node *root, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81849a30)
Location: net/ipv6/ip6_fib.c:1166
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:fib6_backtrack
```
**Symbols:**

```
ffffffff81849a30-ffffffff81849abb: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fib6_node *fib6_lookup(struct fib6_node *root, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8187b8c0)
Location: net/ipv6/ip6_fib.c:1172
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:fib6_backtrack
```
**Symbols:**

```
ffffffff8187b8c0-ffffffff8187b94b: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fib6_node *fib6_lookup(struct fib6_node *root, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff818a12c0)
Location: net/ipv6/ip6_fib.c:1210
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:fib6_backtrack
```
**Symbols:**

```
ffffffff818a12c0-ffffffff818a137b: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fib6_node *fib6_lookup(struct fib6_node *root, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81923be0)
Location: net/ipv6/ip6_fib.c:1381
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:fib6_backtrack
```
**Symbols:**

```
ffffffff81923be0-ffffffff81923c9b: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fib6_info *fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff819a3c70)
Location: net/ipv6/fib6_rules.c:64
Inline: False
```
**Symbols:**

```
ffffffff819a3c70-ffffffff819a3d68: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fib6_info *fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff819da780)
Location: net/ipv6/fib6_rules.c:64
Inline: False
```
**Symbols:**

```
ffffffff819da780-ffffffff819da878: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, struct fib6_result *res, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff81a49370)
Location: net/ipv6/fib6_rules.c:61
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81a49370-ffffffff81a4945d: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, struct fib6_result *res, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff81a7ff70)
Location: net/ipv6/fib6_rules.c:61
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81a7ff70-ffffffff81a8005d: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, struct fib6_result *res, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff81b7abb0)
Location: net/ipv6/fib6_rules.c:62
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81b7abb0-ffffffff81b7ac9d: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, struct fib6_result *res, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff81b89b60)
Location: net/ipv6/fib6_rules.c:63
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81b89b60-ffffffff81b89c4d: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, struct fib6_result *res, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff81b789b0)
Location: net/ipv6/fib6_rules.c:63
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81b789b0-ffffffff81b78a9d: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, struct fib6_result *res, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/fib6_rules.c (0)
Location: net/ipv6/fib6_rules.c:63
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81d41501-ffffffff81d41516: fib6_lookup.cold (STB_LOCAL)
ffffffff81c434f0-ffffffff81c435f7: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, struct fib6_result *res, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/fib6_rules.c (0)
Location: net/ipv6/fib6_rules.c:64
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81f0de74-ffffffff81f0de89: fib6_lookup.cold (STB_LOCAL)
ffffffff81de2210-ffffffff81de2325: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, struct fib6_result *res, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/fib6_rules.c (0)
Location: net/ipv6/fib6_rules.c:64
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff820b521c-ffffffff820b5231: fib6_lookup.cold (STB_LOCAL)
ffffffff81fb4770-ffffffff81fb4885: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, struct fib6_result *res, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/fib6_rules.c (0)
Location: net/ipv6/fib6_rules.c:64
Inline: False
```
**Symbols:**

```
ffffffff821360d6-ffffffff821360eb: fib6_lookup.cold (STB_LOCAL)
ffffffff82014ef0-ffffffff82015005: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, struct fib6_result *res, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/fib6_rules.c (0)
Location: net/ipv6/fib6_rules.c:64
Inline: False
```
**Symbols:**

```
ffffffff82217cf2-ffffffff82217d07: fib6_lookup.cold (STB_LOCAL)
ffffffff820e4030-ffffffff820e4145: fib6_lookup (STB_GLOBAL)
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
int fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, struct fib6_result *res, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffff800010d4b5f8)
Location: net/ipv6/fib6_rules.c:61
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffff800010d4b5f8-ffff800010d4b6f8: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, struct fib6_result *res, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (c0e4c8f8)
Location: net/ipv6/fib6_rules.c:61
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
c0e4c8f8-c0e4c9fc: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, struct fib6_result *res, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (c000000000e81890)
Location: net/ipv6/fib6_rules.c:61
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
c000000000e81890-c000000000e819d0: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, struct fib6_result *res, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffe0008845e2)
Location: net/ipv6/fib6_rules.c:61
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffe0008845e2-ffffffe0008846ac: fib6_lookup (STB_GLOBAL)
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
int fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, struct fib6_result *res, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff81a1f600)
Location: net/ipv6/fib6_rules.c:61
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81a1f600-ffffffff81a1f6ed: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, struct fib6_result *res, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff819dc3c0)
Location: net/ipv6/fib6_rules.c:61
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff819dc3c0-ffffffff819dc4ad: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, struct fib6_result *res, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff81a8a080)
Location: net/ipv6/fib6_rules.c:61
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81a8a080-ffffffff81a8a16d: fib6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib6_lookup(struct net *net, int oif, struct flowi6 *fl6, struct fib6_result *res, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff81a96ce0)
Location: net/ipv6/fib6_rules.c:61
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81a96ce0-ffffffff81a96dcd: fib6_lookup (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param added. </b>
<code>int oif</code>
</li>
<li>
<b>Param added. </b>
<code>struct flowi6 *fl6</code>
</li>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fib6_node *root</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct in6_addr *daddr</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct in6_addr *saddr</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct fib6_node *</code> ➡️ <code>struct fib6_info *</code>
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
<code>struct fib6_result *res</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, oif, fl6, flags</code> ➡️ <code>net, oif, fl6, res, flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct fib6_info *</code> ➡️ <code>int</code>
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

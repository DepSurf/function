# Function: <code>fib6_select_path</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void fib6_select_path(const struct net *net, struct fib6_result *res, struct flowi6 *fl6, int oif, bool have_oif_match, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a19410)
Location: net/ipv6/route.c:425
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81a19410-ffffffff81a195b5: fib6_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fib6_select_path(const struct net *net, struct fib6_result *res, struct flowi6 *fl6, int oif, bool have_oif_match, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a50070)
Location: net/ipv6/route.c:427
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81a50070-ffffffff81a50215: fib6_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fib6_select_path(const struct net *net, struct fib6_result *res, struct flowi6 *fl6, int oif, bool have_oif_match, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b47800)
Location: net/ipv6/route.c:427
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81b47800-ffffffff81b479ba: fib6_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fib6_select_path(const struct net *net, struct fib6_result *res, struct flowi6 *fl6, int oif, bool have_oif_match, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b563e0)
Location: net/ipv6/route.c:410
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81b563e0-ffffffff81b5659a: fib6_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fib6_select_path(const struct net *net, struct fib6_result *res, struct flowi6 *fl6, int oif, bool have_oif_match, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b43ff0)
Location: net/ipv6/route.c:413
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81b43ff0-ffffffff81b441aa: fib6_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fib6_select_path(const struct net *net, struct fib6_result *res, struct flowi6 *fl6, int oif, bool have_oif_match, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:413
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81d40018-ffffffff81d400ab: fib6_select_path.cold (STB_LOCAL)
ffffffff81c0af00-ffffffff81c0b10b: fib6_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fib6_select_path(const struct net *net, struct fib6_result *res, struct flowi6 *fl6, int oif, bool have_oif_match, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:415
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81f0c991-ffffffff81f0ca24: fib6_select_path.cold (STB_LOCAL)
ffffffff81da5ca0-ffffffff81da5ecb: fib6_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fib6_select_path(const struct net *net, struct fib6_result *res, struct flowi6 *fl6, int oif, bool have_oif_match, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:415
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff820b3fe2-ffffffff820b4075: fib6_select_path.cold (STB_LOCAL)
ffffffff81f751f0-ffffffff81f7541b: fib6_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fib6_select_path(const struct net *net, struct fib6_result *res, struct flowi6 *fl6, int oif, bool have_oif_match, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:414
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff821350a9-ffffffff8213513d: fib6_select_path.cold (STB_LOCAL)
ffffffff81fd5280-ffffffff81fd54ab: fib6_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fib6_select_path(const struct net *net, struct fib6_result *res, struct flowi6 *fl6, int oif, bool have_oif_match, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:413
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff82216b6d-ffffffff82216c0e: fib6_select_path.cold (STB_LOCAL)
ffffffff820a2b90-ffffffff820a2e0a: fib6_select_path (STB_GLOBAL)
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
void fib6_select_path(const struct net *net, struct fib6_result *res, struct flowi6 *fl6, int oif, bool have_oif_match, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d13fd0)
Location: net/ipv6/route.c:427
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffff800010d13fd0-ffff800010d14194: fib6_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fib6_select_path(const struct net *net, struct fib6_result *res, struct flowi6 *fl6, int oif, bool have_oif_match, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e19b6c)
Location: net/ipv6/route.c:427
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:ip6_nh_lookup_table
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
c0e19b6c-c0e19d24: fib6_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fib6_select_path(const struct net *net, struct fib6_result *res, struct flowi6 *fl6, int oif, bool have_oif_match, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e40a90)
Location: net/ipv6/route.c:427
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
c000000000e40a90-c000000000e40d1c: fib6_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fib6_select_path(const struct net *net, struct fib6_result *res, struct flowi6 *fl6, int oif, bool have_oif_match, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000859996)
Location: net/ipv6/route.c:427
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:ip6_nh_lookup_table
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffe000859996-ffffffe000859b06: fib6_select_path (STB_GLOBAL)
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
void fib6_select_path(const struct net *net, struct fib6_result *res, struct flowi6 *fl6, int oif, bool have_oif_match, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ef700)
Location: net/ipv6/route.c:427
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff819ef700-ffffffff819ef8a5: fib6_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fib6_select_path(const struct net *net, struct fib6_result *res, struct flowi6 *fl6, int oif, bool have_oif_match, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ac4c0)
Location: net/ipv6/route.c:427
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff819ac4c0-ffffffff819ac665: fib6_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fib6_select_path(const struct net *net, struct fib6_result *res, struct flowi6 *fl6, int oif, bool have_oif_match, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5a180)
Location: net/ipv6/route.c:427
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81a5a180-ffffffff81a5a325: fib6_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fib6_select_path(const struct net *net, struct fib6_result *res, struct flowi6 *fl6, int oif, bool have_oif_match, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a663e0)
Location: net/ipv6/route.c:427
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81a663e0-ffffffff81a66585: fib6_select_path (STB_GLOBAL)
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

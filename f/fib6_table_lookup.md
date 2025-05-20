# Function: <code>fib6_table_lookup</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fib6_info *fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819759b0)
Location: net/ipv6/route.c:1819
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
ffffffff819759b0-ffffffff81975cee: fib6_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fib6_info *fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ab600)
Location: net/ipv6/route.c:1810
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
ffffffff819ab600-ffffffff819ab93e: fib6_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, struct fib6_result *res, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a18e10)
Location: net/ipv6/route.c:2152
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
ffffffff81a18e10-ffffffff81a190ec: fib6_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, struct fib6_result *res, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4fa70)
Location: net/ipv6/route.c:2158
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
ffffffff81a4fa70-ffffffff81a4fd4c: fib6_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, struct fib6_result *res, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b471f0)
Location: net/ipv6/route.c:2180
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
ffffffff81b471f0-ffffffff81b474d2: fib6_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, struct fib6_result *res, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b55df0)
Location: net/ipv6/route.c:2163
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
ffffffff81b55df0-ffffffff81b560b3: fib6_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, struct fib6_result *res, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b43a10)
Location: net/ipv6/route.c:2170
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
ffffffff81b43a10-ffffffff81b43cd0: fib6_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, struct fib6_result *res, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2173
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
ffffffff81d3fff3-ffffffff81d40018: fib6_table_lookup.cold (STB_LOCAL)
ffffffff81c0a590-ffffffff81c0a84d: fib6_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, struct fib6_result *res, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2173
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
ffffffff81f0c96c-ffffffff81f0c991: fib6_table_lookup.cold (STB_LOCAL)
ffffffff81da52a0-ffffffff81da5576: fib6_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, struct fib6_result *res, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2173
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
ffffffff820b3fbd-ffffffff820b3fe2: fib6_table_lookup.cold (STB_LOCAL)
ffffffff81f747d0-ffffffff81f74aa6: fib6_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, struct fib6_result *res, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2172
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
ffffffff82135084-ffffffff821350a9: fib6_table_lookup.cold (STB_LOCAL)
ffffffff81fd4870-ffffffff81fd4b46: fib6_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, struct fib6_result *res, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2174
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
ffffffff82216b48-ffffffff82216b6d: fib6_table_lookup.cold (STB_LOCAL)
ffffffff820a2180-ffffffff820a2456: fib6_table_lookup (STB_GLOBAL)
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
int fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, struct fib6_result *res, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d139c0)
Location: net/ipv6/route.c:2158
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
ffff800010d139c0-ffff800010d13d04: fib6_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, struct fib6_result *res, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e19548)
Location: net/ipv6/route.c:2158
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_nh_lookup_table
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
c0e19548-c0e19870: fib6_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, struct fib6_result *res, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e40310)
Location: net/ipv6/route.c:2158
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
c000000000e40310-c000000000e406ac: fib6_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, struct fib6_result *res, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085949c)
Location: net/ipv6/route.c:2158
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_nh_lookup_table
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
ffffffe00085949c-ffffffe0008596c8: fib6_table_lookup (STB_GLOBAL)
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
int fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, struct fib6_result *res, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ef100)
Location: net/ipv6/route.c:2158
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
ffffffff819ef100-ffffffff819ef3dc: fib6_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, struct fib6_result *res, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819abec0)
Location: net/ipv6/route.c:2158
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
ffffffff819abec0-ffffffff819ac19c: fib6_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, struct fib6_result *res, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a59b80)
Location: net/ipv6/route.c:2158
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
ffffffff81a59b80-ffffffff81a59e5c: fib6_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib6_table_lookup(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, struct fib6_result *res, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a65dc0)
Location: net/ipv6/route.c:2158
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_lookup
  - net/ipv6/fib6_rules.c:fib6_lookup
```
**Symbols:**

```
ffffffff81a65dc0-ffffffff81a660b4: fib6_table_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>net, table, oif, fl6, strict</code> ➡️ <code>net, table, oif, fl6, res, strict</code>
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

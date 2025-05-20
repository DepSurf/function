# Function: <code>ip6_nh_lookup_table</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81844c0b)
Location: net/ipv6/route.c:1775
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8187698a)
Location: net/ipv6/route.c:1793
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189c0fc)
Location: net/ipv6/route.c:1782
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191edc4)
Location: net/ipv6/route.c:2473
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81976890)
Location: net/ipv6/route.c:2748
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81976890-ffffffff81976975: ip6_nh_lookup_table.isra.81 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff819ac470)
Location: net/ipv6/route.c:2719
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff819ac470-ffffffff819ac551: ip6_nh_lookup_table.isra.81 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff81a19ea0)
Location: net/ipv6/route.c:3184
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81a19ea0-ffffffff81a19fd6: ip6_nh_lookup_table.isra.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff81a50b10)
Location: net/ipv6/route.c:3194
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81a50b10-ffffffff81a50c46: ip6_nh_lookup_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b47f00)
Location: net/ipv6/route.c:3220
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81b47f00-ffffffff81b48034: ip6_nh_lookup_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b56ac0)
Location: net/ipv6/route.c:3204
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81b56ac0-ffffffff81b56bf4: ip6_nh_lookup_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b44660)
Location: net/ipv6/route.c:3214
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81b44660-ffffffff81b44794: ip6_nh_lookup_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0b760)
Location: net/ipv6/route.c:3326
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81c0b760-ffffffff81c0b894: ip6_nh_lookup_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81da6590)
Location: net/ipv6/route.c:3316
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81da6590-ffffffff81da66e6: ip6_nh_lookup_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81f75b30)
Location: net/ipv6/route.c:3316
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81f75b30-ffffffff81f75c86: ip6_nh_lookup_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd5bc0)
Location: net/ipv6/route.c:3309
Inline: True
```
**Symbols:**

```
ffffffff81fd5bc0-ffffffff81fd5d16: ip6_nh_lookup_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff820a3550)
Location: net/ipv6/route.c:3311
Inline: True
```
**Symbols:**

```
ffffffff820a3550-ffffffff820a36a6: ip6_nh_lookup_table.isra.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffff800010d14ad8)
Location: net/ipv6/route.c:3194
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffff800010d14ad8-ffff800010d14c10: ip6_nh_lookup_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_nh_lookup_table(struct net *net, struct fib6_config *cfg, const struct in6_addr *gw_addr, u32 tbid, int flags, struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1a70c)
Location: net/ipv6/route.c:3194
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
c0e1a70c-c0e1a840: ip6_nh_lookup_table (STB_LOCAL)
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
In net/ipv6/route.c (c000000000e41830)
Location: net/ipv6/route.c:3194
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
c000000000e41830-c000000000e419a8: ip6_nh_lookup_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_nh_lookup_table(struct net *net, struct fib6_config *cfg, const struct in6_addr *gw_addr, u32 tbid, int flags, struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085a290)
Location: net/ipv6/route.c:3194
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffe00085a290-ffffffe00085a398: ip6_nh_lookup_table (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff819f01a0)
Location: net/ipv6/route.c:3194
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff819f01a0-ffffffff819f02d6: ip6_nh_lookup_table.isra.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff819acf60)
Location: net/ipv6/route.c:3194
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff819acf60-ffffffff819ad096: ip6_nh_lookup_table.isra.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff81a5ac20)
Location: net/ipv6/route.c:3194
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81a5ac20-ffffffff81a5ad56: ip6_nh_lookup_table.isra.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff81a66ee0)
Location: net/ipv6/route.c:3194
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
**Symbols:**

```
ffffffff81a66ee0-ffffffff81a67016: ip6_nh_lookup_table.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>

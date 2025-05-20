# Function: <code>rt_set_nexthop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rt_set_nexthop(struct rtable *rt, __be32 daddr, const struct fib_result *res, struct fib_nh_exception *fnhe, struct fib_info *fi, u16 type, u32 itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817543d0)
Location: net/ipv4/route.c:1396
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
**Symbols:**

```
ffffffff817543d0-ffffffff8175464a: rt_set_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff817c0550)
Location: net/ipv4/route.c:1402
Inline: True
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
**Symbols:**

```
ffffffff817c0550-ffffffff817c07dd: rt_set_nexthop.constprop.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff817ef760)
Location: net/ipv4/route.c:1412
Inline: True
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff817ef760-ffffffff817ef9ea: rt_set_nexthop.constprop.50 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81810750)
Location: net/ipv4/route.c:1441
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff81810750-ffffffff81810a42: rt_set_nexthop.constprop.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff8188fbd0)
Location: net/ipv4/route.c:1448
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff8188fbd0-ffffffff8188fec3: rt_set_nexthop.constprop.47 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff818e4270)
Location: net/ipv4/route.c:1521
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff818e4270-ffffffff818e4587: rt_set_nexthop.constprop.53 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff81911180)
Location: net/ipv4/route.c:1521
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81911180-ffffffff819114b3: rt_set_nexthop.constprop.56 (STB_LOCAL)
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
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1560
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81973810-ffffffff81973b16: rt_set_nexthop.constprop.0 (STB_LOCAL)
ffffffff81976a98-ffffffff81976ab4: rt_set_nexthop.constprop.0.cold (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff819aa220)
Location: net/ipv4/route.c:1562
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff819aa220-ffffffff819aa53d: rt_set_nexthop.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff81a93760)
Location: net/ipv4/route.c:1566
Inline: True
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81a93760-ffffffff81a93b6d: rt_set_nexthop.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff81a9d610)
Location: net/ipv4/route.c:1572
Inline: True
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81a9d610-ffffffff81a9da1d: rt_set_nexthop.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff81a885a0)
Location: net/ipv4/route.c:1560
Inline: True
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81a885a0-ffffffff81a889aa: rt_set_nexthop.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1556
Inline: True
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81b42d00-ffffffff81b4311b: rt_set_nexthop.constprop.0 (STB_LOCAL)
ffffffff81d39e06-ffffffff81d39e3f: rt_set_nexthop.constprop.0.cold (STB_LOCAL)
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
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1569
Inline: True
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81ccf760-ffffffff81ccfba5: rt_set_nexthop.constprop.0 (STB_LOCAL)
ffffffff81f0654b-ffffffff81f06586: rt_set_nexthop.constprop.0.cold (STB_LOCAL)
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
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1568
Inline: True
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81e8f970-ffffffff81e8fdb5: rt_set_nexthop.constprop.0 (STB_LOCAL)
ffffffff820ae0f1-ffffffff820ae12c: rt_set_nexthop.constprop.0.cold (STB_LOCAL)
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
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1568
Inline: True
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81eee070-ffffffff81eee4cf: rt_set_nexthop.isra.0 (STB_LOCAL)
ffffffff8212f5ef-ffffffff8212f62a: rt_set_nexthop.isra.0.cold (STB_LOCAL)
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
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1570
Inline: True
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81fb21d0-ffffffff81fb262f: rt_set_nexthop.isra.0 (STB_LOCAL)
ffffffff822113ac-ffffffff822113e7: rt_set_nexthop.isra.0.cold (STB_LOCAL)
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
In net/ipv4/route.c (ffff800010c5a430)
Location: net/ipv4/route.c:1562
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffff800010c5a430-ffff800010c5a80c: rt_set_nexthop.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (c0d69a28)
Location: net/ipv4/route.c:1562
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
c0d69a28-c0d69d80: rt_set_nexthop.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (c000000000d5bf30)
Location: net/ipv4/route.c:1562
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
c000000000d5bf30-c000000000d5c398: rt_set_nexthop.isra.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffe0007c3996)
Location: net/ipv4/route.c:1562
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffe0007c3996-ffffffe0007c3c7c: rt_set_nexthop.isra.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff8194a090)
Location: net/ipv4/route.c:1562
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff8194a090-ffffffff8194a3ad: rt_set_nexthop.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff81903b80)
Location: net/ipv4/route.c:1562
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81903b80-ffffffff81903e9d: rt_set_nexthop.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff819b4860)
Location: net/ipv4/route.c:1562
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff819b4860-ffffffff819b4b7d: rt_set_nexthop.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff819bdfa0)
Location: net/ipv4/route.c:1562
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff819bdfa0-ffffffff819be2bd: rt_set_nexthop.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>

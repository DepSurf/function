# Function: <code>rt6_device_match</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d5052)
Location: net/ipv6/route.c:465
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81843579)
Location: net/ipv6/route.c:467
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
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
In net/ipv6/route.c (ffffffff818752e9)
Location: net/ipv6/route.c:469
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
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
In net/ipv6/route.c (ffffffff8189a13a)
Location: net/ipv6/route.c:488
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
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
In net/ipv6/route.c (ffffffff8191d284)
Location: net/ipv6/route.c:493
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8197621e)
Location: net/ipv6/route.c:465
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819abe3e)
Location: net/ipv6/route.c:467
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a19679)
Location: net/ipv6/route.c:533
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a502d9)
Location: net/ipv6/route.c:535
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rt6_device_match(struct net *net, struct fib6_result *res, const struct in6_addr *saddr, int oif, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b442d0)
Location: net/ipv6/route.c:538
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81b442d0-ffffffff81b445f7: rt6_device_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rt6_device_match(struct net *net, struct fib6_result *res, const struct in6_addr *saddr, int oif, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b52bd0)
Location: net/ipv6/route.c:521
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81b52bd0-ffffffff81b52ef7: rt6_device_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rt6_device_match(struct net *net, struct fib6_result *res, const struct in6_addr *saddr, int oif, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b40560)
Location: net/ipv6/route.c:524
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81b40560-ffffffff81b40887: rt6_device_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rt6_device_match(struct net *net, struct fib6_result *res, const struct in6_addr *saddr, int oif, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:524
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81c086c0-ffffffff81c08a2c: rt6_device_match (STB_LOCAL)
ffffffff81d3fdd8-ffffffff81d3fef9: rt6_device_match.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rt6_device_match(struct net *net, struct fib6_result *res, const struct in6_addr *saddr, int oif, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:526
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81da2270-ffffffff81da25c5: rt6_device_match (STB_LOCAL)
ffffffff81f0c706-ffffffff81f0c826: rt6_device_match.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rt6_device_match(struct net *net, struct fib6_result *res, const struct in6_addr *saddr, int oif, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:526
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81f71620-ffffffff81f71975: rt6_device_match (STB_LOCAL)
ffffffff820b3d57-ffffffff820b3e77: rt6_device_match.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rt6_device_match(struct net *net, struct fib6_result *res, const struct in6_addr *saddr, int oif, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:525
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81fd16f0-ffffffff81fd1a5a: rt6_device_match (STB_LOCAL)
ffffffff82134e6c-ffffffff82134f4c: rt6_device_match.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rt6_device_match(struct net *net, struct fib6_result *res, const struct in6_addr *saddr, int oif, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:527
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff8209ffa0-ffffffff820a030a: rt6_device_match (STB_LOCAL)
ffffffff82216972-ffffffff82216a52: rt6_device_match.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d14240)
Location: net/ipv6/route.c:535
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e19dd8)
Location: net/ipv6/route.c:535
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e40e24)
Location: net/ipv6/route.c:535
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000859b7a)
Location: net/ipv6/route.c:535
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ef969)
Location: net/ipv6/route.c:535
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ac729)
Location: net/ipv6/route.c:535
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5a3e9)
Location: net/ipv6/route.c:535
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a66657)
Location: net/ipv6/route.c:535
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route_lookup
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

# Function: <code>inet6_rt_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct rt6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d91d0)
Location: net/ipv6/route.c:3318
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_del
```
**Symbols:**

```
ffffffff817d91d0-ffffffff817d933d: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct rt6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81847120)
Location: net/ipv6/route.c:3386
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81847120-ffffffff81847290: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct rt6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81878f60)
Location: net/ipv6/route.c:3457
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81878f60-ffffffff818790d0: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct rt6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189e1a0)
Location: net/ipv6/route.c:3680
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_mpath_notify
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff8189e1a0-ffffffff8189e2dd: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct rt6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81920780)
Location: net/ipv6/route.c:4380
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_mpath_notify
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81920780-ffffffff819208bd: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81978ad0)
Location: net/ipv6/route.c:4981
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_mpath_notify
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81978ad0-ffffffff81978c07: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ae750)
Location: net/ipv6/route.c:4978
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_mpath_notify
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff819ae750-ffffffff819ae887: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:5899
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_mpath_notify
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81a1d2f2-ffffffff81a1d30d: inet6_rt_notify.cold (STB_LOCAL)
ffffffff81a1c710-ffffffff81a1c83e: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a53390)
Location: net/ipv6/route.c:5913
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_mpath_notify
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81a53390-ffffffff81a534be: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4a920)
Location: net/ipv6/route.c:6001
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81b4a920-ffffffff81b4aa4b: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b595b0)
Location: net/ipv6/route.c:5990
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81b595b0-ffffffff81b596db: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b47670)
Location: net/ipv6/route.c:6009
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81b47670-ffffffff81b4779b: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0e8f0)
Location: net/ipv6/route.c:6168
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81c0e8f0-ffffffff81c0ea1b: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da9af0)
Location: net/ipv6/route.c:6161
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81da9af0-ffffffff81da9c56: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f792b0)
Location: net/ipv6/route.c:6162
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81f792b0-ffffffff81f79416: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd94c0)
Location: net/ipv6/route.c:6160
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81fd94c0-ffffffff81fd9626: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a6e50)
Location: net/ipv6/route.c:6153
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff820a6e50-ffffffff820a6fb6: inet6_rt_notify (STB_GLOBAL)
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
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d17520)
Location: net/ipv6/route.c:5913
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_mpath_notify
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffff800010d17520-ffff800010d17674: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1d0c8)
Location: net/ipv6/route.c:5913
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_mpath_notify
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
c0e1d0c8-c0e1d210: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e44f00)
Location: net/ipv6/route.c:5913
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_mpath_notify
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
c000000000e44f00-c000000000e450b8: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085c5bc)
Location: net/ipv6/route.c:5913
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_mpath_notify
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffe00085c5bc-ffffffe00085c6d0: inet6_rt_notify (STB_GLOBAL)
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
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819f2a20)
Location: net/ipv6/route.c:5913
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_mpath_notify
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff819f2a20-ffffffff819f2b4e: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819af7e0)
Location: net/ipv6/route.c:5913
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_mpath_notify
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff819af7e0-ffffffff819af90e: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5d4a0)
Location: net/ipv6/route.c:5913
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_mpath_notify
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81a5d4a0-ffffffff81a5d5ce: inet6_rt_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct fib6_info *rt, struct nl_info *info, unsigned int nlm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a698b0)
Location: net/ipv6/route.c:5913
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_mpath_notify
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81a698b0-ffffffff81a699de: inet6_rt_notify (STB_GLOBAL)
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

# Function: <code>rt6_add_dflt_router</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rt6_info *rt6_add_dflt_router(const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d8170)
Location: net/ipv6/route.c:2333
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff817d8170-ffffffff817d8240: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rt6_info *rt6_add_dflt_router(const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff818469d0)
Location: net/ipv6/route.c:2404
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff818469d0-ffffffff81846aa0: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rt6_info *rt6_add_dflt_router(const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81878750)
Location: net/ipv6/route.c:2432
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81878750-ffffffff8187883f: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rt6_info *rt6_add_dflt_router(const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189d9a0)
Location: net/ipv6/route.c:2515
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff8189d9a0-ffffffff8189daaa: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rt6_info *rt6_add_dflt_router(const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81920030)
Location: net/ipv6/route.c:3213
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81920030-ffffffff81920137: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81978220)
Location: net/ipv6/route.c:3553
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81978220-ffffffff8197832b: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ade10)
Location: net/ipv6/route.c:3533
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff819ade10-ffffffff819adf1b: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a1bbb0)
Location: net/ipv6/route.c:4184
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a1bbb0-ffffffff81a1bcbc: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a52830)
Location: net/ipv6/route.c:4197
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a52830-ffffffff81a5293c: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4a0e0)
Location: net/ipv6/route.c:4250
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81b4a0e0-ffffffff81b4a1ec: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b58d30)
Location: net/ipv6/route.c:4234
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81b58d30-ffffffff81b58e48: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref, u32 defrtr_usr_metric);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b46950)
Location: net/ipv6/route.c:4248
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81b46950-ffffffff81b46a75: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref, u32 defrtr_usr_metric);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0db90)
Location: net/ipv6/route.c:4378
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81c0db90-ffffffff81c0dcb5: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref, u32 defrtr_usr_metric);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da8b80)
Location: net/ipv6/route.c:4354
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81da8b80-ffffffff81da8cbc: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref, u32 defrtr_usr_metric);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f78270)
Location: net/ipv6/route.c:4354
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81f78270-ffffffff81f783ac: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref, u32 defrtr_usr_metric);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd8470)
Location: net/ipv6/route.c:4352
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81fd8470-ffffffff81fd85ac: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref, u32 defrtr_usr_metric);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a5df0)
Location: net/ipv6/route.c:4354
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff820a5df0-ffffffff820a5f2c: rt6_add_dflt_router (STB_GLOBAL)
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
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d16738)
Location: net/ipv6/route.c:4197
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffff800010d16738-ffff800010d16864: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1c440)
Location: net/ipv6/route.c:4197
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
c0e1c440-c0e1c550: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e43ee0)
Location: net/ipv6/route.c:4197
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
c000000000e43ee0-c000000000e44030: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085bb8c)
Location: net/ipv6/route.c:4197
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffe00085bb8c-ffffffe00085bc78: rt6_add_dflt_router (STB_GLOBAL)
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
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819f1ec0)
Location: net/ipv6/route.c:4197
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff819f1ec0-ffffffff819f1fcc: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819aec80)
Location: net/ipv6/route.c:4197
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff819aec80-ffffffff819aed8c: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5c940)
Location: net/ipv6/route.c:4197
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a5c940-ffffffff81a5ca4c: rt6_add_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fib6_info *rt6_add_dflt_router(struct net *net, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a68d00)
Location: net/ipv6/route.c:4197
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a68d00-ffffffff81a68e1d: rt6_add_dflt_router (STB_GLOBAL)
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
<b>Param reordered. </b>
<code>gwaddr, dev, pref</code> ➡️ <code>net, gwaddr, dev, pref</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct rt6_info *</code> ➡️ <code>struct fib6_info *</code>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 defrtr_usr_metric</code>
</li>
</ul>
</details>
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

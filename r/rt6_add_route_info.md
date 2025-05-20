# Function: <code>rt6_add_route_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rt6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, int ifindex, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d7650)
Location: net/ipv6/route.c:2281
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff817d7650-ffffffff817d775c: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rt6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, int ifindex, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81845d80)
Location: net/ipv6/route.c:2352
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81845d80-ffffffff81845e8c: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rt6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81877ae0)
Location: net/ipv6/route.c:2378
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81877ae0-ffffffff81877bea: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rt6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189ccb0)
Location: net/ipv6/route.c:2460
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff8189ccb0-ffffffff8189cddb: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rt6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191fa10)
Location: net/ipv6/route.c:3158
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff8191fa10-ffffffff8191fb3b: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81977cb0)
Location: net/ipv6/route.c:3495
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81977cb0-ffffffff81977dcc: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ad8a0)
Location: net/ipv6/route.c:3475
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff819ad8a0-ffffffff819ad9bc: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a1b610)
Location: net/ipv6/route.c:4119
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81a1b610-ffffffff81a1b72d: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a52290)
Location: net/ipv6/route.c:4132
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81a52290-ffffffff81a523ad: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b499c0)
Location: net/ipv6/route.c:4185
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81b499c0-ffffffff81b49add: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b585d0)
Location: net/ipv6/route.c:4169
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81b585d0-ffffffff81b586ff: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b462f0)
Location: net/ipv6/route.c:4183
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81b462f0-ffffffff81b4641f: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0d530)
Location: net/ipv6/route.c:4313
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81c0d530-ffffffff81c0d65f: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da84e0)
Location: net/ipv6/route.c:4289
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81da84e0-ffffffff81da8625: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f77b90)
Location: net/ipv6/route.c:4289
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81f77b90-ffffffff81f77cd5: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd7d10)
Location: net/ipv6/route.c:4287
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81fd7d10-ffffffff81fd7e55: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a5690)
Location: net/ipv6/route.c:4289
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff820a5690-ffffffff820a57d5: rt6_add_route_info (STB_LOCAL)
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
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d16238)
Location: net/ipv6/route.c:4132
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffff800010d16238-ffff800010d16370: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1bf04)
Location: net/ipv6/route.c:4132
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
c0e1bf04-c0e1c01c: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e437e0)
Location: net/ipv6/route.c:4132
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
c000000000e437e0-c000000000e43940: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085b724)
Location: net/ipv6/route.c:4132
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffe00085b724-ffffffe00085b836: rt6_add_route_info (STB_LOCAL)
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
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819f1920)
Location: net/ipv6/route.c:4132
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff819f1920-ffffffff819f1a3d: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ae6e0)
Location: net/ipv6/route.c:4132
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff819ae6e0-ffffffff819ae7fd: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5c3a0)
Location: net/ipv6/route.c:4132
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81a5c3a0-ffffffff81a5c4bd: rt6_add_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fib6_info *rt6_add_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev, unsigned int pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a68720)
Location: net/ipv6/route.c:4132
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81a68720-ffffffff81a68854: rt6_add_route_info (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net_device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>int ifindex</code>
</li>
</ul>
</details>
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

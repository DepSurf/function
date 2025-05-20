# Function: <code>rt6_get_dflt_router</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rt6_info *rt6_get_dflt_router(const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d7db0)
Location: net/ipv6/route.c:2311
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff817d7db0-ffffffff817d7e54: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rt6_info *rt6_get_dflt_router(const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81846610)
Location: net/ipv6/route.c:2382
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81846610-ffffffff818466b4: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rt6_info *rt6_get_dflt_router(const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81878390)
Location: net/ipv6/route.c:2409
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81878390-ffffffff81878444: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rt6_info *rt6_get_dflt_router(const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189d5c0)
Location: net/ipv6/route.c:2492
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff8189d5c0-ffffffff8189d6a1: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rt6_info *rt6_get_dflt_router(const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191fc70)
Location: net/ipv6/route.c:3190
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff8191fc70-ffffffff8191fd40: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81977e30)
Location: net/ipv6/route.c:3528
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81977e30-ffffffff81977ee8: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ada20)
Location: net/ipv6/route.c:3508
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff819ada20-ffffffff819adad8: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a1b790)
Location: net/ipv6/route.c:4152
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a1b790-ffffffff81a1b854: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a52410)
Location: net/ipv6/route.c:4165
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a52410-ffffffff81a524d4: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b49ce0)
Location: net/ipv6/route.c:4218
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81b49ce0-ffffffff81b49db0: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b58910)
Location: net/ipv6/route.c:4202
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81b58910-ffffffff81b589f6: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b46500)
Location: net/ipv6/route.c:4216
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81b46500-ffffffff81b465e2: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0d740)
Location: net/ipv6/route.c:4346
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81c0d740-ffffffff81c0d822: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da8720)
Location: net/ipv6/route.c:4322
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81da8720-ffffffff81da880d: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f77df0)
Location: net/ipv6/route.c:4322
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81f77df0-ffffffff81f77edd: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd7f70)
Location: net/ipv6/route.c:4320
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81fd7f70-ffffffff81fd8052: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a58f0)
Location: net/ipv6/route.c:4322
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff820a58f0-ffffffff820a59d2: rt6_get_dflt_router (STB_GLOBAL)
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
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d163d8)
Location: net/ipv6/route.c:4165
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffff800010d163d8-ffff800010d164a4: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1c090)
Location: net/ipv6/route.c:4165
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
c0e1c090-c0e1c178: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e439c0)
Location: net/ipv6/route.c:4165
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
c000000000e439c0-c000000000e43af8: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085b876)
Location: net/ipv6/route.c:4165
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffe00085b876-ffffffe00085b94a: rt6_get_dflt_router (STB_GLOBAL)
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
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819f1aa0)
Location: net/ipv6/route.c:4165
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff819f1aa0-ffffffff819f1b64: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ae860)
Location: net/ipv6/route.c:4165
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff819ae860-ffffffff819ae924: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5c520)
Location: net/ipv6/route.c:4165
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a5c520-ffffffff81a5c5e4: rt6_get_dflt_router (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fib6_info *rt6_get_dflt_router(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a688c0)
Location: net/ipv6/route.c:4165
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a688c0-ffffffff81a689b0: rt6_get_dflt_router (STB_GLOBAL)
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
<code>addr, dev</code> ➡️ <code>net, addr, dev</code>
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

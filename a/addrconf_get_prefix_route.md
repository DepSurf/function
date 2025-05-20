# Function: <code>addrconf_get_prefix_route</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rt6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817c9bb0)
Location: net/ipv6/addrconf.c:2182
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff817c9bb0-ffffffff817c9c9c: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rt6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81836d50)
Location: net/ipv6/addrconf.c:2232
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff81836d50-ffffffff81836e3c: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rt6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81868910)
Location: net/ipv6/addrconf.c:2247
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff81868910-ffffffff818689fc: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rt6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8188cfc0)
Location: net/ipv6/addrconf.c:2302
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff8188cfc0-ffffffff8188d0d1: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rt6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8190fb70)
Location: net/ipv6/addrconf.c:2326
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff8190fb70-ffffffff8190fc4f: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819653c0)
Location: net/ipv6/addrconf.c:2351
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff819653c0-ffffffff819654a6: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199a840)
Location: net/ipv6/addrconf.c:2367
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff8199a840-ffffffff8199a926: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags, bool no_gw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a067c0)
Location: net/ipv6/addrconf.c:2400
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff81a067c0-ffffffff81a068c9: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags, bool no_gw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a3d330)
Location: net/ipv6/addrconf.c:2402
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff81a3d330-ffffffff81a3d439: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags, bool no_gw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b331d0)
Location: net/ipv6/addrconf.c:2391
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff81b331d0-ffffffff81b332ee: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags, bool no_gw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b41af0)
Location: net/ipv6/addrconf.c:2417
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff81b41af0-ffffffff81b41c19: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags, bool no_gw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b2f7e0)
Location: net/ipv6/addrconf.c:2419
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff81b2f7e0-ffffffff81b2f901: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags, bool no_gw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bf5b60)
Location: net/ipv6/addrconf.c:2426
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff81bf5b60-ffffffff81bf5c81: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags, bool no_gw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d8ed30)
Location: net/ipv6/addrconf.c:2429
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff81d8ed30-ffffffff81d8ee67: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags, bool no_gw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f5d220)
Location: net/ipv6/addrconf.c:2429
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff81f5d220-ffffffff81f5d357: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags, bool no_gw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fbcf40)
Location: net/ipv6/addrconf.c:2428
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff81fbcf40-ffffffff81fbd072: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags, bool no_gw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8208a370)
Location: net/ipv6/addrconf.c:2456
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff8208a370-ffffffff8208a4a2: addrconf_get_prefix_route (STB_LOCAL)
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
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags, bool no_gw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010cfe500)
Location: net/ipv6/addrconf.c:2402
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffff800010cfe500-ffff800010cfe600: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags, bool no_gw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e0682c)
Location: net/ipv6/addrconf.c:2402
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
c0e0682c-c0e0692c: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags, bool no_gw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e27080)
Location: net/ipv6/addrconf.c:2402
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
c000000000e27080-c000000000e271f8: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags, bool no_gw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe000848ece)
Location: net/ipv6/addrconf.c:2402
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffe000848ece-ffffffe000848fa0: addrconf_get_prefix_route (STB_LOCAL)
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
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags, bool no_gw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819dc9c0)
Location: net/ipv6/addrconf.c:2402
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff819dc9c0-ffffffff819dcac9: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags, bool no_gw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81999780)
Location: net/ipv6/addrconf.c:2402
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff81999780-ffffffff81999889: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags, bool no_gw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a47440)
Location: net/ipv6/addrconf.c:2402
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff81a47440-ffffffff81a47549: addrconf_get_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fib6_info *addrconf_get_prefix_route(const struct in6_addr *pfx, int plen, const struct net_device *dev, u32 flags, u32 noflags, bool no_gw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a531f0)
Location: net/ipv6/addrconf.c:2402
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
**Symbols:**

```
ffffffff81a531f0-ffffffff81a5331d: addrconf_get_prefix_route (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool no_gw</code>
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

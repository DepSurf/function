# Function: <code>ip6_dst_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d39f0)
Location: net/ipv6/route.c:340
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:addrconf_dst_alloc
```
**Symbols:**

```
ffffffff817d39f0-ffffffff817d3a86: ip6_dst_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81840db0)
Location: net/ipv6/route.c:341
Inline: False
Direct callers:
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
```
**Symbols:**

```
ffffffff81840db0-ffffffff81840e44: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81872a80)
Location: net/ipv6/route.c:343
Inline: False
Direct callers:
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
```
**Symbols:**

```
ffffffff81872a80-ffffffff81872b16: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81897790)
Location: net/ipv6/route.c:364
Inline: False
Direct callers:
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
```
**Symbols:**

```
ffffffff81897790-ffffffff81897825: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81918a80)
Location: net/ipv6/route.c:372
Inline: False
Direct callers:
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
```
**Symbols:**

```
ffffffff81918a80-ffffffff81918ac9: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819706f0)
Location: net/ipv6/route.c:350
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffff819706f0-ffffffff8197073d: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a6320)
Location: net/ipv6/route.c:352
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffff819a6320-ffffffff819a636d: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a12940)
Location: net/ipv6/route.c:350
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffff81a12940-ffffffff81a1298c: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a49530)
Location: net/ipv6/route.c:352
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffff81a49530-ffffffff81a4957c: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b41c50)
Location: net/ipv6/route.c:352
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffff81b41c50-ffffffff81b41cd3: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b50730)
Location: net/ipv6/route.c:335
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffff81b50730-ffffffff81b507b3: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3e020)
Location: net/ipv6/route.c:338
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffff81b3e020-ffffffff81b3e0a3: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c04900)
Location: net/ipv6/route.c:338
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffff81c04900-ffffffff81c04983: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da73e3)
Location: net/ipv6/route.c:341
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffff81d9dfc0-ffffffff81d9e01c: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f76a13)
Location: net/ipv6/route.c:341
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffff81f6bfb0-ffffffff81f6c00c: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd6a43)
Location: net/ipv6/route.c:340
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffff81fcc0e0-ffffffff81fcc13c: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a43c3)
Location: net/ipv6/route.c:340
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffff82099820-ffffffff82099873: ip6_dst_alloc (STB_GLOBAL)
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
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0ed78)
Location: net/ipv6/route.c:352
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffff800010d0ed78-ffff800010d0ee08: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1273c)
Location: net/ipv6/route.c:352
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
c0e1273c-c0e127a8: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e375f0)
Location: net/ipv6/route.c:352
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
c000000000e375f0-c000000000e37674: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe0008537e6)
Location: net/ipv6/route.c:352
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffe0008537e6-ffffffe000853856: ip6_dst_alloc (STB_GLOBAL)
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
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819e8bc0)
Location: net/ipv6/route.c:352
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffff819e8bc0-ffffffff819e8c0c: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a5980)
Location: net/ipv6/route.c:352
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffff819a5980-ffffffff819a59cc: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a53640)
Location: net/ipv6/route.c:352
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffff81a53640-ffffffff81a5368c: ip6_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rt6_info *ip6_dst_alloc(struct net *net, struct net_device *dev, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5f590)
Location: net/ipv6/route.c:352
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffff81a5f590-ffffffff81a5f5dc: ip6_dst_alloc (STB_GLOBAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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

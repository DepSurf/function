# Function: <code>lwtunnel_build_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int lwtunnel_build_state(struct net_device *dev, u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff8173e080)
Location: net/core/lwtunnel.c:74
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff8173e080-ffffffff8173e0c9: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int lwtunnel_build_state(struct net_device *dev, u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff817aa980)
Location: net/core/lwtunnel.c:99
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff817aa980-ffffffff817aaa60: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int lwtunnel_build_state(struct net_device *dev, u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff817d9500)
Location: net/core/lwtunnel.c:104
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff817d9500-ffffffff817d95b4: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_build_state(u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff817f8940)
Location: net/core/lwtunnel.c:104
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff817f8940-ffffffff817f8a13: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_build_state(u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81876220)
Location: net/core/lwtunnel.c:106
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81876220-ffffffff818762f8: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int lwtunnel_build_state(u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818c7750)
Location: net/core/lwtunnel.c:106
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff818c7750-ffffffff818c782f: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int lwtunnel_build_state(u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818f0890)
Location: net/core/lwtunnel.c:106
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff818f0890-ffffffff818f096f: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int lwtunnel_build_state(u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff819421b0)
Location: net/core/lwtunnel.c:101
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
**Symbols:**

```
ffffffff819421b0-ffffffff8194228d: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int lwtunnel_build_state(u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff819770f0)
Location: net/core/lwtunnel.c:101
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
**Symbols:**

```
ffffffff819770f0-ffffffff819771cd: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int lwtunnel_build_state(struct net *net, u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81a4beb0)
Location: net/core/lwtunnel.c:103
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
**Symbols:**

```
ffffffff81a4beb0-ffffffff81a4bf9a: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int lwtunnel_build_state(struct net *net, u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81a51ab0)
Location: net/core/lwtunnel.c:103
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
**Symbols:**

```
ffffffff81a51ab0-ffffffff81a51bb7: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int lwtunnel_build_state(struct net *net, u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81a37360)
Location: net/core/lwtunnel.c:103
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
**Symbols:**

```
ffffffff81a37360-ffffffff81a37483: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int lwtunnel_build_state(struct net *net, u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81aecfd0)
Location: net/core/lwtunnel.c:108
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
**Symbols:**

```
ffffffff81aecfd0-ffffffff81aed111: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int lwtunnel_build_state(struct net *net, u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81c6fc20)
Location: net/core/lwtunnel.c:108
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_init
```
**Symbols:**

```
ffffffff81c6fc20-ffffffff81c6fda9: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int lwtunnel_build_state(struct net *net, u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81e27b40)
Location: net/core/lwtunnel.c:111
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_init
```
**Symbols:**

```
ffffffff81e27b40-ffffffff81e27cc9: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int lwtunnel_build_state(struct net *net, u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81e9d150)
Location: net/core/lwtunnel.c:111
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_init
```
**Symbols:**

```
ffffffff81e9d150-ffffffff81e9d2d9: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int lwtunnel_build_state(struct net *net, u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81f5f8d0)
Location: net/core/lwtunnel.c:111
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_common_init
```
**Symbols:**

```
ffffffff81f5f8d0-ffffffff81f5fa59: lwtunnel_build_state (STB_GLOBAL)
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
int lwtunnel_build_state(u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffff800010c1d9e0)
Location: net/core/lwtunnel.c:101
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
**Symbols:**

```
ffff800010c1d9e0-ffff800010c1daf0: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int lwtunnel_build_state(u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (c0d35690)
Location: net/core/lwtunnel.c:101
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
**Symbols:**

```
c0d35690-c0d35780: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int lwtunnel_build_state(u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (c000000000d0ee30)
Location: net/core/lwtunnel.c:101
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
**Symbols:**

```
c000000000d0ee30-c000000000d0efc0: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int lwtunnel_build_state(u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffe0007975f6)
Location: net/core/lwtunnel.c:101
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
**Symbols:**

```
ffffffe0007975f6-ffffffe0007976b4: lwtunnel_build_state (STB_GLOBAL)
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
int lwtunnel_build_state(u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81916f60)
Location: net/core/lwtunnel.c:101
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
**Symbols:**

```
ffffffff81916f60-ffffffff8191703d: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int lwtunnel_build_state(u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818d0d10)
Location: net/core/lwtunnel.c:101
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
**Symbols:**

```
ffffffff818d0d10-ffffffff818d0ded: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int lwtunnel_build_state(u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff819680f0)
Location: net/core/lwtunnel.c:101
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
**Symbols:**

```
ffffffff819680f0-ffffffff819681cd: lwtunnel_build_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int lwtunnel_build_state(u16 encap_type, struct nlattr *encap, unsigned int family, const void *cfg, struct lwtunnel_state **lws, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff8198a380)
Location: net/core/lwtunnel.c:101
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
**Symbols:**

```
ffffffff8198a380-ffffffff8198a46d: lwtunnel_build_state (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
<li>
<b>Param removed. </b>
<code>struct net_device *dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, encap_type, encap, family, cfg, lws</code> ➡️ <code>encap_type, encap, family, cfg, lws, extack</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>encap_type, encap, family, cfg, lws, extack</code> ➡️ <code>net, encap_type, encap, family, cfg, lws, extack</code>
</li>
</ul>
</details>
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

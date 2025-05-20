# Function: <code>addrconf_f6i_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81978610)
Location: net/ipv6/route.c:3741
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff81978610-ffffffff819786fa: addrconf_f6i_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ae200)
Location: net/ipv6/route.c:3721
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff819ae200-ffffffff819ae2fb: addrconf_f6i_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a1c030)
Location: net/ipv6/route.c:4383
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff81a1c030-ffffffff81a1c149: addrconf_f6i_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a52cb0)
Location: net/ipv6/route.c:4396
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff81a52cb0-ffffffff81a52dc9: addrconf_f6i_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4a320)
Location: net/ipv6/route.c:4437
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:fixup_permanent_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff81b4a320-ffffffff81b4a439: addrconf_f6i_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b58f90)
Location: net/ipv6/route.c:4421
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:fixup_permanent_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff81b58f90-ffffffff81b590b6: addrconf_f6i_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b46e90)
Location: net/ipv6/route.c:4436
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff81b46e90-ffffffff81b46faa: addrconf_f6i_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0e0e0)
Location: net/ipv6/route.c:4566
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff81c0e0e0-ffffffff81c0e1fa: addrconf_f6i_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da9130)
Location: net/ipv6/route.c:4546
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff81da9130-ffffffff81da92a4: addrconf_f6i_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f78850)
Location: net/ipv6/route.c:4546
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff81f78850-ffffffff81f789c4: addrconf_f6i_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd8a40)
Location: net/ipv6/route.c:4544
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff81fd8a40-ffffffff81fd8bb4: addrconf_f6i_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a63c0)
Location: net/ipv6/route.c:4546
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff820a63c0-ffffffff820a6546: addrconf_f6i_alloc (STB_GLOBAL)
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
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d16cb8)
Location: net/ipv6/route.c:4396
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffff800010d16cb8-ffff800010d16dfc: addrconf_f6i_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1c928)
Location: net/ipv6/route.c:4396
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
c0e1c928-c0e1ca2c: addrconf_f6i_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e44510)
Location: net/ipv6/route.c:4396
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
c000000000e44510-c000000000e44680: addrconf_f6i_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085bfa2)
Location: net/ipv6/route.c:4396
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffe00085bfa2-ffffffe00085c090: addrconf_f6i_alloc (STB_GLOBAL)
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
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819f2340)
Location: net/ipv6/route.c:4396
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff819f2340-ffffffff819f2459: addrconf_f6i_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819af100)
Location: net/ipv6/route.c:4396
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff819af100-ffffffff819af219: addrconf_f6i_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5cdc0)
Location: net/ipv6/route.c:4396
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff81a5cdc0-ffffffff81a5ced9: addrconf_f6i_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fib6_info *addrconf_f6i_alloc(struct net *net, struct inet6_dev *idev, const struct in6_addr *addr, bool anycast, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a69190)
Location: net/ipv6/route.c:4396
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff81a69190-ffffffff81a692bf: addrconf_f6i_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
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

# Function: <code>addrconf_prefix_rcv_add_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8183d850)
Location: net/ipv6/addrconf.c:2379
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff8183d850-ffffffff8183da7a: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186f460)
Location: net/ipv6/addrconf.c:2394
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff8186f460-ffffffff8186f68a: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81894220)
Location: net/ipv6/addrconf.c:2449
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81894220-ffffffff81894442: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81915670)
Location: net/ipv6/addrconf.c:2473
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81915670-ffffffff819158bc: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8196cc60)
Location: net/ipv6/addrconf.c:2499
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff8196cc60-ffffffff8196cf01: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819a2790)
Location: net/ipv6/addrconf.c:2515
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff819a2790-ffffffff819a2a31: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a0ee10)
Location: net/ipv6/addrconf.c:2555
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81a0ee10-ffffffff81a0f09b: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a45b50)
Location: net/ipv6/addrconf.c:2557
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81a45b50-ffffffff81a45ddb: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b3c960)
Location: net/ipv6/addrconf.c:2546
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81b3c960-ffffffff81b3cc44: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b4b670)
Location: net/ipv6/addrconf.c:2573
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81b4b670-ffffffff81b4b95f: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b39240)
Location: net/ipv6/addrconf.c:2575
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81b39240-ffffffff81b39504: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bff9e0)
Location: net/ipv6/addrconf.c:2582
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81bff9e0-ffffffff81bffcb7: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d99480)
Location: net/ipv6/addrconf.c:2585
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81d99480-ffffffff81d99776: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f681b0)
Location: net/ipv6/addrconf.c:2585
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81f681b0-ffffffff81f684a6: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fc82a0)
Location: net/ipv6/addrconf.c:2590
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81fc82a0-ffffffff81fc8596: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff820959d0)
Location: net/ipv6/addrconf.c:2618
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff820959d0-ffffffff82095cc9: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
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
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d08508)
Location: net/ipv6/addrconf.c:2557
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffff800010d08508-ffff800010d08874: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e0ecf8)
Location: net/ipv6/addrconf.c:2557
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
c0e0ecf8-c0e0ef74: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e32a10)
Location: net/ipv6/addrconf.c:2557
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
c000000000e32a10-c000000000e32d54: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe0008505ac)
Location: net/ipv6/addrconf.c:2557
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffe0008505ac-ffffffe0008507c8: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
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
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819e51e0)
Location: net/ipv6/addrconf.c:2557
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff819e51e0-ffffffff819e546b: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819a1fa0)
Location: net/ipv6/addrconf.c:2557
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff819a1fa0-ffffffff819a222b: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a4fc60)
Location: net/ipv6/addrconf.c:2557
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81a4fc60-ffffffff81a4feeb: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int addrconf_prefix_rcv_add_addr(struct net *net, struct net_device *dev, const struct prefix_info *pinfo, struct inet6_dev *in6_dev, const struct in6_addr *addr, int addr_type, u32 addr_flags, bool sllao, bool tokenized, __u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a5bc40)
Location: net/ipv6/addrconf.c:2557
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81a5bc40-ffffffff81a5bee4: addrconf_prefix_rcv_add_addr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

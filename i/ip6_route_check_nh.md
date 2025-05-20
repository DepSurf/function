# Function: <code>ip6_route_check_nh</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819771b2)
Location: net/ipv6/route.c:2807
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
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
In net/ipv6/route.c (ffffffff819acde8)
Location: net/ipv6/route.c:2784
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6_route_check_nh(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a19fe0)
Location: net/ipv6/route.c:3236
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81a19fe0-ffffffff81a1a1bd: ip6_route_check_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6_route_check_nh(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a50c50)
Location: net/ipv6/route.c:3246
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81a50c50-ffffffff81a50e2d: ip6_route_check_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6_route_check_nh(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b48040)
Location: net/ipv6/route.c:3272
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_validate_gw
```
**Symbols:**

```
ffffffff81b48040-ffffffff81b48241: ip6_route_check_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_route_check_nh(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b56c00)
Location: net/ipv6/route.c:3256
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_validate_gw
```
**Symbols:**

```
ffffffff81b56c00-ffffffff81b56e03: ip6_route_check_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6_route_check_nh(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b447a0)
Location: net/ipv6/route.c:3266
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_validate_gw
```
**Symbols:**

```
ffffffff81b447a0-ffffffff81b449a6: ip6_route_check_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip6_route_check_nh(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0b8a0)
Location: net/ipv6/route.c:3378
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_validate_gw
```
**Symbols:**

```
ffffffff81c0b8a0-ffffffff81c0bab5: ip6_route_check_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip6_route_check_nh(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da66f0)
Location: net/ipv6/route.c:3368
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_validate_gw
```
**Symbols:**

```
ffffffff81da66f0-ffffffff81da6930: ip6_route_check_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip6_route_check_nh(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f75ca0)
Location: net/ipv6/route.c:3368
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_validate_gw
```
**Symbols:**

```
ffffffff81f75ca0-ffffffff81f75ee0: ip6_route_check_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd5d30)
Location: net/ipv6/route.c:3361
Inline: True
```
**Symbols:**

```
ffffffff81fd5d30-ffffffff81fd5f70: ip6_route_check_nh.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff820a36c0)
Location: net/ipv6/route.c:3363
Inline: True
```
**Symbols:**

```
ffffffff820a36c0-ffffffff820a3900: ip6_route_check_nh.isra.0 (STB_LOCAL)
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
int ip6_route_check_nh(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d14c10)
Location: net/ipv6/route.c:3246
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffff800010d14c10-ffff800010d14dc4: ip6_route_check_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_route_check_nh(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1a840)
Location: net/ipv6/route.c:3246
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
c0e1a840-c0e1aa14: ip6_route_check_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6_route_check_nh(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e419b0)
Location: net/ipv6/route.c:3246
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
c000000000e419b0-c000000000e41c04: ip6_route_check_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_route_check_nh(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085a398)
Location: net/ipv6/route.c:3246
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffe00085a398-ffffffe00085a510: ip6_route_check_nh (STB_LOCAL)
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
int ip6_route_check_nh(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819f02e0)
Location: net/ipv6/route.c:3246
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff819f02e0-ffffffff819f04bd: ip6_route_check_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6_route_check_nh(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ad0a0)
Location: net/ipv6/route.c:3246
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff819ad0a0-ffffffff819ad27d: ip6_route_check_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6_route_check_nh(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5ad60)
Location: net/ipv6/route.c:3246
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81a5ad60-ffffffff81a5af3d: ip6_route_check_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6_route_check_nh(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a67020)
Location: net/ipv6/route.c:3246
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81a67020-ffffffff81a6721d: ip6_route_check_nh (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

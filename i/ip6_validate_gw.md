# Function: <code>ip6_validate_gw</code>

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
In net/ipv6/route.c (ffffffff8197700c)
Location: net/ipv6/route.c:2858
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
In net/ipv6/route.c (ffffffff819acc20)
Location: net/ipv6/route.c:2835
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a1ac30)
Location: net/ipv6/route.c:3290
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a518ab)
Location: net/ipv6/route.c:3300
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6_validate_gw(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b48250)
Location: net/ipv6/route.c:3326
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81b48250-ffffffff81b484a2: ip6_validate_gw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_validate_gw(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b56e10)
Location: net/ipv6/route.c:3310
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81b56e10-ffffffff81b5708d: ip6_validate_gw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6_validate_gw(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b449b0)
Location: net/ipv6/route.c:3320
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81b449b0-ffffffff81b44c73: ip6_validate_gw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip6_validate_gw(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0bac0)
Location: net/ipv6/route.c:3432
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81c0bac0-ffffffff81c0bd83: ip6_validate_gw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip6_validate_gw(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da6930)
Location: net/ipv6/route.c:3422
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81da6930-ffffffff81da6c0f: ip6_validate_gw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip6_validate_gw(struct net *net, struct fib6_config *cfg, struct net_device **_dev, struct inet6_dev **idev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f75ef0)
Location: net/ipv6/route.c:3422
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81f75ef0-ffffffff81f761cf: ip6_validate_gw (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff81fd5f80)
Location: net/ipv6/route.c:3416
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81fd5f80-ffffffff81fd625f: ip6_validate_gw.isra.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff820a3910)
Location: net/ipv6/route.c:3418
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff820a3910-ffffffff820a3bef: ip6_validate_gw.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d1571c)
Location: net/ipv6/route.c:3300
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1b5b4)
Location: net/ipv6/route.c:3300
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e429b8)
Location: net/ipv6/route.c:3300
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085ae28)
Location: net/ipv6/route.c:3300
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819f0f3b)
Location: net/ipv6/route.c:3300
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819adcfb)
Location: net/ipv6/route.c:3300
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5b9bb)
Location: net/ipv6/route.c:3300
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a67c79)
Location: net/ipv6/route.c:3300
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

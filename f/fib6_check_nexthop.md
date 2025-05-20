# Function: <code>fib6_check_nexthop</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int fib6_check_nexthop(struct nexthop *nh, struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819d35b0)
Location: net/ipv4/nexthop.c:561
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff819d35b0-ffffffff819d360a: fib6_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fib6_check_nexthop(struct nexthop *nh, struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a0a120)
Location: net/ipv4/nexthop.c:563
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81a0a120-ffffffff81a0a17a: fib6_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fib6_check_nexthop(struct nexthop *nh, struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afa8f0)
Location: net/ipv4/nexthop.c:629
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81afa8f0-ffffffff81afa96c: fib6_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fib6_check_nexthop(struct nexthop *nh, struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b080b0)
Location: net/ipv4/nexthop.c:757
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81b080b0-ffffffff81b0812c: fib6_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib6_check_nexthop(struct nexthop *nh, struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af41e0)
Location: net/ipv4/nexthop.c:1266
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:fib6_check_nh_list
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81af41e0-ffffffff81af428c: fib6_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fib6_check_nexthop(struct nexthop *nh, struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1266
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:fib6_check_nh_list
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81d3dd9d-ffffffff81d3ddfd: fib6_check_nexthop.cold (STB_LOCAL)
ffffffff81bb4850-ffffffff81bb494b: fib6_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fib6_check_nexthop(struct nexthop *nh, struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1267
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:fib6_check_nh_list
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81f0a662-ffffffff81f0a6e2: fib6_check_nexthop.cold (STB_LOCAL)
ffffffff81d483a0-ffffffff81d4849d: fib6_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fib6_check_nexthop(struct nexthop *nh, struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1267
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:fib6_check_nh_list
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff820b1f17-ffffffff820b1f97: fib6_check_nexthop.cold (STB_LOCAL)
ffffffff81f11930-ffffffff81f11a2d: fib6_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fib6_check_nexthop(struct nexthop *nh, struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1267
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:fib6_check_nh_list
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff821330f7-ffffffff82133177: fib6_check_nexthop.cold (STB_LOCAL)
ffffffff81f71620-ffffffff81f7171d: fib6_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fib6_check_nexthop(struct nexthop *nh, struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1290
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:fib6_check_nh_list
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff82214aa6-ffffffff82214b26: fib6_check_nexthop.cold (STB_LOCAL)
ffffffff82037d80-ffffffff82037e7d: fib6_check_nexthop (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int fib6_check_nexthop(struct nexthop *nh, struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffff800010cc3568)
Location: net/ipv4/nexthop.c:563
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffff800010cc3568-ffff800010cc3614: fib6_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fib6_check_nexthop(struct nexthop *nh, struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dced4c)
Location: net/ipv4/nexthop.c:563
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
c0dced4c-c0dcedf8: fib6_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fib6_check_nexthop(struct nexthop *nh, struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c000000000ddf180)
Location: net/ipv4/nexthop.c:563
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
c000000000ddf180-c000000000ddf218: fib6_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fib6_check_nexthop(struct nexthop *nh, struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffe000818886)
Location: net/ipv4/nexthop.c:563
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffe000818886-ffffffe000818918: fib6_check_nexthop (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int fib6_check_nexthop(struct nexthop *nh, struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819a9ec0)
Location: net/ipv4/nexthop.c:563
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff819a9ec0-ffffffff819a9f1a: fib6_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fib6_check_nexthop(struct nexthop *nh, struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81963980)
Location: net/ipv4/nexthop.c:563
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81963980-ffffffff819639da: fib6_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fib6_check_nexthop(struct nexthop *nh, struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a14760)
Location: net/ipv4/nexthop.c:563
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81a14760-ffffffff81a147ba: fib6_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fib6_check_nexthop(struct nexthop *nh, struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a1f170)
Location: net/ipv4/nexthop.c:563
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81a1f170-ffffffff81a1f1ca: fib6_check_nexthop (STB_GLOBAL)
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

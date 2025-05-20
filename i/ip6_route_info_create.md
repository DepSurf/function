# Function: <code>ip6_route_info_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rt6_info *ip6_route_info_create(struct fib6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d5f00)
Location: net/ipv6/route.c:1749
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff817d5f00-ffffffff817d66ae: ip6_route_info_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rt6_info *ip6_route_info_create(struct fib6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff818444a0)
Location: net/ipv6/route.c:1806
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff818444a0-ffffffff81844d01: ip6_route_info_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rt6_info *ip6_route_info_create(struct fib6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81876210)
Location: net/ipv6/route.c:1824
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff81876210-ffffffff81876a80: ip6_route_info_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rt6_info *ip6_route_info_create(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189b8a0)
Location: net/ipv6/route.c:1813
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff8189b8a0-ffffffff8189c281: ip6_route_info_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rt6_info *ip6_route_info_create(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191e520)
Location: net/ipv6/route.c:2504
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff8191e520-ffffffff8191ef47: ip6_route_info_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2931
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff81976980-ffffffff81977422: ip6_route_info_create (STB_LOCAL)
ffffffff81979522-ffffffff81979544: ip6_route_info_create.cold.92 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2908
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff819ac560-ffffffff819ad059: ip6_route_info_create (STB_LOCAL)
ffffffff819af102-ffffffff819af124: ip6_route_info_create.cold.93 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3534
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff81a1af40-ffffffff81a1b4e0: ip6_route_info_create (STB_LOCAL)
ffffffff81a1d2d2-ffffffff81a1d2f2: ip6_route_info_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3547
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff81a51bc0-ffffffff81a52160: ip6_route_info_create (STB_LOCAL)
ffffffff81a53f3c-ffffffff81a53f5c: ip6_route_info_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3578
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff81b49290-ffffffff81b49839: ip6_route_info_create (STB_LOCAL)
ffffffff81b4b60e-ffffffff81b4b62e: ip6_route_info_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3562
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff81b57ea0-ffffffff81b58449: ip6_route_info_create (STB_LOCAL)
ffffffff81c32d0a-ffffffff81c32d2a: ip6_route_info_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3572
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff81b45b30-ffffffff81b46159: ip6_route_info_create (STB_LOCAL)
ffffffff81c2501d-ffffffff81c2503f: ip6_route_info_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3702
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff81c0cc90-ffffffff81c0d2f4: ip6_route_info_create (STB_LOCAL)
ffffffff81d40100-ffffffff81d40137: ip6_route_info_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3678
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff81da7d10-ffffffff81da8342: ip6_route_info_create (STB_LOCAL)
ffffffff81f0ca79-ffffffff81f0cab8: ip6_route_info_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3678
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff81f77360-ffffffff81f779b6: ip6_route_info_create (STB_LOCAL)
ffffffff820b40ca-ffffffff820b40e7: ip6_route_info_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3676
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff81fd7300-ffffffff81fd7b3a: ip6_route_info_create (STB_LOCAL)
ffffffff82135184-ffffffff8213521f: ip6_route_info_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3678
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff820a4c80-ffffffff820a54ba: ip6_route_info_create (STB_LOCAL)
ffffffff82216c55-ffffffff82216cf0: ip6_route_info_create.cold (STB_LOCAL)
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
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d15b30)
Location: net/ipv6/route.c:3547
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffff800010d15b30-ffff800010d16090: ip6_route_info_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1b840)
Location: net/ipv6/route.c:3547
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
c0e1b840-c0e1bdb4: ip6_route_info_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e42e30)
Location: net/ipv6/route.c:3547
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
c000000000e42e30-c000000000e4355c: ip6_route_info_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085b134)
Location: net/ipv6/route.c:3547
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffe00085b134-ffffffe00085b5aa: ip6_route_info_create (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3547
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff819f1250-ffffffff819f17f0: ip6_route_info_create (STB_LOCAL)
ffffffff819f35cc-ffffffff819f35ec: ip6_route_info_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3547
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff819ae010-ffffffff819ae5b0: ip6_route_info_create (STB_LOCAL)
ffffffff819b038c-ffffffff819b03ac: ip6_route_info_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3547
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff81a5bcd0-ffffffff81a5c270: ip6_route_info_create (STB_LOCAL)
ffffffff81a5e04c-ffffffff81a5e06c: ip6_route_info_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct fib6_info *ip6_route_info_create(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3547
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_add
```
**Symbols:**

```
ffffffff81a68040-ffffffff81a685e0: ip6_route_info_create (STB_LOCAL)
ffffffff81a6a478-ffffffff81a6a498: ip6_route_info_create.cold (STB_LOCAL)
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
</ul>
</details>
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
<code>gfp_t gfp_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>cfg, extack</code> ➡️ <code>cfg, gfp_flags, extack</code>
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

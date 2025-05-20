# Function: <code>fib6_nh_init</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int fib6_nh_init(struct net *net, struct fib6_nh *fib6_nh, struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a1a930)
Location: net/ipv6/route.c:3378
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81a1a930-ffffffff81a1af39: fib6_nh_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib6_nh_init(struct net *net, struct fib6_nh *fib6_nh, struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a515a0)
Location: net/ipv6/route.c:3388
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81a515a0-ffffffff81a51bb8: fib6_nh_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib6_nh_init(struct net *net, struct fib6_nh *fib6_nh, struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b48d70)
Location: net/ipv6/route.c:3414
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81b48d70-ffffffff81b49283: fib6_nh_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib6_nh_init(struct net *net, struct fib6_nh *fib6_nh, struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b57990)
Location: net/ipv6/route.c:3398
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81b57990-ffffffff81b57e96: fib6_nh_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib6_nh_init(struct net *net, struct fib6_nh *fib6_nh, struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b45560)
Location: net/ipv6/route.c:3408
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81b45560-ffffffff81b45b2b: fib6_nh_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fib6_nh_init(struct net *net, struct fib6_nh *fib6_nh, struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3520
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81d400eb-ffffffff81d40100: fib6_nh_init.cold (STB_LOCAL)
ffffffff81c0c6a0-ffffffff81c0cc8c: fib6_nh_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fib6_nh_init(struct net *net, struct fib6_nh *fib6_nh, struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3510
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81f0ca64-ffffffff81f0ca79: fib6_nh_init.cold (STB_LOCAL)
ffffffff81da75c0-ffffffff81da7d0c: fib6_nh_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fib6_nh_init(struct net *net, struct fib6_nh *fib6_nh, struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3510
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff820b40b5-ffffffff820b40ca: fib6_nh_init.cold (STB_LOCAL)
ffffffff81f76c00-ffffffff81f7734c: fib6_nh_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fib6_nh_init(struct net *net, struct fib6_nh *fib6_nh, struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3507
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff8213516f-ffffffff82135184: fib6_nh_init.cold (STB_LOCAL)
ffffffff81fd6c20-ffffffff81fd72e5: fib6_nh_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fib6_nh_init(struct net *net, struct fib6_nh *fib6_nh, struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3509
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff82216c40-ffffffff82216c55: fib6_nh_init.cold (STB_LOCAL)
ffffffff820a45a0-ffffffff820a4c68: fib6_nh_init (STB_GLOBAL)
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
int fib6_nh_init(struct net *net, struct fib6_nh *fib6_nh, struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d15508)
Location: net/ipv6/route.c:3388
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffff800010d15508-ffff800010d15b30: fib6_nh_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib6_nh_init(struct net *net, struct fib6_nh *fib6_nh, struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1b19c)
Location: net/ipv6/route.c:3388
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
c0e1b19c-c0e1b840: fib6_nh_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib6_nh_init(struct net *net, struct fib6_nh *fib6_nh, struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e425b0)
Location: net/ipv6/route.c:3388
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
c000000000e425b0-c000000000e42e28: fib6_nh_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib6_nh_init(struct net *net, struct fib6_nh *fib6_nh, struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085abaa)
Location: net/ipv6/route.c:3388
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffe00085abaa-ffffffe00085b134: fib6_nh_init (STB_GLOBAL)
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
int fib6_nh_init(struct net *net, struct fib6_nh *fib6_nh, struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819f0c30)
Location: net/ipv6/route.c:3388
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff819f0c30-ffffffff819f1248: fib6_nh_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib6_nh_init(struct net *net, struct fib6_nh *fib6_nh, struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ad9f0)
Location: net/ipv6/route.c:3388
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff819ad9f0-ffffffff819ae008: fib6_nh_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib6_nh_init(struct net *net, struct fib6_nh *fib6_nh, struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5b6b0)
Location: net/ipv6/route.c:3388
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81a5b6b0-ffffffff81a5bcc8: fib6_nh_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib6_nh_init(struct net *net, struct fib6_nh *fib6_nh, struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a679d0)
Location: net/ipv6/route.c:3388
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81a679d0-ffffffff81a6803f: fib6_nh_init (STB_GLOBAL)
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

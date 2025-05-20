# Function: <code>ip6_route_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d7570)
Location: net/ipv6/route.c:1995
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff817d7570-ffffffff817d764b: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81845ca0)
Location: net/ipv6/route.c:2066
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff81845ca0-ffffffff81845d72: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81877a00)
Location: net/ipv6/route.c:2087
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff81877a00-ffffffff81877ad2: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189cbf0)
Location: net/ipv6/route.c:2103
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff8189cbf0-ffffffff8189cca5: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191f960)
Location: net/ipv6/route.c:2800
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff8191f960-ffffffff8191fa10: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81977c30)
Location: net/ipv6/route.c:3154
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff81977c30-ffffffff81977ca5: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ad820)
Location: net/ipv6/route.c:3134
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff819ad820-ffffffff819ad895: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a1b590)
Location: net/ipv6/route.c:3691
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff81a1b590-ffffffff81a1b60b: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a52210)
Location: net/ipv6/route.c:3704
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff81a52210-ffffffff81a5228b: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b498f0)
Location: net/ipv6/route.c:3733
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff81b498f0-ffffffff81b499b5: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b58500)
Location: net/ipv6/route.c:3717
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff81b58500-ffffffff81b585c5: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b46220)
Location: net/ipv6/route.c:3731
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff81b46220-ffffffff81b462e5: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0d460)
Location: net/ipv6/route.c:3861
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff81c0d460-ffffffff81c0d525: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da83f0)
Location: net/ipv6/route.c:3837
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff81da83f0-ffffffff81da84d9: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f77a90)
Location: net/ipv6/route.c:3837
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff81f77a90-ffffffff81f77b79: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd7c10)
Location: net/ipv6/route.c:3835
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff81fd7c10-ffffffff81fd7cf9: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a5590)
Location: net/ipv6/route.c:3837
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff820a5590-ffffffff820a5679: ip6_route_add (STB_GLOBAL)
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
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d16180)
Location: net/ipv6/route.c:3704
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffff800010d16180-ffff800010d16234: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1be8c)
Location: net/ipv6/route.c:3704
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
c0e1be8c-c0e1bf04: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e436c0)
Location: net/ipv6/route.c:3704
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
c000000000e436c0-c000000000e437d4: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085b684)
Location: net/ipv6/route.c:3704
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffe00085b684-ffffffe00085b724: ip6_route_add (STB_GLOBAL)
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
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819f18a0)
Location: net/ipv6/route.c:3704
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff819f18a0-ffffffff819f191b: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ae660)
Location: net/ipv6/route.c:3704
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff819ae660-ffffffff819ae6db: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5c320)
Location: net/ipv6/route.c:3704
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff81a5c320-ffffffff81a5c39b: ip6_route_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a686a0)
Location: net/ipv6/route.c:3704
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/route.c:inet6_rtm_newroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
```
**Symbols:**

```
ffffffff81a686a0-ffffffff81a6871b: ip6_route_add (STB_GLOBAL)
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

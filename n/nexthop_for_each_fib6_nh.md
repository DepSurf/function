# Function: <code>nexthop_for_each_fib6_nh</code>

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
int nexthop_for_each_fib6_nh(struct nexthop *nh, int (*cb)(struct fib6_nh *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819d3a20)
Location: net/ipv4/nexthop.c:520
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
```
**Symbols:**

```
ffffffff819d3a20-ffffffff819d3aa6: nexthop_for_each_fib6_nh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int nexthop_for_each_fib6_nh(struct nexthop *nh, int (*cb)(struct fib6_nh *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a0a590)
Location: net/ipv4/nexthop.c:522
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
```
**Symbols:**

```
ffffffff81a0a590-ffffffff81a0a616: nexthop_for_each_fib6_nh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int nexthop_for_each_fib6_nh(struct nexthop *nh, int (*cb)(struct fib6_nh *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afb160)
Location: net/ipv4/nexthop.c:588
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_update_exception_stamp_rt
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
**Symbols:**

```
ffffffff81afb160-ffffffff81afb1ef: nexthop_for_each_fib6_nh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int nexthop_for_each_fib6_nh(struct nexthop *nh, int (*cb)(struct fib6_nh *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b08820)
Location: net/ipv4/nexthop.c:716
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_update_exception_stamp_rt
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
**Symbols:**

```
ffffffff81b08820-ffffffff81b088af: nexthop_for_each_fib6_nh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int nexthop_for_each_fib6_nh(struct nexthop *nh, int (*cb)(struct fib6_nh *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af4610)
Location: net/ipv4/nexthop.c:1225
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
**Symbols:**

```
ffffffff81af4610-ffffffff81af469f: nexthop_for_each_fib6_nh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nexthop_for_each_fib6_nh(struct nexthop *nh, int (*cb)(struct fib6_nh *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb497e)
Location: net/ipv4/nexthop.c:1225
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
**Symbols:**

```
ffffffff81d3ddfd-ffffffff81d3de12: nexthop_for_each_fib6_nh.cold (STB_LOCAL)
ffffffff81bb4950-ffffffff81bb49f3: nexthop_for_each_fib6_nh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nexthop_for_each_fib6_nh(struct nexthop *nh, int (*cb)(struct fib6_nh *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1226
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
**Symbols:**

```
ffffffff81f0a513-ffffffff81f0a528: nexthop_for_each_fib6_nh.cold (STB_LOCAL)
ffffffff81d47cd0-ffffffff81d47d8f: nexthop_for_each_fib6_nh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int nexthop_for_each_fib6_nh(struct nexthop *nh, int (*cb)(struct fib6_nh *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1226
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
**Symbols:**

```
ffffffff820b1dc8-ffffffff820b1ddd: nexthop_for_each_fib6_nh.cold (STB_LOCAL)
ffffffff81f111f0-ffffffff81f112af: nexthop_for_each_fib6_nh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int nexthop_for_each_fib6_nh(struct nexthop *nh, int (*cb)(struct fib6_nh *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1226
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
**Symbols:**

```
ffffffff82132fd5-ffffffff82132fea: nexthop_for_each_fib6_nh.cold (STB_LOCAL)
ffffffff81f70ee0-ffffffff81f70f9f: nexthop_for_each_fib6_nh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int nexthop_for_each_fib6_nh(struct nexthop *nh, int (*cb)(struct fib6_nh *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1249
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
**Symbols:**

```
ffffffff82214984-ffffffff82214999: nexthop_for_each_fib6_nh.cold (STB_LOCAL)
ffffffff82037640-ffffffff820376ff: nexthop_for_each_fib6_nh (STB_GLOBAL)
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
int nexthop_for_each_fib6_nh(struct nexthop *nh, int (*cb)(struct fib6_nh *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffff800010cc3af8)
Location: net/ipv4/nexthop.c:522
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
```
**Symbols:**

```
ffff800010cc3af8-ffff800010cc3bac: nexthop_for_each_fib6_nh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int nexthop_for_each_fib6_nh(struct nexthop *nh, int (*cb)(struct fib6_nh *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dcf89c)
Location: net/ipv4/nexthop.c:522
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
```
**Symbols:**

```
c0dcf89c-c0dcf928: nexthop_for_each_fib6_nh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int nexthop_for_each_fib6_nh(struct nexthop *nh, int (*cb)(struct fib6_nh *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c000000000ddf820)
Location: net/ipv4/nexthop.c:522
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
```
**Symbols:**

```
c000000000ddf820-c000000000ddf954: nexthop_for_each_fib6_nh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int nexthop_for_each_fib6_nh(struct nexthop *nh, int (*cb)(struct fib6_nh *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffe000818cfe)
Location: net/ipv4/nexthop.c:522
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
```
**Symbols:**

```
ffffffe000818cfe-ffffffe000818d8e: nexthop_for_each_fib6_nh (STB_GLOBAL)
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
int nexthop_for_each_fib6_nh(struct nexthop *nh, int (*cb)(struct fib6_nh *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819aa330)
Location: net/ipv4/nexthop.c:522
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
```
**Symbols:**

```
ffffffff819aa330-ffffffff819aa3b6: nexthop_for_each_fib6_nh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int nexthop_for_each_fib6_nh(struct nexthop *nh, int (*cb)(struct fib6_nh *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81963df0)
Location: net/ipv4/nexthop.c:522
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
```
**Symbols:**

```
ffffffff81963df0-ffffffff81963e76: nexthop_for_each_fib6_nh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int nexthop_for_each_fib6_nh(struct nexthop *nh, int (*cb)(struct fib6_nh *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a14bd0)
Location: net/ipv4/nexthop.c:522
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
```
**Symbols:**

```
ffffffff81a14bd0-ffffffff81a14c56: nexthop_for_each_fib6_nh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int nexthop_for_each_fib6_nh(struct nexthop *nh, int (*cb)(struct fib6_nh *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a1f5e0)
Location: net/ipv4/nexthop.c:522
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
```
**Symbols:**

```
ffffffff81a1f5e0-ffffffff81a1f666: nexthop_for_each_fib6_nh (STB_GLOBAL)
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

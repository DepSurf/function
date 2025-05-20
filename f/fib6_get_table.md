# Function: <code>fib6_get_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff817d94e0)
Location: net/ipv6/ip6_fib.c:246
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/fib6_rules.c:fib6_rule_action
```
**Symbols:**

```
ffffffff817d94e0-ffffffff817d9530: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81848ab5)
Location: net/ipv6/ip6_fib.c:246
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/fib6_rules.c:fib6_rule_action
```
**Symbols:**

```
ffffffff81847430-ffffffff81847471: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8187a905)
Location: net/ipv6/ip6_fib.c:246
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/fib6_rules.c:fib6_rule_action
```
**Symbols:**

```
ffffffff81879270-ffffffff818792b1: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff818a0035)
Location: net/ipv6/ip6_fib.c:261
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/fib6_rules.c:fib6_rule_action
```
**Symbols:**

```
ffffffff8189ec10-ffffffff8189ec5b: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81922045)
Location: net/ipv6/ip6_fib.c:264
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:lookup_nexthop
```
**Symbols:**

```
ffffffff819211e0-ffffffff8192122b: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819795e0)
Location: net/ipv6/ip6_fib.c:304
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_table
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff819795e0-ffffffff8197962b: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819affe6)
Location: net/ipv6/ip6_fib.c:303
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff819af190-ffffffff819af1db: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a1d370)
Location: net/ipv6/ip6_fib.c:271
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff81a1d370-ffffffff81a1d3ad: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a53fb0)
Location: net/ipv6/ip6_fib.c:271
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff81a53fb0-ffffffff81a53fed: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4b630)
Location: net/ipv6/ip6_fib.c:271
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81b4b630-ffffffff81b4b66d: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b5a420)
Location: net/ipv6/ip6_fib.c:271
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81b5a420-ffffffff81b5a483: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b485f0)
Location: net/ipv6/ip6_fib.c:271
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81b485f0-ffffffff81b48653: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81c0f8c0)
Location: net/ipv6/ip6_fib.c:272
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81c0f8c0-ffffffff81c0f923: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81dac249)
Location: net/ipv6/ip6_fib.c:273
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81daaa80-ffffffff81daab08: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81f7bc39)
Location: net/ipv6/ip6_fib.c:272
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81f7a310-ffffffff81f7a398: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81fdbe57)
Location: net/ipv6/ip6_fib.c:272
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81fda520-ffffffff81fda5a8: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff820a9987)
Location: net/ipv6/ip6_fib.c:272
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff820a7f70-ffffffff820a7ff8: fib6_get_table (STB_GLOBAL)
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
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffff800010d183e0)
Location: net/ipv6/ip6_fib.c:271
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffff800010d183e0-ffff800010d1844c: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c0e1dcac)
Location: net/ipv6/ip6_fib.c:271
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_nh_lookup_table
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
c0e1dcac-c0e1dd0c: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c000000000e45dd0)
Location: net/ipv6/ip6_fib.c:271
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
c000000000e45dd0-c000000000e45e3c: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffe00085d008)
Location: net/ipv6/ip6_fib.c:271
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_nh_lookup_table
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffe00085d008-ffffffe00085d066: fib6_get_table (STB_GLOBAL)
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
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819f3640)
Location: net/ipv6/ip6_fib.c:271
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff819f3640-ffffffff819f367d: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b0400)
Location: net/ipv6/ip6_fib.c:271
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff819b0400-ffffffff819b043d: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a5e0c0)
Location: net/ipv6/ip6_fib.c:271
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff81a5e0c0-ffffffff81a5e0fd: fib6_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fib6_table *fib6_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a6a8f0)
Location: net/ipv6/ip6_fib.c:271
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_new_table
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff81a6a8f0-ffffffff81a6a96a: fib6_get_table (STB_GLOBAL)
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

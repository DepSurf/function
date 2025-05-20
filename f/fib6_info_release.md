# Function: <code>fib6_info_release</code>

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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff8195f46d)
Location: include/net/ip6_fib.h:289
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff8196d40a)
Location: include/net/ip6_fib.h:289
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81978dad)
Location: include/net/ip6_fib.h:289
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff8197c2ec)
Location: include/net/ip6_fib.h:289
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff81981e62)
Location: include/net/ip6_fib.h:289
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff819940c1)
Location: include/net/ip6_fib.h:292
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff819a2f62)
Location: include/net/ip6_fib.h:292
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819aea29)
Location: include/net/ip6_fib.h:292
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff819b1fcc)
Location: include/net/ip6_fib.h:292
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff819b850b)
Location: include/net/ip6_fib.h:292
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff819ffba9)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81a0df59)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a1c9a1)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81a2047c)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81a26f6e)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81a3678c)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81a3fa22)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a53614)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81a570bf)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81a5d9d1)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81b2b892)
Location: include/net/ip6_fib.h:332
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81b3470e)
Location: include/net/ip6_fib.h:332
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:fixup_permanent_addr
  - net/ipv6/addrconf.c:fixup_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81b4ab8c)
Location: include/net/ip6_fib.h:332
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_del_rt
  - net/ipv6/route.c:ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4eee0)
Location: include/net/ip6_fib.h:332
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/ndisc.c (ffffffff81b5514e)
Location: include/net/ip6_fib.h:332
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81b3a2b2)
Location: include/net/ip6_fib.h:333
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81b431de)
Location: include/net/ip6_fib.h:333
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:fixup_permanent_addr
  - net/ipv6/addrconf.c:fixup_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81b5981c)
Location: include/net/ip6_fib.h:333
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_del_rt
  - net/ipv6/route.c:ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5db60)
Location: include/net/ip6_fib.h:333
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/ndisc.c (ffffffff81b6376e)
Location: include/net/ip6_fib.h:333
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81b27f9a)
Location: include/net/ip6_fib.h:334
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81b30efe)
Location: include/net/ip6_fib.h:334
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81b47970)
Location: include/net/ip6_fib.h:334
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4bcef)
Location: include/net/ip6_fib.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/ndisc.c (ffffffff81b51b0f)
Location: include/net/ip6_fib.h:334
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81bedee9)
Location: include/net/ip6_fib.h:336
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81bf741e)
Location: include/net/ip6_fib.h:336
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81c0ebf4)
Location: include/net/ip6_fib.h:336
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81c13035)
Location: include/net/ip6_fib.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/ndisc.c (ffffffff81c19408)
Location: include/net/ip6_fib.h:336
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81d8644a)
Location: include/net/ip6_fib.h:337
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81d90abb)
Location: include/net/ip6_fib.h:337
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81da9e28)
Location: include/net/ip6_fib.h:337
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81dae786)
Location: include/net/ip6_fib.h:337
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/ndisc.c (ffffffff81db5694)
Location: include/net/ip6_fib.h:337
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81f53f9a)
Location: include/net/ip6_fib.h:337
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81f5f1cb)
Location: include/net/ip6_fib.h:337
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81f795f8)
Location: include/net/ip6_fib.h:337
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7e295)
Location: include/net/ip6_fib.h:337
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/ndisc.c (ffffffff81f85294)
Location: include/net/ip6_fib.h:337
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81fb398a)
Location: include/net/ip6_fib.h:334
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81fbed7b)
Location: include/net/ip6_fib.h:334
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81fd9808)
Location: include/net/ip6_fib.h:334
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81fde49c)
Location: include/net/ip6_fib.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/ndisc.c (ffffffff81fe555d)
Location: include/net/ip6_fib.h:334
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff8208122f)
Location: include/net/ip6_fib.h:334
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff8208c20b)
Location: include/net/ip6_fib.h:334
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff820a72d0)
Location: include/net/ip6_fib.h:334
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff820ac01c)
Location: include/net/ip6_fib.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/ndisc.c (ffffffff820b33cf)
Location: include/net/ip6_fib.h:334
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffff800010cf73b8)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffff800010cffc04)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffff800010d1780c)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffff800010d1bc40)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffff800010d22bbc)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (c0dfda64)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (c0e08180)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c0e1d378)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (c0e210b0)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (c0e271bc)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (c000000000e1dc30)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (c000000000e29d64)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c000000000e45248)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (c000000000e4a574)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (c000000000e52408)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffe0008427c4)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffe0008490ba)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffe00085c7f6)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffe00085fc00)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffe00086437c)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff819d5e1c)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff819df0b2)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819f2ca4)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff819f674f)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff819fd061)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81992bdc)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff8199be72)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819afa64)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff819b350f)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff819b9e21)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81a4089c)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81a49b32)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a5d724)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81a611cf)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81a67ae1)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81a4c4a2)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81a55a72)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a69b34)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6d690)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81a740d0)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
</ul>

## Differences

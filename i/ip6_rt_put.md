# Function: <code>ip6_rt_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff817c3d90)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff817c7a9e)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/addrconf.c (ffffffff817c9ce4)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_notify
```
```
In net/ipv6/route.c (ffffffff817d3c7f)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff817df72e)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/mcast.c (ffffffff817e8fa1)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff817fe0a6)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81830e5b)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81834bb8)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/addrconf.c (ffffffff8183f2f5)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
```
```
In net/ipv6/route.c (ffffffff81842893)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ndisc.c (ffffffff8184ed99)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/icmp.c (ffffffff81856625)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff818577f1)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff8186da0c)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff818628cb)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81866650)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/addrconf.c (ffffffff81870f1a)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
```
```
In net/ipv6/route.c (ffffffff81874606)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81880ce9)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/icmp.c (ffffffff81888415)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff818895f1)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff818a07ec)
Location: include/net/ip6_fib.h:177
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff8188703e)
Location: include/net/ip6_fib.h:207
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/addrconf.c (ffffffff81896041)
Location: include/net/ip6_fib.h:207
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
```
```
In net/ipv6/route.c (ffffffff81899489)
Location: include/net/ip6_fib.h:207
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ndisc.c (ffffffff818a6d19)
Location: include/net/ip6_fib.h:207
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/icmp.c (ffffffff818aeaf6)
Location: include/net/ip6_fib.h:207
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff818afc91)
Location: include/net/ip6_fib.h:207
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff818c701f)
Location: include/net/ip6_fib.h:207
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff8190826a)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/addrconf.c (ffffffff8191748a)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
```
```
In net/ipv6/route.c (ffffffff8191d934)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ndisc.c (ffffffff8192976f)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/icmp.c (ffffffff819317b6)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff819329b1)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff8194a2df)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff8195f66c)
Location: include/net/ip6_fib.h:267
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (ffffffff81972860)
Location: include/net/ip6_fib.h:267
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/icmp.c (ffffffff8198a326)
Location: include/net/ip6_fib.h:267
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff8198b49a)
Location: include/net/ip6_fib.h:267
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff819a32d1)
Location: include/net/ip6_fib.h:267
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (ffffffff819942bc)
Location: include/net/ip6_fib.h:270
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (ffffffff819a839e)
Location: include/net/ip6_fib.h:270
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/icmp.c (ffffffff819c0bcc)
Location: include/net/ip6_fib.h:270
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff819c1dba)
Location: include/net/ip6_fib.h:270
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff819d9de7)
Location: include/net/ip6_fib.h:270
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (ffffffff819ffdb6)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (ffffffff81a155a7)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/icmp.c (ffffffff81a2f8c6)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81a30bbb)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff81a489b1)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (ffffffff81a36996)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (ffffffff81a4c177)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/icmp.c (ffffffff81a66416)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81a6770b)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff81a7f5aa)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (ffffffff81b2bb07)
Location: include/net/ip6_fib.h:310
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (ffffffff81b45cf5)
Location: include/net/ip6_fib.h:310
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/icmp.c (ffffffff81b5ee0c)
Location: include/net/ip6_fib.h:310
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81b600bb)
Location: include/net/ip6_fib.h:310
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff81b7a17a)
Location: include/net/ip6_fib.h:310
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (ffffffff81b3a527)
Location: include/net/ip6_fib.h:311
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (ffffffff81b546b9)
Location: include/net/ip6_fib.h:311
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/icmp.c (ffffffff81b6d591)
Location: include/net/ip6_fib.h:311
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81b6e82b)
Location: include/net/ip6_fib.h:311
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff81b890ca)
Location: include/net/ip6_fib.h:311
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (ffffffff81b28207)
Location: include/net/ip6_fib.h:312
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (ffffffff81b41e19)
Location: include/net/ip6_fib.h:312
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/icmp.c (ffffffff81b5b92c)
Location: include/net/ip6_fib.h:312
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81b5c998)
Location: include/net/ip6_fib.h:312
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff81b77eea)
Location: include/net/ip6_fib.h:312
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (ffffffff81bee161)
Location: include/net/ip6_fib.h:314
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (ffffffff81c09b6f)
Location: include/net/ip6_fib.h:314
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/icmp.c (ffffffff81c2303c)
Location: include/net/ip6_fib.h:314
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81c241e8)
Location: include/net/ip6_fib.h:314
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff81c42e39)
Location: include/net/ip6_fib.h:314
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (ffffffff81d866dc)
Location: include/net/ip6_fib.h:315
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (ffffffff81da4d60)
Location: include/net/ip6_fib.h:315
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/icmp.c (ffffffff81dbfea8)
Location: include/net/ip6_fib.h:315
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81dc1198)
Location: include/net/ip6_fib.h:315
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff81de1b87)
Location: include/net/ip6_fib.h:315
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (ffffffff81f5423c)
Location: include/net/ip6_fib.h:315
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (ffffffff81f74210)
Location: include/net/ip6_fib.h:315
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/icmp.c (ffffffff81f90608)
Location: include/net/ip6_fib.h:315
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81f918f8)
Location: include/net/ip6_fib.h:315
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff81fb4087)
Location: include/net/ip6_fib.h:315
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (ffffffff81fb3c28)
Location: include/net/ip6_fib.h:312
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (ffffffff81fd42f3)
Location: include/net/ip6_fib.h:312
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/icmp.c (ffffffff81ff0e68)
Location: include/net/ip6_fib.h:312
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81ff2218)
Location: include/net/ip6_fib.h:312
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff82014821)
Location: include/net/ip6_fib.h:312
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (ffffffff820814d8)
Location: include/net/ip6_fib.h:312
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (ffffffff820a1c05)
Location: include/net/ip6_fib.h:312
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/icmp.c (ffffffff820bea48)
Location: include/net/ip6_fib.h:312
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff820bfe48)
Location: include/net/ip6_fib.h:312
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff820e3961)
Location: include/net/ip6_fib.h:312
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (ffff800010cf75a0)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (ffff800010d11670)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/icmp.c (ffff800010d2c374)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffff800010d30b68)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffff800010d4ab24)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (c0dfdc4c)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (c0e15a90)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/icmp.c (c0e30228)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (c0e31b14)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (c0e4be9c)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (c000000000e1df3c)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (c000000000e3ab20)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/icmp.c (c000000000e5dc14)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (c000000000e5f958)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (c000000000e809e4)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (ffffffe000842970)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (ffffffe0008562d2)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/icmp.c (ffffffe00086c5e2)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffe00086dc92)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffe000883c6c)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (ffffffff819d6026)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (ffffffff819eb807)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/icmp.c (ffffffff81a05aa6)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81a06d9b)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff81a1ec3a)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (ffffffff81992de6)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (ffffffff819a85c7)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/icmp.c (ffffffff819c2866)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff819c3b5b)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff819db9fa)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (ffffffff81a40aa6)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (ffffffff81a56287)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/icmp.c (ffffffff81a70526)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81a7181b)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff81a896ba)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/ipv6/anycast.c (ffffffff81a4c6a6)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/route.c (ffffffff81a622d7)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/icmp.c (ffffffff81a7cb46)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/mcast.c (ffffffff81a7de3b)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/fib6_rules.c (ffffffff81a9631a)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
</details>
</li>
</ul>

## Differences

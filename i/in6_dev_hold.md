# Function: <code>in6_dev_hold</code>

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
In net/ipv6/anycast.c (ffffffff817c3ce5)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff817c9deb)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
```
```
In net/ipv6/route.c (ffffffff817d372c)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:addrconf_dst_alloc
```
```
In net/ipv6/mcast.c (ffffffff817e96aa)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/xfrm6_policy.c (ffffffff817fc272)
Location: include/net/addrconf.h:307
Inline: True
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
In net/ipv6/anycast.c (ffffffff81830db0)
Location: include/net/addrconf.h:320
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81838b99)
Location: include/net/addrconf.h:320
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
```
```
In net/ipv6/route.c (ffffffff81846d0c)
Location: include/net/addrconf.h:320
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_blackhole_route
```
```
In net/ipv6/mcast.c (ffffffff8185b833)
Location: include/net/addrconf.h:320
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8186bb77)
Location: include/net/addrconf.h:320
Inline: True
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
In net/ipv6/anycast.c (ffffffff81862820)
Location: include/net/addrconf.h:322
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff8186d9c2)
Location: include/net/addrconf.h:322
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
```
```
In net/ipv6/route.c (ffffffff81878af8)
Location: include/net/addrconf.h:322
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_blackhole_route
```
```
In net/ipv6/mcast.c (ffffffff8188d733)
Location: include/net/addrconf.h:322
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8189e9d7)
Location: include/net/addrconf.h:322
Inline: True
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
In net/ipv6/anycast.c (ffffffff81886fbd)
Location: include/net/addrconf.h:354
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81892808)
Location: include/net/addrconf.h:354
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
```
```
In net/ipv6/route.c (ffffffff8189ddca)
Location: include/net/addrconf.h:354
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/mcast.c (ffffffff818b3de5)
Location: include/net/addrconf.h:354
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff818c4f57)
Location: include/net/addrconf.h:354
Inline: True
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
In net/ipv6/anycast.c (ffffffff819081dd)
Location: include/net/addrconf.h:353
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81913a51)
Location: include/net/addrconf.h:353
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
```
```
In net/ipv6/route.c (ffffffff81920407)
Location: include/net/addrconf.h:353
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/mcast.c (ffffffff81936b55)
Location: include/net/addrconf.h:353
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81948000)
Location: include/net/addrconf.h:353
Inline: True
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
In net/ipv6/addrconf.c (ffffffff8196b021)
Location: include/net/addrconf.h:403
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
```
```
In net/ipv6/route.c (ffffffff81977370)
Location: include/net/addrconf.h:403
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/mcast.c (ffffffff8198f928)
Location: include/net/addrconf.h:403
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a1297)
Location: include/net/addrconf.h:403
Inline: True
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
In net/ipv6/addrconf.c (ffffffff819a0a90)
Location: include/net/addrconf.h:411
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
```
```
In net/ipv6/route.c (ffffffff819acfa7)
Location: include/net/addrconf.h:411
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/mcast.c (ffffffff819c61dc)
Location: include/net/addrconf.h:411
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d7d78)
Location: include/net/addrconf.h:411
Inline: True
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
In net/ipv6/addrconf.c (ffffffff81a0cc7d)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
```
```
In net/ipv6/mcast.c (ffffffff81a3503d)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a46da9)
Location: include/net/addrconf.h:392
Inline: True
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
In net/ipv6/addrconf.c (ffffffff81a4395d)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
```
```
In net/ipv6/mcast.c (ffffffff81a6bb8a)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a7d959)
Location: include/net/addrconf.h:392
Inline: True
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
In net/ipv6/addrconf.c (ffffffff81b3e8c2)
Location: include/net/addrconf.h:394
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/mcast.c (ffffffff81b62f99)
Location: include/net/addrconf.h:394
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_add_delrec
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b783f6)
Location: include/net/addrconf.h:394
Inline: True
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
In net/ipv6/addrconf.c (ffffffff81b4d452)
Location: include/net/addrconf.h:397
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/mcast.c (ffffffff81b71739)
Location: include/net/addrconf.h:397
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_add_delrec
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b8735b)
Location: include/net/addrconf.h:397
Inline: True
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
In net/ipv6/addrconf.c (ffffffff81b3b27d)
Location: include/net/addrconf.h:396
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/mcast.c (ffffffff81b5f4a3)
Location: include/net/addrconf.h:396
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b7602c)
Location: include/net/addrconf.h:396
Inline: True
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
In net/ipv6/addrconf.c (ffffffff81c01a8a)
Location: include/net/addrconf.h:396
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/mcast.c (ffffffff81c26c63)
Location: include/net/addrconf.h:396
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81c40a9c)
Location: include/net/addrconf.h:396
Inline: True
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
In net/ipv6/addrconf.c (ffffffff81d9b7a5)
Location: include/net/addrconf.h:398
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/mcast.c (ffffffff81dc46dc)
Location: include/net/addrconf.h:398
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81ddf1bd)
Location: include/net/addrconf.h:398
Inline: True
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
In net/ipv6/addrconf.c (ffffffff81f6a3e5)
Location: include/net/addrconf.h:398
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/mcast.c (ffffffff81f9532a)
Location: include/net/addrconf.h:398
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81fb13fd)
Location: include/net/addrconf.h:398
Inline: True
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
In net/ipv6/addrconf.c (ffffffff81fca41b)
Location: include/net/addrconf.h:398
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/mcast.c (ffffffff81ff5cd1)
Location: include/net/addrconf.h:398
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff82011aad)
Location: include/net/addrconf.h:398
Inline: True
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
In net/ipv6/addrconf.c (ffffffff82097bbb)
Location: include/net/addrconf.h:406
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/mcast.c (ffffffff820c38e1)
Location: include/net/addrconf.h:406
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e0a46)
Location: include/net/addrconf.h:406
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_ifdown
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
In net/ipv6/addrconf.c (ffff800010d05898)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
```
```
In net/ipv6/mcast.c (ffff800010d33858)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d48b34)
Location: include/net/addrconf.h:392
Inline: True
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
In net/ipv6/addrconf.c (c0e0c8bc)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
```
```
In net/ipv6/mcast.c (c0e361c8)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (c0e4a164)
Location: include/net/addrconf.h:392
Inline: True
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
In net/ipv6/addrconf.c (c000000000e2f858)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
```
```
In net/ipv6/mcast.c (c000000000e65b44)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7dfc4)
Location: include/net/addrconf.h:392
Inline: True
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
In net/ipv6/addrconf.c (ffffffe00084fc66)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/mcast.c (ffffffe000871842)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffe000882216)
Location: include/net/addrconf.h:392
Inline: True
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
In net/ipv6/addrconf.c (ffffffff819e2fed)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
```
```
In net/ipv6/mcast.c (ffffffff81a0b21a)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a1cfe9)
Location: include/net/addrconf.h:392
Inline: True
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
In net/ipv6/addrconf.c (ffffffff8199fdad)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
```
```
In net/ipv6/mcast.c (ffffffff819c7fda)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d9da9)
Location: include/net/addrconf.h:392
Inline: True
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
In net/ipv6/addrconf.c (ffffffff81a4da6d)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
```
```
In net/ipv6/mcast.c (ffffffff81a75c9a)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a87a69)
Location: include/net/addrconf.h:392
Inline: True
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
In net/ipv6/addrconf.c (ffffffff81a599cd)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
```
```
In net/ipv6/mcast.c (ffffffff81a823ca)
Location: include/net/addrconf.h:392
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a94653)
Location: include/net/addrconf.h:392
Inline: True
```
</details>
</li>
</ul>

## Differences

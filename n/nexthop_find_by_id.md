# Function: <code>nexthop_find_by_id</code>

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
struct nexthop *nexthop_find_by_id(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819d4b67)
Location: net/ipv4/nexthop.c:136
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff819d3570-ffffffff819d35a8: nexthop_find_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_find_by_id(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a0b6ce)
Location: net/ipv4/nexthop.c:136
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81a0a0e0-ffffffff81a0a118: nexthop_find_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_find_by_id(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afc0fc)
Location: net/ipv4/nexthop.c:155
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_add
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_check_attr_group
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81afa8b0-ffffffff81afa8e8: nexthop_find_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_find_by_id(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b081e9)
Location: net/ipv4/nexthop.c:283
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_set_hw_flags
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_check_attr_group
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81b08070-ffffffff81b080a8: nexthop_find_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_find_by_id(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af3e69)
Location: net/ipv4/nexthop.c:573
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nexthop_bucket_set_hw_flags
  - net/ipv4/nexthop.c:nexthop_set_hw_flags
  - net/ipv4/nexthop.c:nexthop_find_group_resilient
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81af38f0-ffffffff81af3928: nexthop_find_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_find_by_id(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb4534)
Location: net/ipv4/nexthop.c:573
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nexthop_bucket_set_hw_flags
  - net/ipv4/nexthop.c:nexthop_set_hw_flags
  - net/ipv4/nexthop.c:nexthop_find_group_resilient
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81bb3e10-ffffffff81bb3e48: nexthop_find_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_find_by_id(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d47fd1)
Location: net/ipv4/nexthop.c:574
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nexthop_bucket_set_hw_flags
  - net/ipv4/nexthop.c:nexthop_set_hw_flags
  - net/ipv4/nexthop.c:nexthop_find_group_resilient
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81d476c0-ffffffff81d47706: nexthop_find_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_find_by_id(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f11521)
Location: net/ipv4/nexthop.c:574
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nexthop_bucket_set_hw_flags
  - net/ipv4/nexthop.c:nexthop_set_hw_flags
  - net/ipv4/nexthop.c:nexthop_find_group_resilient
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81f10b60-ffffffff81f10ba6: nexthop_find_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_find_by_id(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f71211)
Location: net/ipv4/nexthop.c:574
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nexthop_bucket_set_hw_flags
  - net/ipv4/nexthop.c:nexthop_set_hw_flags
  - net/ipv4/nexthop.c:nexthop_find_group_resilient
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81f70850-ffffffff81f70896: nexthop_find_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_find_by_id(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff82037971)
Location: net/ipv4/nexthop.c:574
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nexthop_bucket_set_hw_flags
  - net/ipv4/nexthop.c:nexthop_set_hw_flags
  - net/ipv4/nexthop.c:nexthop_find_group_resilient
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff82036fb0-ffffffff82036ff6: nexthop_find_by_id (STB_GLOBAL)
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
struct nexthop *nexthop_find_by_id(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffff800010cc4cb0)
Location: net/ipv4/nexthop.c:136
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffff800010cc3510-ffff800010cc3564: nexthop_find_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_find_by_id(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dd0728)
Location: net/ipv4/nexthop.c:136
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:nexthop_create_group
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
c0dced04-c0dced4c: nexthop_find_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_find_by_id(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c000000000de0f3c)
Location: net/ipv4/nexthop.c:136
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
c000000000ddf130-c000000000ddf178: nexthop_find_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_find_by_id(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffe000819fa8)
Location: net/ipv4/nexthop.c:136
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffe000818844-ffffffe000818886: nexthop_find_by_id (STB_GLOBAL)
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
struct nexthop *nexthop_find_by_id(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819ab46e)
Location: net/ipv4/nexthop.c:136
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff819a9e80-ffffffff819a9eb8: nexthop_find_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_find_by_id(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81964f2e)
Location: net/ipv4/nexthop.c:136
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81963940-ffffffff81963978: nexthop_find_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_find_by_id(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a15d0e)
Location: net/ipv4/nexthop.c:136
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81a14720-ffffffff81a14758: nexthop_find_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_find_by_id(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a2074e)
Location: net/ipv4/nexthop.c:136
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81a1f130-ffffffff81a1f168: nexthop_find_by_id (STB_GLOBAL)
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

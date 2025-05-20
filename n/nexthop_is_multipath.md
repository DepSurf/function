# Function: <code>nexthop_is_multipath</code>

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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8192a611)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819768f3)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff819c48cf)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff819caeb4)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff819cba28)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffff819d5cf1)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff819d7d9a)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff81a002ba)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81a007af)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a0978a)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff81a14335)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1daa0)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/core/filter.c (ffffffff8195c9a1)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819ad310)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff819fb46f)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff81a01b3d)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff81a02578)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffff81a0c861)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff81a0e88a)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff81a36e9d)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81a3737f)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a4047a)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff81a4af25)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81a546d0)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b45577)
Location: include/net/nexthop.h:165
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:fib6_select_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b53f1a)
Location: include/net/nexthop.h:199
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:fib6_select_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b414ef)
Location: include/net/nexthop.h:275
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:fib6_select_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c09193)
Location: include/net/nexthop.h:275
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:fib6_select_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da3cbd)
Location: include/net/nexthop.h:275
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:fib6_select_path
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f730fd)
Location: include/net/nexthop.h:275
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:fib6_select_path
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd31f3)
Location: include/net/nexthop.h:275
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:fib6_select_path
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a0b03)
Location: include/net/nexthop.h:275
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:fib6_select_path
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
In net/core/filter.c (ffff800010bfe758)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffff800010c5d35c)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffff800010cb3338)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9fe8)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffff800010cbaeec)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffff800010cc5e1c)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffff800010cc8520)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffff800010cf7c1c)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffff800010cf9f10)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffff800010d016f0)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffff800010d0df2c)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffff800010d1896c)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/core/filter.c (c0d18ee4)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c0d6cb0c)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (c0dbf9bc)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
```
```
In net/ipv4/fib_semantics.c (c0dc59e0)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (c0dc6804)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (c0dd16f4)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (c0dd39e0)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (c0dfe17c)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (c0dfe864)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (c0e09234)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (c0e1482c)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (c0e1eb34)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/core/filter.c (c000000000ce6490)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c000000000d5fb54)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (c000000000dca65c)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (c000000000dd3260)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (c000000000dd45b0)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (c000000000de2768)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (c000000000de58f0)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (c000000000e1e624)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (c000000000e1ed9c)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (c000000000e2b708)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (c000000000e39eec)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (c000000000e46a64)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/core/filter.c (ffffffe0007807b4)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffe0007c6034)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b5b4)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffe000810b7e)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffe00081171c)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffe00081a934)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffe00081c854)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffe000842e8c)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffe0008433ea)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffe00084b45a)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffe000855b40)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffe00085d94c)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/core/filter.c (ffffffff818fc971)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff8194d180)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff8199b20f)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff819a18dd)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff819a2318)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffff819ac601)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff819ae62a)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff819d652d)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff819d6a0f)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff819dfb0a)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff819ea5b5)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff819f3d60)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/core/filter.c (ffffffff818b67a1)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81906c70)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81954ccf)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff8195b39d)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff8195bdd8)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffff819660c1)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff8196ac5a)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff819932ed)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff819937cf)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff8199c8ca)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff819a7375)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff819b0b20)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/core/filter.c (ffffffff8194d9a1)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819b7950)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81a05aaf)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0c17d)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff81a0cbb8)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffff81a16ea1)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff81a18eca)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff81a40fad)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81a4148f)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a4a58a)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff81a55035)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5e7e0)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/core/filter.c (ffffffff8196f37c)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819c11b3)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81a1007f)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff81a1696d)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff81a17388)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffff81a218d1)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff81a2394a)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff81a4cbb8)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d09c)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a564ca)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff81a61025)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6ac60)
Location: include/net/nexthop.h:122
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
</details>
</li>
</ul>

## Differences

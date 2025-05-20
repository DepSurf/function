# Function: <code>nexthop_num_path</code>

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
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff8197689e)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff819c487e)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff819caeb4)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
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
In net/ipv4/fib_trie.c (ffffffff819cd2b2)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffff819d5cf1)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv6/route.c (ffffffff81a14392)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
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
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819ad2bb)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff819fb41e)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff81a01b3d)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
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
In net/ipv4/fib_trie.c (ffffffff81a03e00)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffff81a0c861)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv6/route.c (ffffffff81a4af82)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
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
In net/core/filter.c (ffffffff81a2e169)
Location: include/net/nexthop.h:178
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a9706a)
Location: include/net/nexthop.h:178
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81aea1a0)
Location: include/net/nexthop.h:178
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81af09a8)
Location: include/net/nexthop.h:178
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_multipath
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff81af3d9f)
Location: include/net/nexthop.h:178
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffff81afd2c6)
Location: include/net/nexthop.h:178
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:replace_nexthop
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
In net/core/filter.c (ffffffff81a300e9)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81aa1167)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81af7000)
Location: include/net/nexthop.h:212
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81afd998)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_multipath
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (0)
Location: include/net/nexthop.h:212
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81b0b2a6)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:replace_nexthop
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
In net/core/filter.c (ffffffff81a17225)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a8c1a2)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae277a)
Location: include/net/nexthop.h:288
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae91c8)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (0)
Location: include/net/nexthop.h:288
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81af8eba)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:replace_nexthop
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
In net/core/filter.c (ffffffff81ac94c0)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81b47146)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba1f9d)
Location: include/net/nexthop.h:288
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba9224)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff81bac558)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffff81bb9929)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:replace_nexthop
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
In net/core/filter.c (ffffffff81c46419)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81cd4216)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81d34677)
Location: include/net/nexthop.h:288
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3bccd)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff81d3f3d8)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffff81d4d916)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:replace_nexthop
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int nexthop_num_path(const struct nexthop *nh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81dfa8f6)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81e94476)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81efcb67)
Location: include/net/nexthop.h:288
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81f046bd)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/fib_semantics.c:fib_find_info
```
```
In net/ipv4/fib_trie.c (ffffffff81f07fc3)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffff81f17236)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81eff9d0-ffffffff81effa2f: nexthop_num_path (STB_LOCAL)
ffffffff820b09c0-ffffffff820b09e9: nexthop_num_path.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int nexthop_num_path(const struct nexthop *nh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81e6e5b9)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81ef2c46)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5c5a7)
Location: include/net/nexthop.h:288
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81f6407d)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/fib_semantics.c:fib_find_info
```
```
In net/ipv4/fib_trie.c (ffffffff81f67aad)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffff81f76f16)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81f5f450-ffffffff81f5f4af: nexthop_num_path (STB_LOCAL)
ffffffff82131c47-ffffffff82131c70: nexthop_num_path.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int nexthop_num_path(const struct nexthop *nh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81f2debe)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81fb6bd6)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff82022b27)
Location: include/net/nexthop.h:288
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8202a64d)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/fib_semantics.c:fib_find_info
```
```
In net/ipv4/fib_trie.c (ffffffff8202e08f)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffff8203d6e6)
Location: include/net/nexthop.h:288
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff82025a20-ffffffff82025a7f: nexthop_num_path (STB_LOCAL)
ffffffff82213605-ffffffff8221362e: nexthop_num_path.cold (STB_LOCAL)
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
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffff800010c5d2ec)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffff800010cb32d0)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9fe8)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
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
In net/ipv4/fib_trie.c (ffff800010cbc960)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffff800010cc5e1c)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv6/route.c (ffff800010d0df90)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
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
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c0d6cab8)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (c0dbea78)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (c0dc59e0)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
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
In net/ipv4/fib_trie.c (c0dc81dc)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (c0dd16f4)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv6/route.c (c0e14894)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
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
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c000000000d5faac)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (c000000000dca5cc)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (c000000000dd3260)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
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
In net/ipv4/fib_trie.c (c000000000dd659c)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (c000000000de2768)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv6/route.c (c000000000e39f8c)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
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
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffe0007c5fde)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b572)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffe000810b7e)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
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
In net/ipv4/fib_trie.c (ffffffe000812d4a)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffe00081a934)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv6/route.c (ffffffe000855b88)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
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
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff8194d12b)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff8199b1be)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff819a18dd)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
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
In net/ipv4/fib_trie.c (ffffffff819a3ba0)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffff819ac601)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv6/route.c (ffffffff819ea612)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
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
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81906c1b)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81954c7e)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff8195b39d)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
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
In net/ipv4/fib_trie.c (ffffffff8195d660)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffff819660c1)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv6/route.c (ffffffff819a73d2)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
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
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819b78fb)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81a05a5e)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0c17d)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
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
In net/ipv4/fib_trie.c (ffffffff81a0e440)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffff81a16ea1)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv6/route.c (ffffffff81a55092)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
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
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819c116c)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81a1002e)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff81a1696d)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
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
In net/ipv4/fib_trie.c (ffffffff81a18c6e)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/nexthop.c (ffffffff81a218d1)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv6/route.c (ffffffff81a61082)
Location: include/net/nexthop.h:135
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

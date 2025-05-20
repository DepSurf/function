# Function: <code>nexthop_mpath_select</code>

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
In net/ipv4/route.c (ffffffff819768fd)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff819c48d9)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff819cb016)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff819cba6b)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff819d7db5)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff81a00311)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81a0080d)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a09809)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff81a1436f)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1db78)
Location: include/net/nexthop.h:150
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
In net/ipv4/route.c (ffffffff819ad31a)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff819fb479)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff81a01c1d)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81a025bb)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81a0e8a5)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff81a36ef4)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81a373dd)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a404f9)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff81a4af5f)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81a547a8)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv4/route.c (ffffffff81a97094)
Location: include/net/nexthop.h:194
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeac6d)
Location: include/net/nexthop.h:194
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81aedd23)
Location: include/net/nexthop.h:194
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81af1f14)
Location: include/net/nexthop.h:194
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81aff818)
Location: include/net/nexthop.h:194
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff81b2c120)
Location: include/net/nexthop.h:194
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c8b9)
Location: include/net/nexthop.h:194
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81b3434f)
Location: include/net/nexthop.h:194
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81b4549a)
Location: include/net/nexthop.h:194
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4babe)
Location: include/net/nexthop.h:194
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv4/route.c (ffffffff81aa1190)
Location: include/net/nexthop.h:228
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81af7b2e)
Location: include/net/nexthop.h:228
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81afac83)
Location: include/net/nexthop.h:228
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81aff0a4)
Location: include/net/nexthop.h:228
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff81b0d898)
Location: include/net/nexthop.h:228
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff81b3ab45)
Location: include/net/nexthop.h:228
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81b3b2ad)
Location: include/net/nexthop.h:228
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81b44b9f)
Location: include/net/nexthop.h:228
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81b53e3d)
Location: include/net/nexthop.h:228
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5a6fe)
Location: include/net/nexthop.h:228
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv4/route.c (ffffffff81a8c1cc)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae323e)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae6238)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
```
```
In net/ipv4/fib_trie.c (ffffffff81aea5da)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff81afb688)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff81b28825)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81b290a0)
Location: include/net/nexthop.h:304
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b3286f)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81b41413)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81b488ce)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv4/route.c (ffffffff81b471b5)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba2b39)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba5d1e)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
```
```
In net/ipv4/fib_trie.c (ffffffff81baa767)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81bbcb21)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff81bee7f1)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81bf0203)
Location: include/net/nexthop.h:304
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81bf8bcc)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81c09109)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81c0fc6e)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv4/route.c (ffffffff81cd4285)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81d35286)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81d389dd)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
```
```
In net/ipv4/fib_trie.c (ffffffff81d3d3ff)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81d5112e)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff81d86d71)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81d888a6)
Location: include/net/nexthop.h:304
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81d920fe)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81da3bbb)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81daaebf)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv4/route.c (ffffffff81e944e5)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81efd7d6)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81f00f7d)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
```
```
In net/ipv4/fib_trie.c (ffffffff81f060af)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81f1af6e)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff81f54931)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81f56686)
Location: include/net/nexthop.h:304
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81f6080e)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81f72ffb)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7a7af)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv4/route.c (ffffffff81ef2cb5)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5d246)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81f609e9)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
```
```
In net/ipv4/fib_trie.c (ffffffff81f65b0f)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81f7abde)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff81fb4341)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81fb607c)
Location: include/net/nexthop.h:304
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fc063e)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81fd30f1)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81fda9bf)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv4/route.c (ffffffff81fb6c45)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff820237d3)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff82026fb9)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
```
```
In net/ipv4/fib_trie.c (ffffffff8202c0e6)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff820412de)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff82081bf1)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff82083745)
Location: include/net/nexthop.h:304
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8208daee)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff820a0a01)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff820a840f)
Location: include/net/nexthop.h:304
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv4/route.c (ffff800010c5d368)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffff800010cb3344)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffff800010cba228)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffff800010cbaf30)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffff800010cc8540)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffff800010cf7c7c)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffff800010cf9f60)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffff800010d01764)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffff800010d0df6c)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffff800010d18a48)
Location: include/net/nexthop.h:150
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
In net/ipv4/route.c (c0d6cb1c)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (c0dbf9ec)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
```
```
In net/ipv4/fib_semantics.c (c0dc5b20)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (c0dc685c)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (c0dd3a08)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (c0dfe1f8)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (c0dfe8e0)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (c0e092ac)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (c0e14868)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (c0e1ec18)
Location: include/net/nexthop.h:150
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
In net/ipv4/route.c (c000000000d5fb64)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (c000000000dca66c)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (c000000000dd3594)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (c000000000dd4610)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (c000000000de5920)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (c000000000e1e6a0)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (c000000000e1ee50)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (c000000000e2b7a0)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (c000000000e39f60)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (c000000000e46ba0)
Location: include/net/nexthop.h:150
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
In net/ipv4/route.c (ffffffe0007c603c)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b5bc)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffe000810c18)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffe000811748)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffe00081c87c)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffe000842ee0)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffe00084344c)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffe00084b55a)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffe000855b6e)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffe00085da1c)
Location: include/net/nexthop.h:150
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
In net/ipv4/route.c (ffffffff8194d18a)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff8199b219)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff819a19bd)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff819a235b)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff819ae645)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff819d6584)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff819d6a6d)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff819dfb89)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff819ea5ef)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff819f3e38)
Location: include/net/nexthop.h:150
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
In net/ipv4/route.c (ffffffff81906c7a)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81954cd9)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff8195b47d)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff8195be1b)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff8196ac75)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff81993344)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff8199382d)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff8199c949)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff819a73af)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff819b0bf8)
Location: include/net/nexthop.h:150
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
In net/ipv4/route.c (ffffffff819b795a)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81a05ab9)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0c25d)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81a0cbfb)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81a18ee5)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff81a41004)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81a414ed)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a4a609)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff81a5506f)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5e8b8)
Location: include/net/nexthop.h:150
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
In net/ipv4/route.c (ffffffff819c11bd)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81a10089)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff81a16a4d)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81a173cb)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81a23965)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv6/anycast.c (ffffffff81a4cc0f)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d13e)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a56549)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff81a6105f)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6ad38)
Location: include/net/nexthop.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
</details>
</li>
</ul>

## Differences

# Function: <code>fib_info_nhc</code>

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
In net/ipv4/route.c (0)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff819c4c50)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff819caf90)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff819cb8e8)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff819d7d29)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
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
In net/ipv4/route.c (0)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff819fb7f0)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff81a01b99)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81a02438)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81a0e819)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
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
In net/ipv4/route.c (0)
Location: include/net/nexthop.h:347
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeac06)
Location: include/net/nexthop.h:347
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81aedb75)
Location: include/net/nexthop.h:347
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
In net/ipv4/fib_trie.c (ffffffff81af1da0)
Location: include/net/nexthop.h:347
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81aff799)
Location: include/net/nexthop.h:347
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
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
In net/ipv4/route.c (0)
Location: include/net/nexthop.h:381
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81af7ab8)
Location: include/net/nexthop.h:381
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81afaad5)
Location: include/net/nexthop.h:381
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
In net/ipv4/fib_trie.c (ffffffff81afef30)
Location: include/net/nexthop.h:381
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81b0d819)
Location: include/net/nexthop.h:381
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
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
In net/ipv4/route.c (0)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae31c8)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae6088)
Location: include/net/nexthop.h:457
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
In net/ipv4/fib_trie.c (ffffffff81aea465)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81afb609)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
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
In net/ipv4/route.c (ffffffff81b4717d)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba2a9c)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba5b50)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
```
```
In net/ipv4/fib_trie.c (ffffffff81baa5bb)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81bbca59)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
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
In net/ipv4/route.c (ffffffff81cd424c)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81d351d8)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81d38870)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
```
```
In net/ipv4/fib_trie.c (ffffffff81d3d237)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81d51069)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
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
In net/ipv4/route.c (ffffffff81e944ac)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81efd728)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81f00e10)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
```
```
In net/ipv4/fib_trie.c (ffffffff81f05ee7)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81f1aea9)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
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
In net/ipv4/route.c (ffffffff81ef2c7c)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5d198)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81f60890)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
```
```
In net/ipv4/fib_trie.c (ffffffff81f65947)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81f7ab19)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
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
In net/ipv4/route.c (ffffffff81fb6c0c)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff82023725)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff82026e60)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
```
```
In net/ipv4/fib_trie.c (ffffffff8202bf17)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff82041219)
Location: include/net/nexthop.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
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
In net/ipv4/route.c (0)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffff800010cb36b8)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffff800010cba184)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffff800010cbadb0)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffff800010cc8484)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
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
In net/ipv4/route.c (0)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (c0dbf94c)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
```
```
In net/ipv4/fib_semantics.c (c0dc5a68)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (c0dc66a0)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (c0dd3954)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
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
In net/ipv4/route.c (0)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (c000000000dca2e0)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (c000000000dd33e8)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (c000000000dd43fc)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (c000000000de5818)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
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
In net/ipv4/route.c (ffffffe0007c5f28)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b542)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffe000810ba0)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffe0008115e2)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffe00081c7f8)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
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
In net/ipv4/route.c (0)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff8199b590)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff819a1939)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff819a21d8)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff819ae5b9)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
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
In net/ipv4/route.c (0)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81955050)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff8195b3f9)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff8195bc98)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff8196abe9)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
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
In net/ipv4/route.c (0)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81a05e30)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0c1d9)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81a0ca78)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81a18e59)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
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
In net/ipv4/route.c (0)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81a10434)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff81a169c9)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81a17248)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81a238d9)
Location: include/net/nexthop.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
</details>
</li>
</ul>

## Differences

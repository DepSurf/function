# Function: <code>nexthop_fib_nhc</code>

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
In net/ipv4/route.c (ffffffff819768f3)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff819c48cf)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff819cafe7)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff819cba28)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff819d7d9a)
Location: include/net/nexthop.h:212
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
In net/ipv4/route.c (ffffffff819ad310)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff819fb46f)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff81a01bee)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81a02578)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81a0e88a)
Location: include/net/nexthop.h:212
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
In net/ipv4/route.c (ffffffff81a97087)
Location: include/net/nexthop.h:256
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeac5a)
Location: include/net/nexthop.h:256
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81aedd10)
Location: include/net/nexthop.h:256
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
In net/ipv4/fib_trie.c (ffffffff81af1f01)
Location: include/net/nexthop.h:256
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81aff804)
Location: include/net/nexthop.h:256
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
In net/ipv4/route.c (ffffffff81aa1183)
Location: include/net/nexthop.h:290
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81af7b1b)
Location: include/net/nexthop.h:290
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81afac70)
Location: include/net/nexthop.h:290
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
In net/ipv4/fib_trie.c (ffffffff81aff091)
Location: include/net/nexthop.h:290
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff81b0d884)
Location: include/net/nexthop.h:290
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
In net/ipv4/route.c (ffffffff81a8c1bf)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae322b)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae6225)
Location: include/net/nexthop.h:366
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
In net/ipv4/fib_trie.c (ffffffff81aea5c7)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff81afb674)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
struct fib_nh_common *nexthop_fib_nhc(struct nexthop *nh, int nhsel);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81b4718e)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba2b06)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba5cf3)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_default
```
```
In net/ipv4/fib_trie.c (ffffffff81baa73f)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81bbcaf0)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff81ba4c30-ffffffff81ba4ca5: nexthop_fib_nhc (STB_LOCAL)
ffffffff81d3c864-ffffffff81d3c88e: nexthop_fib_nhc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
struct fib_nh_common *nexthop_fib_nhc(struct nexthop *nh, int nhsel);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81cd4259)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81d35255)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81d389b2)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_default
```
```
In net/ipv4/fib_trie.c (ffffffff81d3d3d6)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81d510fd)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff81d375c0-ffffffff81d3763d: nexthop_fib_nhc (STB_LOCAL)
ffffffff81f090af-ffffffff81f090d9: nexthop_fib_nhc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
struct fib_nh_common *nexthop_fib_nhc(struct nexthop *nh, int nhsel);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81e944b9)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81efd7a5)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81f00f52)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_default
```
```
In net/ipv4/fib_trie.c (ffffffff81f06086)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81f1af3d)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff81effa40-ffffffff81effabd: nexthop_fib_nhc (STB_LOCAL)
ffffffff820b09e9-ffffffff820b0a13: nexthop_fib_nhc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
struct fib_nh_common *nexthop_fib_nhc(struct nexthop *nh, int nhsel);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81ef2c89)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5d215)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81f609be)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_default
```
```
In net/ipv4/fib_trie.c (ffffffff81f65ae6)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81f7abad)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff81f5f4c0-ffffffff81f5f53d: nexthop_fib_nhc (STB_LOCAL)
ffffffff82131c70-ffffffff82131c9a: nexthop_fib_nhc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
struct fib_nh_common *nexthop_fib_nhc(struct nexthop *nh, int nhsel);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb6c19)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff820237a2)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff82026f8e)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_select_default
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_default
```
```
In net/ipv4/fib_trie.c (ffffffff8202c0bd)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff820412ad)
Location: include/net/nexthop.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff82025a90-ffffffff82025b0d: nexthop_fib_nhc (STB_LOCAL)
ffffffff8221362e-ffffffff82213658: nexthop_fib_nhc.cold (STB_LOCAL)
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
In net/ipv4/route.c (ffff800010c5d35c)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffff800010cb3338)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffff800010cba1e4)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffff800010cbaeec)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffff800010cc8520)
Location: include/net/nexthop.h:212
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
In net/ipv4/route.c (c0d6cb0c)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (c0dbf9bc)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
```
```
In net/ipv4/fib_semantics.c (c0dc5adc)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (c0dc6804)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (c0dd39e0)
Location: include/net/nexthop.h:212
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
In net/ipv4/route.c (c000000000d5fb54)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (c000000000dca65c)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (c000000000dd3520)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (c000000000dd45b0)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (c000000000de58f0)
Location: include/net/nexthop.h:212
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
In net/ipv4/route.c (ffffffe0007c5fea)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b57a)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffe000810bf0)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffe00081171c)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffe00081c854)
Location: include/net/nexthop.h:212
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
In net/ipv4/route.c (ffffffff8194d180)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff8199b20f)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff819a198e)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff819a2318)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff819ae62a)
Location: include/net/nexthop.h:212
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
In net/ipv4/route.c (ffffffff81906c70)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81954ccf)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff8195b44e)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff8195bdd8)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff8196ac5a)
Location: include/net/nexthop.h:212
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
In net/ipv4/route.c (ffffffff819b7950)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81a05aaf)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0c22e)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81a0cbb8)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81a18eca)
Location: include/net/nexthop.h:212
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
In net/ipv4/route.c (ffffffff819c11b3)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
```
In net/ipv4/fib_frontend.c (ffffffff81a1007f)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff81a16a1e)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81a17388)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/fib_rules.c (ffffffff81a2394a)
Location: include/net/nexthop.h:212
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

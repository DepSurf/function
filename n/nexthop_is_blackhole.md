# Function: <code>nexthop_is_blackhole</code>

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
In net/ipv4/fib_semantics.c (ffffffff819c9e04)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffffffff819cd2d6)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff81a14227)
Location: include/net/nexthop.h:184
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
In net/ipv4/fib_semantics.c (ffffffff81a009c4)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffffffff81a03e24)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff81a4ae17)
Location: include/net/nexthop.h:184
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
In net/ipv4/fib_semantics.c (ffffffff81aefb0f)
Location: include/net/nexthop.h:226
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffffffff81af3e22)
Location: include/net/nexthop.h:226
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff81b4539f)
Location: include/net/nexthop.h:226
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
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
In net/ipv4/fib_semantics.c (ffffffff81afca4f)
Location: include/net/nexthop.h:260
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffffffff81b00ca4)
Location: include/net/nexthop.h:260
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff81b53d42)
Location: include/net/nexthop.h:260
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
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
In net/ipv4/fib_semantics.c (ffffffff81ae824c)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffffffff81aec330)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff81b41305)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
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
In net/ipv4/fib_semantics.c (ffffffff81ba818c)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffffffff81bac629)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff81c08fdb)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
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
In net/ipv4/fib_semantics.c (ffffffff81d3aba5)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffffffff81d3f4a4)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff81da39cf)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
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
In net/ipv4/fib_semantics.c (ffffffff81f03515)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffffffff81f0808f)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff81f72e0f)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
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
In net/ipv4/fib_semantics.c (ffffffff81f62ef5)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffffffff81f67b8b)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff81fd2f05)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
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
In net/ipv4/fib_semantics.c (ffffffff820294c5)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffffffff8202e16d)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff820a0815)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
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
In net/ipv4/fib_semantics.c (ffff800010cb8fcc)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffff800010cbc9a8)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffff800010d0ddac)
Location: include/net/nexthop.h:184
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
In net/ipv4/fib_semantics.c (c0dc472c)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (c0dc8280)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (c0e14714)
Location: include/net/nexthop.h:184
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
In net/ipv4/fib_semantics.c (c000000000dd1bdc)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (c000000000dd677c)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (c000000000e39cf4)
Location: include/net/nexthop.h:184
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
In net/ipv4/fib_semantics.c (ffffffe00080fd92)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffffffe000812dfe)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffe000855a74)
Location: include/net/nexthop.h:184
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
In net/ipv4/fib_semantics.c (ffffffff819a0764)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffffffff819a3bc4)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff819ea4a7)
Location: include/net/nexthop.h:184
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
In net/ipv4/fib_semantics.c (ffffffff8195a224)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffffffff8195d684)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff819a7267)
Location: include/net/nexthop.h:184
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
In net/ipv4/fib_semantics.c (ffffffff81a0b004)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffffffff81a0e464)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff81a54f27)
Location: include/net/nexthop.h:184
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
In net/ipv4/fib_semantics.c (ffffffff81a157e4)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffffffff81a18c92)
Location: include/net/nexthop.h:184
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff81a60f17)
Location: include/net/nexthop.h:184
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

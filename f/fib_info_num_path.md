# Function: <code>fib_info_num_path</code>

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
In net/core/filter.c (ffffffff8192a481)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff8197674f)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff819c4875)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff819cad46)
Location: include/net/nexthop.h:229
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
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff819cd0bb)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff8195c811)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819ad16c)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff819fb415)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff81a01936)
Location: include/net/nexthop.h:229
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
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff81a03c14)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff81a2dfea)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a9702c)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81aea159)
Location: include/net/nexthop.h:336
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81af093b)
Location: include/net/nexthop.h:336
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
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff81af3b1c)
Location: include/net/nexthop.h:336
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff81a2ff53)
Location: include/net/nexthop.h:370
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81aa1124)
Location: include/net/nexthop.h:370
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81af6fb9)
Location: include/net/nexthop.h:370
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81afd92b)
Location: include/net/nexthop.h:370
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
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff81b00a30)
Location: include/net/nexthop.h:370
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff81a17090)
Location: include/net/nexthop.h:446
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a8c06b)
Location: include/net/nexthop.h:446
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae273c)
Location: include/net/nexthop.h:446
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae915b)
Location: include/net/nexthop.h:446
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
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff81aec0b7)
Location: include/net/nexthop.h:446
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff81ac930e)
Location: include/net/nexthop.h:446
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81b46ffb)
Location: include/net/nexthop.h:446
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba1f56)
Location: include/net/nexthop.h:446
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba91a3)
Location: include/net/nexthop.h:446
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
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff81bac336)
Location: include/net/nexthop.h:446
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff81c4615a)
Location: include/net/nexthop.h:446
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81cd40c0)
Location: include/net/nexthop.h:446
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81d34626)
Location: include/net/nexthop.h:446
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3bc2c)
Location: include/net/nexthop.h:446
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
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff81d3f20f)
Location: include/net/nexthop.h:446
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff81dfa62a)
Location: include/net/nexthop.h:446
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81e94320)
Location: include/net/nexthop.h:446
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81efcb16)
Location: include/net/nexthop.h:446
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81f0461c)
Location: include/net/nexthop.h:446
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
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff81f07dfa)
Location: include/net/nexthop.h:446
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff81e6e2dd)
Location: include/net/nexthop.h:446
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81ef2af0)
Location: include/net/nexthop.h:446
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5c556)
Location: include/net/nexthop.h:446
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81f63fdc)
Location: include/net/nexthop.h:446
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
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff81f678e5)
Location: include/net/nexthop.h:446
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff81f2dbaa)
Location: include/net/nexthop.h:446
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81fb6a80)
Location: include/net/nexthop.h:446
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff82022ad6)
Location: include/net/nexthop.h:446
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8202a5ac)
Location: include/net/nexthop.h:446
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
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff8202dec7)
Location: include/net/nexthop.h:446
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffff800010bfe5f4)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffff800010c5d1e0)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffff800010cb32c8)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9f3c)
Location: include/net/nexthop.h:229
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
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffff800010cbc820)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (c0d18d7c)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c0d6c958)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (c0dbea6c)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (c0dc57c0)
Location: include/net/nexthop.h:229
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
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (c0dc7fe8)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (c000000000ce6284)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c000000000d5f954)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (c000000000dca5c0)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (c000000000dd3168)
Location: include/net/nexthop.h:229
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
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (c000000000dd64a0)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffe000780640)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffe0007c5f22)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b53e)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffe0008109f4)
Location: include/net/nexthop.h:229
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
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffe000812c04)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff818fc7e1)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff8194cfdc)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff8199b1b5)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff819a16d6)
Location: include/net/nexthop.h:229
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
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff819a39b4)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff818b6611)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81906acc)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81954c75)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff8195b196)
Location: include/net/nexthop.h:229
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
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff8195d474)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff8194d811)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819b77ac)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81a05a55)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0bf76)
Location: include/net/nexthop.h:229
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
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff81a0e254)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff8196f1c9)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819c103a)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81a10025)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
```
```
In net/ipv4/fib_semantics.c (ffffffff81a16766)
Location: include/net/nexthop.h:229
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
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/fib_trie.c (ffffffff81a18a64)
Location: include/net/nexthop.h:229
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
</details>
</li>
</ul>

## Differences

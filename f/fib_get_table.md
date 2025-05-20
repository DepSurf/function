# Function: <code>fib_get_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81799ebe)
Location: net/ipv4/fib_frontend.c:115
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:fib_new_table
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
Direct callers:
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff8179a8e0-ffffffff8179a930: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81807fca)
Location: net/ipv4/fib_frontend.c:116
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff81808510-ffffffff81808551: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8183909a)
Location: net/ipv4/fib_frontend.c:114
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff818395f0-ffffffff81839631: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8185a5be)
Location: net/ipv4/fib_frontend.c:114
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff8185ab50-ffffffff8185ab9b: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff818da4de)
Location: net/ipv4/fib_frontend.c:119
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff818daa80-ffffffff818daacb: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81930f62)
Location: net/ipv4/fib_frontend.c:119
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff81931a10-ffffffff81931a5b: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8196085f)
Location: net/ipv4/fib_frontend.c:119
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff81961270-ffffffff819612bb: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819c5261)
Location: net/ipv4/fib_frontend.c:116
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff819c59a0-ffffffff819c59d9: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819fbe01)
Location: net/ipv4/fib_frontend.c:116
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff819fc540-ffffffff819fc586: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81aeaa09)
Location: net/ipv4/fib_frontend.c:111
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_find_matching_alias
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff81aeb310-ffffffff81aeb349: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81af78a9)
Location: net/ipv4/fib_frontend.c:111
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_find_matching_alias
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff81af8210-ffffffff81af8249: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ae2fc9)
Location: net/ipv4/fib_frontend.c:111
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff81ae3930-ffffffff81ae3969: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ba25f9)
Location: net/ipv4/fib_frontend.c:111
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff81ba3240-ffffffff81ba3279: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81d34ce6)
Location: net/ipv4/fib_frontend.c:112
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff81d35a40-ffffffff81d35a81: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81efd1f6)
Location: net/ipv4/fib_frontend.c:112
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff81efe000-ffffffff81efe041: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81f5cc36)
Location: net/ipv4/fib_frontend.c:112
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff81f5da90-ffffffff81f5dad1: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff820231b6)
Location: net/ipv4/fib_frontend.c:112
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff82024050-ffffffff82024091: fib_get_table (STB_GLOBAL)
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
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffff800010cb3e4c)
Location: net/ipv4/fib_frontend.c:116
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffff800010cb48e8-ffff800010cb494c: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c0dbf328)
Location: net/ipv4/fib_frontend.c:116
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
c0dc0318-c0dc036c: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c000000000dca8f0)
Location: net/ipv4/fib_frontend.c:116
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
c000000000dcb9e0-c000000000dcba60: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffe00080b758)
Location: net/ipv4/fib_frontend.c:116
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffe00080c534-ffffffe00080c588: fib_get_table (STB_GLOBAL)
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
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8199bba1)
Location: net/ipv4/fib_frontend.c:116
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff8199c2e0-ffffffff8199c326: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81955661)
Location: net/ipv4/fib_frontend.c:116
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff81955da0-ffffffff81955de6: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a06441)
Location: net/ipv4/fib_frontend.c:116
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff81a06b80-ffffffff81a06bc6: fib_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct fib_table *fib_get_table(struct net *net, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a109f9)
Location: net/ipv4/fib_frontend.c:116
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_unmerge
  - net/ipv4/fib_frontend.c:fib_new_table
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff81a11230-ffffffff81a11276: fib_get_table (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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

# Function: <code>nexthop_put</code>

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
In net/ipv4/fib_semantics.c (ffffffff819c7d00)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/nexthop.c (ffffffff819d5e60)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1d84a)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
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
In net/ipv4/fib_semantics.c (ffffffff819fe8b0)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/nexthop.c (ffffffff81a0c9d0)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
```
In net/ipv6/ip6_fib.c (ffffffff81a54476)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
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
In net/ipv4/fib_semantics.c (ffffffff81aed6c0)
Location: include/net/nexthop.h:127
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/nexthop.c (ffffffff81afce33)
Location: include/net/nexthop.h:127
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:nexthop_add
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4bfaa)
Location: include/net/nexthop.h:127
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
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
In net/ipv4/fib_semantics.c (ffffffff81afa590)
Location: include/net/nexthop.h:161
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/nexthop.c (ffffffff81b0ac42)
Location: include/net/nexthop.h:161
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5abea)
Location: include/net/nexthop.h:161
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
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
In net/ipv4/fib_semantics.c (ffffffff81ae5b90)
Location: include/net/nexthop.h:237
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/nexthop.c (ffffffff81af84d2)
Location: include/net/nexthop.h:237
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
```
In net/ipv6/ip6_fib.c (ffffffff81b48dba)
Location: include/net/nexthop.h:237
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
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
In net/ipv4/fib_semantics.c (ffffffff81ba5716)
Location: include/net/nexthop.h:237
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/nexthop.c (ffffffff81bb9672)
Location: include/net/nexthop.h:237
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
```
In net/ipv6/ip6_fib.c (ffffffff81c100ca)
Location: include/net/nexthop.h:237
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
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
In net/ipv4/fib_semantics.c (ffffffff81d380b6)
Location: include/net/nexthop.h:237
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/nexthop.c (ffffffff81d4d655)
Location: include/net/nexthop.h:237
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
```
In net/ipv6/ip6_fib.c (ffffffff81dab34a)
Location: include/net/nexthop.h:237
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
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
In net/ipv4/fib_semantics.c (ffffffff81f00916)
Location: include/net/nexthop.h:237
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/nexthop.c (ffffffff81f16f55)
Location: include/net/nexthop.h:237
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7ac7a)
Location: include/net/nexthop.h:237
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
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
In net/ipv4/fib_semantics.c (ffffffff81f60396)
Location: include/net/nexthop.h:237
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/nexthop.c (ffffffff81f76c35)
Location: include/net/nexthop.h:237
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdae8a)
Location: include/net/nexthop.h:237
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
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
In net/ipv4/fib_semantics.c (ffffffff82026966)
Location: include/net/nexthop.h:237
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/nexthop.c (ffffffff8203d405)
Location: include/net/nexthop.h:237
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
```
In net/ipv6/ip6_fib.c (ffffffff820a88da)
Location: include/net/nexthop.h:237
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
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
In net/ipv4/fib_semantics.c (ffff800010cb69d4)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/nexthop.c (ffff800010cc5f04)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
```
In net/ipv6/ip6_fib.c (ffff800010d186a0)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
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
In net/ipv4/fib_semantics.c (c0dc2278)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/nexthop.c (c0dd1870)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:remove_nexthop
```
```
In net/ipv6/ip6_fib.c (c0e1e334)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
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
In net/ipv4/fib_semantics.c (c000000000dce9d8)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/nexthop.c (c000000000de285c)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
```
In net/ipv6/ip6_fib.c (c000000000e465b8)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
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
In net/ipv4/fib_semantics.c (ffffffe00080e154)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/nexthop.c (ffffffe00081a99c)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
```
In net/ipv6/ip6_fib.c (ffffffe00085d47a)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
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
In net/ipv4/fib_semantics.c (ffffffff8199e650)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/nexthop.c (ffffffff819ac770)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
```
In net/ipv6/ip6_fib.c (ffffffff819f3b06)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
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
In net/ipv4/fib_semantics.c (ffffffff81958110)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/nexthop.c (ffffffff81966230)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
```
In net/ipv6/ip6_fib.c (ffffffff819b08c6)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
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
In net/ipv4/fib_semantics.c (ffffffff81a08ef0)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/nexthop.c (ffffffff81a17010)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5e586)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
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
In net/ipv4/fib_semantics.c (ffffffff81a136a0)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/nexthop.c (ffffffff81a21a40)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6a886)
Location: include/net/nexthop.h:110
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
```
</details>
</li>
</ul>

## Differences

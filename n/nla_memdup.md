# Function: <code>nla_memdup</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff817d9bc8)
Location: include/net/netlink.h:1198
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/act_api.c (ffffffff817e470b)
Location: include/net/netlink.h:1198
Inline: True
Inline callers:
  - net/sched/act_api.c:nla_memdup_cookie
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff817f91fb)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/act_api.c (ffffffff818043bd)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81876b0b)
Location: include/net/netlink.h:1265
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/act_api.c (ffffffff818830d2)
Location: include/net/netlink.h:1265
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff818c82d0)
Location: include/net/netlink.h:1265
Inline: True
```
```
In net/sched/act_api.c (ffffffff818d6bde)
Location: include/net/netlink.h:1265
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/ipv6/seg6_local.c (ffffffff819a856a)
Location: include/net/netlink.h:1265
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff818f1440)
Location: include/net/netlink.h:1408
Inline: True
```
```
In net/sched/act_api.c (ffffffff81902e54)
Location: include/net/netlink.h:1408
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/ipv6/seg6_local.c (ffffffff819df0ba)
Location: include/net/netlink.h:1408
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81942d63)
Location: include/net/netlink.h:1666
Inline: True
```
```
In net/sched/act_api.c (ffffffff8196404e)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/ipv6/seg6_local.c (ffffffff81a4dc2e)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
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
In net/core/lwt_bpf.c (ffffffff81977d13)
Location: include/net/netlink.h:1666
Inline: True
```
```
In net/sched/act_api.c (ffffffff8199ab18)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/ipv6/seg6_local.c (ffffffff81a847fe)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
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
In net/core/lwt_bpf.c (ffffffff81a4c94e)
Location: include/net/netlink.h:1733
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/act_api.c (ffffffff81a72b91)
Location: include/net/netlink.h:1733
Inline: True
Inline callers:
  - net/sched/act_api.c:nla_memdup_cookie
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f9ce)
Location: include/net/netlink.h:1733
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
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
In net/core/lwt_bpf.c (ffffffff81a525ce)
Location: include/net/netlink.h:1746
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/act_api.c (ffffffff81a7b751)
Location: include/net/netlink.h:1746
Inline: True
Inline callers:
  - net/sched/act_api.c:nla_memdup_cookie
```
```
In net/ipv6/seg6_local.c (ffffffff81b8ea7e)
Location: include/net/netlink.h:1746
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
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
In net/core/lwt_bpf.c (ffffffff81a37c9e)
Location: include/net/netlink.h:1746
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/act_api.c (ffffffff81a65752)
Location: include/net/netlink.h:1746
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/ipv6/seg6_local.c (ffffffff81b7d99e)
Location: include/net/netlink.h:1746
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
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
In net/core/lwt_bpf.c (ffffffff81aedaae)
Location: include/net/netlink.h:1746
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/act_api.c (ffffffff81b1e911)
Location: include/net/netlink.h:1746
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/ipv6/seg6_local.c (ffffffff81c4911e)
Location: include/net/netlink.h:1746
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
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
In net/core/lwt_bpf.c (ffffffff81c70996)
Location: include/net/netlink.h:1746
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/act_api.c (ffffffff81ca639e)
Location: include/net/netlink.h:1746
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/ipv6/seg6_local.c (ffffffff81de899b)
Location: include/net/netlink.h:1746
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
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
In net/core/lwt_bpf.c (ffffffff81e289b6)
Location: include/net/netlink.h:1795
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/act_api.c (ffffffff81e6287e)
Location: include/net/netlink.h:1795
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/ipv6/seg6_local.c (ffffffff81fbc0cb)
Location: include/net/netlink.h:1795
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
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
In net/core/lwt_bpf.c (ffffffff81e9dfd6)
Location: include/net/netlink.h:1796
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/act_api.c (ffffffff81ebe90e)
Location: include/net/netlink.h:1796
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/ipv6/seg6_local.c (ffffffff8201c9cb)
Location: include/net/netlink.h:1796
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
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
In net/core/lwt_bpf.c (ffffffff81f60759)
Location: include/net/netlink.h:1894
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/act_api.c (ffffffff81f81ab4)
Location: include/net/netlink.h:1894
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/ipv6/seg6_local.c (ffffffff820eb9ae)
Location: include/net/netlink.h:1894
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
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
In net/core/lwt_bpf.c (ffff800010c1e550)
Location: include/net/netlink.h:1666
Inline: True
```
```
In net/sched/act_api.c (ffff800010c47d5c)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/ipv6/seg6_local.c (ffff800010d50838)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
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
In net/core/lwt_bpf.c (c0d365ac)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/act_api.c (c0d58db0)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/ipv6/seg6_local.c (c0e51394)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
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
In net/core/lwt_bpf.c (c000000000d10504)
Location: include/net/netlink.h:1666
Inline: True
```
```
In net/sched/act_api.c (c000000000d44e6c)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/ipv6/seg6_local.c (c000000000e884d8)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
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
In net/core/lwt_bpf.c (ffffffe000798270)
Location: include/net/netlink.h:1666
Inline: True
```
```
In net/sched/act_api.c (ffffffe0007b58ae)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/ipv6/seg6_local.c (ffffffe00088885e)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
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
In net/core/lwt_bpf.c (ffffffff81917b83)
Location: include/net/netlink.h:1666
Inline: True
```
```
In net/sched/act_api.c (ffffffff8193a988)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/ipv6/seg6_local.c (ffffffff81a23e8e)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
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
In net/core/lwt_bpf.c (ffffffff818d1933)
Location: include/net/netlink.h:1666
Inline: True
```
```
In net/sched/act_api.c (ffffffff818f4488)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/ipv6/seg6_local.c (ffffffff819e0c4e)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
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
In net/core/lwt_bpf.c (ffffffff81968d13)
Location: include/net/netlink.h:1666
Inline: True
```
```
In net/sched/act_api.c (ffffffff8198bb18)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/ipv6/seg6_local.c (ffffffff81a8e90e)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
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
In net/core/lwt_bpf.c (ffffffff8198b0f3)
Location: include/net/netlink.h:1666
Inline: True
```
```
In net/sched/act_api.c (ffffffff819ae388)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/ipv6/seg6_local.c (ffffffff81a9b67e)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
</details>
</li>
</ul>

## Differences

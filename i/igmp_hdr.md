# Function: <code>igmp_hdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff817954bc)
Location: include/linux/igmp.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ipmr.c (ffffffff817aaad6)
Location: include/linux/igmp.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff818058db)
Location: include/linux/igmp.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ipmr.c (ffffffff818185b6)
Location: include/linux/igmp.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81836d2b)
Location: include/linux/igmp.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ipmr.c (ffffffff81849e16)
Location: include/linux/igmp.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffff81858476)
Location: include/linux/igmp.h:24
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ipmr.c (ffffffff8186d7a6)
Location: include/linux/igmp.h:24
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffff818d8346)
Location: include/linux/igmp.h:24
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ipmr.c (ffffffff818ee0d6)
Location: include/linux/igmp.h:24
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffff8192de95)
Location: include/linux/igmp.h:24
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ipmr.c (ffffffff81943d5f)
Location: include/linux/igmp.h:24
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffff8195d750)
Location: include/linux/igmp.h:24
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ipmr.c (ffffffff81973eb9)
Location: include/linux/igmp.h:24
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffff819c23df)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ipmr.c (ffffffff819dd999)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffff819f8f7f)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ipmr.c (ffffffff81a14aad)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffff81ae6d43)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ipmr.c (ffffffff81b05a2d)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffff81af3c13)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ipmr.c (ffffffff81b13c4d)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffff81adf3ba)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ipmr.c (ffffffff81b01a8d)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffff81b9e89a)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ipmr.c (ffffffff81bc3861)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffff81d30c14)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ipmr.c (ffffffff81d587c5)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffff81ef8d24)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ipmr.c (ffffffff81f22c25)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffff81f58794)
Location: include/linux/igmp.h:21
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ipmr.c (ffffffff81f82765)
Location: include/linux/igmp.h:21
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffff8201ec54)
Location: include/linux/igmp.h:21
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ipmr.c (ffffffff82048de5)
Location: include/linux/igmp.h:21
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffff800010cae74c)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ipmr.c (ffff800010ccfd98)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (c0dbca58)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ipmr.c (c0dda394)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (c000000000dc6b58)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ipmr.c (c000000000dedfa8)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffe000809ad4)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ipmr.c (ffffffe000821e1e)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffff81998d1f)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ipmr.c (ffffffff819b4169)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffff819527df)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ipmr.c (ffffffff81970799)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffff81a035bf)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ipmr.c (ffffffff81a1ea09)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
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
In net/ipv4/igmp.c (ffffffff81a0db0f)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ipmr.c (ffffffff81a29e7d)
Location: include/linux/igmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv_v1
```
</details>
</li>
</ul>

## Differences

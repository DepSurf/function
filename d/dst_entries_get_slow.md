# Function: <code>dst_entries_get_slow</code>

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
In net/ipv4/route.c (ffffffff81754153)
Location: include/net/dst_ops.h:47
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/xfrm4_policy.c (ffffffff817af417)
Location: include/net/dst_ops.h:47
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
```
```
In net/ipv6/route.c (ffffffff817d3ec5)
Location: include/net/dst_ops.h:47
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:rt6_stats_seq_show
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
In net/ipv4/route.c (ffffffff817c0203)
Location: include/net/dst_ops.h:47
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8181c317)
Location: include/net/dst_ops.h:47
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
```
```
In net/ipv6/route.c (ffffffff81842e7e)
Location: include/net/dst_ops.h:47
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff817ef5b3)
Location: include/net/dst_ops.h:47
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8184dbd7)
Location: include/net/dst_ops.h:47
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
```
```
In net/ipv6/route.c (ffffffff81874bfb)
Location: include/net/dst_ops.h:47
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff8180f47b)
Location: include/net/dst_ops.h:49
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81871644)
Location: include/net/dst_ops.h:49
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
```
```
In net/ipv6/route.c (ffffffff8189856c)
Location: include/net/dst_ops.h:49
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff8188eadb)
Location: include/net/dst_ops.h:50
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffffffff8191996c)
Location: include/net/dst_ops.h:50
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff818e2774)
Location: include/net/dst_ops.h:50
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffffffff81971457)
Location: include/net/dst_ops.h:50
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff8190f614)
Location: include/net/dst_ops.h:50
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffffffff819a6d77)
Location: include/net/dst_ops.h:50
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff8197181b)
Location: include/net/dst_ops.h:50
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffffffff81a132e7)
Location: include/net/dst_ops.h:50
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff819a821b)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffffffff81a49ed7)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff81a90ffb)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffffffff81b40a37)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff81a9ae5b)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffffffff81b4f4e7)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff81a861ba)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffffffff81b3d217)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff81b409fa)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffffffff81c03ad7)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff81ccd473)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffffffff81d9db69)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff81e8d5a3)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffffffff81f6cb09)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff81eebcc3)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffffffff81fccb99)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff81fafd13)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffffffff8209a379)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffff800010c57a08)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffff800010d0d100)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (c0d676c0)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (c0e138d4)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (c000000000d59294)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (c000000000e38a70)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffe0007c1c6a)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffffffe000854a18)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff8194808b)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffffffff819e9567)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff81901b7b)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffffffff819a6327)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff819b285b)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffffffff81a53fe7)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In net/ipv4/route.c (ffffffff819bbf1b)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv6/route.c (ffffffff81a5ffd7)
Location: include/net/dst_ops.h:51
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
```
</details>
</li>
</ul>

## Differences

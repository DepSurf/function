# Function: <code>fib6_nh_get_excptn_bucket</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a14515)
Location: net/ipv6/route.c:1585
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4b105)
Location: net/ipv6/route.c:1591
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b458d5)
Location: net/ipv6/route.c:1613
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:rt6_update_exception_stamp_rt
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_find_cached_rt
  - net/ipv6/route.c:fib6_nh_flush_exceptions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b54275)
Location: net/ipv6/route.c:1596
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:rt6_update_exception_stamp_rt
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_find_cached_rt
  - net/ipv6/route.c:fib6_nh_flush_exceptions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4185d)
Location: net/ipv6/route.c:1606
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_find_cached_rt
  - net/ipv6/route.c:fib6_nh_flush_exceptions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c095bd)
Location: net/ipv6/route.c:1606
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_find_cached_rt
  - net/ipv6/route.c:fib6_nh_flush_exceptions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da471d)
Location: net/ipv6/route.c:1606
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_find_cached_rt
  - net/ipv6/route.c:fib6_nh_flush_exceptions
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f73bad)
Location: net/ipv6/route.c:1606
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_find_cached_rt
  - net/ipv6/route.c:fib6_nh_flush_exceptions
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd3c8d)
Location: net/ipv6/route.c:1605
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_find_cached_rt
  - net/ipv6/route.c:fib6_nh_flush_exceptions
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a159d)
Location: net/ipv6/route.c:1607
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_find_cached_rt
  - net/ipv6/route.c:fib6_nh_flush_exceptions
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0e12c)
Location: net/ipv6/route.c:1591
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e14a58)
Location: net/ipv6/route.c:1591
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_find_cached_rt
  - net/ipv6/route.c:fib6_nh_flush_exceptions
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3a198)
Location: net/ipv6/route.c:1591
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000855cbe)
Location: net/ipv6/route.c:1591
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ea795)
Location: net/ipv6/route.c:1591
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a7555)
Location: net/ipv6/route.c:1591
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a55215)
Location: net/ipv6/route.c:1591
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a61205)
Location: net/ipv6/route.c:1591
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
```
</details>
</li>
</ul>

## Differences

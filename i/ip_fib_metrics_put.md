# Function: <code>ip_fib_metrics_put</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8196287a)
Location: include/net/ip.h:427
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/ip6_fib.c (ffffffff819af73f)
Location: include/net/ip.h:427
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
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
In net/ipv4/fib_semantics.c (ffffffff819c7d14)
Location: include/net/ip.h:465
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1d85a)
Location: include/net/ip.h:465
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
In net/ipv4/fib_semantics.c (ffffffff819fe8c4)
Location: include/net/ip.h:466
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/ip6_fib.c (ffffffff81a54486)
Location: include/net/ip.h:466
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
In net/ipv4/fib_semantics.c (ffffffff81aed6e3)
Location: include/net/ip.h:466
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4bfc5)
Location: include/net/ip.h:466
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
In net/ipv4/fib_semantics.c (ffffffff81afa5b3)
Location: include/net/ip.h:469
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5ac05)
Location: include/net/ip.h:469
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
In net/ipv4/fib_semantics.c (ffffffff81ae5bb3)
Location: include/net/ip.h:473
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/route.c (ffffffff81b45f67)
Location: include/net/ip.h:473
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/ip6_fib.c (ffffffff81b48dd5)
Location: include/net/ip.h:473
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
In net/ipv4/fib_semantics.c (ffffffff81ba573a)
Location: include/net/ip.h:487
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/route.c (ffffffff81c0d0f3)
Location: include/net/ip.h:487
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/ip6_fib.c (ffffffff81c100e5)
Location: include/net/ip.h:487
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
In net/ipv4/fib_semantics.c (ffffffff81d380da)
Location: include/net/ip.h:493
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/route.c (ffffffff81da8137)
Location: include/net/ip.h:493
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/ip6_fib.c (ffffffff81dab365)
Location: include/net/ip.h:493
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
In net/ipv4/fib_semantics.c (ffffffff81f0093a)
Location: include/net/ip.h:493
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/route.c (ffffffff81f777ab)
Location: include/net/ip.h:493
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7ac95)
Location: include/net/ip.h:493
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
In net/ipv4/fib_semantics.c (ffffffff81f603ba)
Location: include/net/ip.h:502
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/route.c (ffffffff81fd77b2)
Location: include/net/ip.h:502
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdaea5)
Location: include/net/ip.h:502
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
In net/ipv4/fib_semantics.c (ffffffff8202698a)
Location: include/net/ip.h:512
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/route.c (ffffffff820a5132)
Location: include/net/ip.h:512
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/ip6_fib.c (ffffffff820a88f5)
Location: include/net/ip.h:512
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
In net/ipv4/fib_semantics.c (ffff800010cb69e8)
Location: include/net/ip.h:466
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/ip6_fib.c (ffff800010d186b4)
Location: include/net/ip.h:466
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
In net/ipv4/fib_semantics.c (c0dc228c)
Location: include/net/ip.h:466
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/ip6_fib.c (c0e1e348)
Location: include/net/ip.h:466
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
In net/ipv4/fib_semantics.c (c000000000dcea08)
Location: include/net/ip.h:466
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/ip6_fib.c (c000000000e465e8)
Location: include/net/ip.h:466
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
In net/ipv4/fib_semantics.c (ffffffe00080e16a)
Location: include/net/ip.h:466
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/ip6_fib.c (ffffffe00085d490)
Location: include/net/ip.h:466
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
In net/ipv4/fib_semantics.c (ffffffff8199e664)
Location: include/net/ip.h:466
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/ip6_fib.c (ffffffff819f3b16)
Location: include/net/ip.h:466
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
In net/ipv4/fib_semantics.c (ffffffff81958124)
Location: include/net/ip.h:466
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/ip6_fib.c (ffffffff819b08d6)
Location: include/net/ip.h:466
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
In net/ipv4/fib_semantics.c (ffffffff81a08f04)
Location: include/net/ip.h:466
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5e596)
Location: include/net/ip.h:466
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
In net/ipv4/fib_semantics.c (ffffffff81a136b4)
Location: include/net/ip.h:466
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6a896)
Location: include/net/ip.h:466
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
```
</details>
</li>
</ul>

## Differences

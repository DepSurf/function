# Function: <code>fib6_rules_early_flow_dissect</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819774fe)
Location: include/net/ip6_fib.h:474
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ad128)
Location: include/net/ip6_fib.h:499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a1a293)
Location: include/net/ip6_fib.h:510
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/ipv6/route.c (ffffffff81a50f03)
Location: include/net/ip6_fib.h:510
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/ipv6/route.c (ffffffff81b48583)
Location: include/net/ip6_fib.h:568
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/ipv6/route.c (ffffffff81b57163)
Location: include/net/ip6_fib.h:604
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/ipv6/route.c (ffffffff81b44d60)
Location: include/net/ip6_fib.h:600
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/netfilter.c (ffffffff81b77739)
Location: include/net/ip6_fib.h:600
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv6/route.c (ffffffff81c0be70)
Location: include/net/ip6_fib.h:603
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/netfilter.c (ffffffff81c4220a)
Location: include/net/ip6_fib.h:603
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv6/route.c (ffffffff81da6d0e)
Location: include/net/ip6_fib.h:603
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/netfilter.c (ffffffff81de0c0a)
Location: include/net/ip6_fib.h:603
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv6/route.c (ffffffff81f762de)
Location: include/net/ip6_fib.h:603
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/netfilter.c (ffffffff81fb304a)
Location: include/net/ip6_fib.h:603
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv6/route.c (ffffffff81fd6374)
Location: include/net/ip6_fib.h:597
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/netfilter.c (ffffffff8201373a)
Location: include/net/ip6_fib.h:597
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv6/route.c (ffffffff820a3d01)
Location: include/net/ip6_fib.h:597
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/netfilter.c (ffffffff820e289f)
Location: include/net/ip6_fib.h:597
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv6/route.c (ffff800010d14e90)
Location: include/net/ip6_fib.h:510
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/ipv6/route.c (c0e1aafc)
Location: include/net/ip6_fib.h:510
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/ipv6/route.c (c000000000e41d10)
Location: include/net/ip6_fib.h:510
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/ipv6/route.c (ffffffe00085a5e2)
Location: include/net/ip6_fib.h:510
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/ipv6/route.c (ffffffff819f0593)
Location: include/net/ip6_fib.h:510
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/ipv6/route.c (ffffffff819ad353)
Location: include/net/ip6_fib.h:510
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/ipv6/route.c (ffffffff81a5b013)
Location: include/net/ip6_fib.h:510
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/ipv6/route.c (ffffffff81a672f3)
Location: include/net/ip6_fib.h:510
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
</details>
</li>
</ul>

## Differences

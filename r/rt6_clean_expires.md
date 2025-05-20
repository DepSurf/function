# Function: <code>rt6_clean_expires</code>

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
In net/ipv6/addrconf.c (ffffffff817d0e72)
Location: include/net/ip6_fib.h:143
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff817d5ff5)
Location: include/net/ip6_fib.h:143
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff817db48d)
Location: include/net/ip6_fib.h:143
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
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
In net/ipv6/addrconf.c (ffffffff8183e6da)
Location: include/net/ip6_fib.h:143
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff81844599)
Location: include/net/ip6_fib.h:143
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff818494b2)
Location: include/net/ip6_fib.h:143
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
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
In net/ipv6/addrconf.c (ffffffff818702ea)
Location: include/net/ip6_fib.h:143
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff81876315)
Location: include/net/ip6_fib.h:143
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff8187b304)
Location: include/net/ip6_fib.h:143
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
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
In net/ipv6/addrconf.c (ffffffff81895007)
Location: include/net/ip6_fib.h:146
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff8189b9f5)
Location: include/net/ip6_fib.h:146
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff818a11d2)
Location: include/net/ip6_fib.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
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
In net/ipv6/addrconf.c (ffffffff819164cc)
Location: include/net/ip6_fib.h:190
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff8191e69b)
Location: include/net/ip6_fib.h:190
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81923b24)
Location: include/net/ip6_fib.h:190
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences

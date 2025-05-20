# Function: <code>dst_neigh_lookup</code>

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
In net/ipv6/ip6_fib.c (ffffffff817d97b5)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
```
In net/ipv6/ndisc.c (ffffffff817df4ae)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ip6_fib.c (ffffffff81847901)
Location: include/net/dst.h:467
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
```
In net/ipv6/ndisc.c (ffffffff8184f71a)
Location: include/net/dst.h:467
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/ip6_fib.c (ffffffff81879741)
Location: include/net/dst.h:467
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
```
In net/ipv6/ndisc.c (ffffffff8188167d)
Location: include/net/dst.h:467
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/ip6_fib.c (ffffffff8189f0d3)
Location: include/net/dst.h:430
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
```
In net/ipv6/ndisc.c (ffffffff818a7715)
Location: include/net/dst.h:430
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff8192a17f)
Location: include/net/dst.h:419
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81982435)
Location: include/net/dst.h:403
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ndisc.c (ffffffff819b8ae5)
Location: include/net/dst.h:403
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ndisc.c (ffffffff81a2759b)
Location: include/net/dst.h:395
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ndisc.c (ffffffff81a5dffb)
Location: include/net/dst.h:395
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ndisc.c (ffffffff81b56dca)
Location: include/net/dst.h:394
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ndisc.c (ffffffff81b6543a)
Location: include/net/dst.h:394
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ndisc.c (ffffffff81b5372b)
Location: include/net/dst.h:397
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ndisc.c (ffffffff81c1ac3b)
Location: include/net/dst.h:399
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ndisc.c (ffffffff81db722b)
Location: include/net/dst.h:400
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ndisc.c (ffffffff81f86efb)
Location: include/net/dst.h:393
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ndisc.c (ffffffff81fe723b)
Location: include/net/dst.h:407
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ndisc.c (ffffffff820b509a)
Location: include/net/dst.h:400
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ndisc.c (ffff800010d230b0)
Location: include/net/dst.h:395
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ndisc.c (c0e27704)
Location: include/net/dst.h:395
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ndisc.c (c000000000e52ff0)
Location: include/net/dst.h:395
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ndisc.c (ffffffe000864afe)
Location: include/net/dst.h:395
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ndisc.c (ffffffff819fd68b)
Location: include/net/dst.h:395
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv4/ip_tunnel.c (ffffffff8196782f)
Location: include/net/dst.h:395
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
```
```
In net/ipv6/ndisc.c (ffffffff819ba44b)
Location: include/net/dst.h:395
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ndisc.c (ffffffff81a6810b)
Location: include/net/dst.h:395
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
In net/ipv6/ndisc.c (ffffffff81a746fb)
Location: include/net/dst.h:395
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
</details>
</li>
</ul>

## Differences

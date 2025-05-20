# Function: <code>ipv6_addr_loopback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (0)
Location: include/net/ipv6.h:575
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81835ef2)
Location: include/net/ipv6.h:607
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81867a12)
Location: include/net/ipv6.h:607
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff8188c1b2)
Location: include/net/ipv6.h:608
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
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
In net/ipv6/ip6_input.c (ffffffff8190d4a2)
Location: include/net/ipv6.h:649
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff8190da77)
Location: include/net/ipv6.h:621
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (ffffffff81964804)
Location: include/net/ipv6.h:621
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff8193bead)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (ffffffff819991a9)
Location: include/net/ipv6.h:613
Inline: True
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
In net/ipv4/tcp_ipv4.c (ffffffff819a02d3)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (ffffffff81a050bc)
Location: include/net/ipv6.h:671
Inline: True
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
In net/ipv4/tcp_ipv4.c (ffffffff819d6e93)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (ffffffff81a3bc8c)
Location: include/net/ipv6.h:671
Inline: True
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
In net/ipv4/tcp_ipv4.c (ffffffff81ac6d6b)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (ffffffff81b31112)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In net/ipv4/tcp_ipv4.c (ffffffff81ad208b)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (ffffffff81b3fd42)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In net/ipv4/tcp_ipv4.c (ffffffff81abd1c6)
Location: include/net/ipv6.h:672
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (ffffffff81b2db69)
Location: include/net/ipv6.h:672
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In net/ipv4/tcp_ipv4.c (ffffffff81b7b2e6)
Location: include/net/ipv6.h:675
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (ffffffff81bf3deb)
Location: include/net/ipv6.h:675
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In net/ipv4/tcp_ipv4.c (ffffffff81d0aa12)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (ffffffff81d8cafd)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In net/ipv4/tcp_ipv4.c (ffffffff81ed02c2)
Location: include/net/ipv6.h:762
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (ffffffff81f5ad0d)
Location: include/net/ipv6.h:762
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In net/ipv4/tcp_ipv4.c (ffffffff81f2ef72)
Location: include/net/ipv6.h:759
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (ffffffff81fbaabd)
Location: include/net/ipv6.h:759
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In net/ipv4/tcp_ipv4.c (ffffffff81ff44c2)
Location: include/net/ipv6.h:759
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (ffffffff82087eed)
Location: include/net/ipv6.h:759
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In net/ipv4/tcp_ipv4.c (ffff800010c89e8c)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (ffff800010cfd22c)
Location: include/net/ipv6.h:671
Inline: True
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
In net/ipv4/tcp_ipv4.c (c0d98f90)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (c0e043b0)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In net/ipv4/tcp_ipv4.c (c000000000d97450)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (c000000000e24cfc)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In net/ipv4/tcp_ipv4.c (ffffffe0007eac2c)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (ffffffe0008475d4)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In net/ipv4/tcp_ipv4.c (ffffffff81976d03)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (ffffffff819db31c)
Location: include/net/ipv6.h:671
Inline: True
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
In drivers/net/vxlan.c (ffffffff8177350b)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - drivers/net/vxlan.c:neigh_reduce
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819307c3)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (ffffffff819980dc)
Location: include/net/ipv6.h:671
Inline: True
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
In net/ipv4/tcp_ipv4.c (ffffffff819e14d3)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (ffffffff81a45d9c)
Location: include/net/ipv6.h:671
Inline: True
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
In net/ipv4/tcp_ipv4.c (ffffffff819eb203)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv6/ip6_input.c (ffffffff81a51a74)
Location: include/net/ipv6.h:671
Inline: True
```
</details>
</li>
</ul>

## Differences

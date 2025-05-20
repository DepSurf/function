# Function: <code>tcp_synq_overflow</code>

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
In net/ipv4/tcp_input.c (ffffffff8176dfb6)
Location: include/net/tcp.h:500
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff817dc3da)
Location: include/net/tcp.h:493
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff8180c303)
Location: include/net/tcp.h:491
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff8182c7f4)
Location: include/net/tcp.h:497
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff818ab6fc)
Location: include/net/tcp.h:468
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff81900b89)
Location: include/net/tcp.h:474
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff8192ec3e)
Location: include/net/tcp.h:475
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff819922fb)
Location: include/net/tcp.h:476
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff819c8c9e)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db246)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a715e6)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
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
In net/ipv4/tcp_input.c (ffffffff81ab43dc)
Location: include/net/tcp.h:492
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac82d6)
Location: include/net/tcp.h:492
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6aed6)
Location: include/net/tcp.h:492
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
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
In net/ipv4/tcp_input.c (ffffffff81abec3a)
Location: include/net/tcp.h:497
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4266)
Location: include/net/tcp.h:497
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b79996)
Location: include/net/tcp.h:497
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
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
In net/ipv4/tcp_input.c (ffffffff81aaafb5)
Location: include/net/tcp.h:498
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf306)
Location: include/net/tcp.h:498
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b684b6)
Location: include/net/tcp.h:498
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
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
In net/ipv4/tcp_input.c (ffffffff81b671cd)
Location: include/net/tcp.h:491
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7ce46)
Location: include/net/tcp.h:491
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c30176)
Location: include/net/tcp.h:491
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
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
In net/ipv4/tcp_input.c (ffffffff81cf644b)
Location: include/net/tcp.h:502
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0cd76)
Location: include/net/tcp.h:502
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcd566)
Location: include/net/tcp.h:502
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
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
In net/ipv4/tcp_input.c (ffffffff81ebae5b)
Location: include/net/tcp.h:512
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed27c6)
Location: include/net/tcp.h:512
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e656)
Location: include/net/tcp.h:512
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
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
In net/ipv4/tcp_input.c (ffffffff81f192ec)
Location: include/net/tcp.h:506
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f314a6)
Location: include/net/tcp.h:506
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81fff116)
Location: include/net/tcp.h:506
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
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
In net/ipv4/tcp_input.c (ffffffff81fdd879)
Location: include/net/tcp.h:518
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7696)
Location: include/net/tcp.h:518
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cde26)
Location: include/net/tcp.h:518
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
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
In net/ipv4/tcp_input.c (ffff800010c7a7e8)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e62c)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39e84)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
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
In net/ipv4/tcp_input.c (c0d88550)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (c0d9d578)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
```
```
In net/ipv6/tcp_ipv6.c (c0e3c51c)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
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
In net/ipv4/tcp_input.c (c000000000d85410)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9cf7c)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6d13c)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
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
In net/ipv4/tcp_input.c (ffffffe0007de762)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee9a0)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000876c88)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
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
In net/ipv4/tcp_input.c (ffffffff81968b0e)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b0b6)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10c76)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
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
In net/ipv4/tcp_input.c (ffffffff819225fe)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934b76)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cda36)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
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
In net/ipv4/tcp_input.c (ffffffff819d32de)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5886)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7b6f6)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
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
In net/ipv4/tcp_input.c (ffffffff819dce84)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef546)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87f46)
Location: include/net/tcp.h:486
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
```
</details>
</li>
</ul>

## Differences

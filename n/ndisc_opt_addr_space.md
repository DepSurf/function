# Function: <code>ndisc_opt_addr_space</code>

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
In net/ipv6/route.c (ffffffff817d791c)
Location: include/net/ndisc.h:130
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff817de3a6)
Location: include/net/ndisc.h:130
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_fill_addr_option
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
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
In net/ipv6/ndisc.c (ffffffff8184dc24)
Location: include/net/ndisc.h:328
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff8187fb04)
Location: include/net/ndisc.h:330
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff818a5c12)
Location: include/net/ndisc.h:330
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81928622)
Location: include/net/ndisc.h:331
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff819809a4)
Location: include/net/ndisc.h:331
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff819b6fb4)
Location: include/net/ndisc.h:331
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81a25a46)
Location: include/net/ndisc.h:333
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81a5c4c6)
Location: include/net/ndisc.h:334
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81b56a83)
Location: include/net/ndisc.h:335
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81b650f3)
Location: include/net/ndisc.h:335
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81b533e3)
Location: include/net/ndisc.h:335
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81c1a8f3)
Location: include/net/ndisc.h:335
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81db6e52)
Location: include/net/ndisc.h:335
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81f86b02)
Location: include/net/ndisc.h:335
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81fe6e42)
Location: include/net/ndisc.h:335
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff820b4ca2)
Location: include/net/ndisc.h:335
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffff800010d21864)
Location: include/net/ndisc.h:334
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (c0e262e8)
Location: include/net/ndisc.h:334
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (c000000000e50f30)
Location: include/net/ndisc.h:334
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffe0008636ac)
Location: include/net/ndisc.h:334
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff819fbb56)
Location: include/net/ndisc.h:334
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff819b8916)
Location: include/net/ndisc.h:334
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81a665d6)
Location: include/net/ndisc.h:334
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81a72bb6)
Location: include/net/ndisc.h:334
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
```
</details>
</li>
</ul>

## Differences

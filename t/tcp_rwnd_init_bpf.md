# Function: <code>tcp_rwnd_init_bpf</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818350fc)
Location: include/net/tcp.h:2081
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183da51)
Location: include/net/tcp.h:2081
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffffffff818b4598)
Location: include/net/tcp.h:2046
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bdb17)
Location: include/net/tcp.h:2046
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffffffff81909ba2)
Location: include/net/tcp.h:2105
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81913994)
Location: include/net/tcp.h:2105
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffffffff81937e4e)
Location: include/net/tcp.h:2185
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81942144)
Location: include/net/tcp.h:2185
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffffffff819995ba)
Location: include/net/tcp.h:2217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a6747)
Location: include/net/tcp.h:2217
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffffffff819cffba)
Location: include/net/tcp.h:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dcb6e)
Location: include/net/tcp.h:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffffffff81abd009)
Location: include/net/tcp.h:2298
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81aca686)
Location: include/net/tcp.h:2298
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffffffff81ac876b)
Location: include/net/tcp.h:2322
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad65f6)
Location: include/net/tcp.h:2322
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffffffff81ab349f)
Location: include/net/tcp.h:2327
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac1665)
Location: include/net/tcp.h:2327
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffffffff81b7029f)
Location: include/net/tcp.h:2319
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7f0cf)
Location: include/net/tcp.h:2319
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffffffff81cff839)
Location: include/net/tcp.h:2379
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0ea21)
Location: include/net/tcp.h:2379
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffffffff81ec48d9)
Location: include/net/tcp.h:2427
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed4501)
Location: include/net/tcp.h:2427
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffffffff81f23242)
Location: include/net/tcp.h:2452
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f33519)
Location: include/net/tcp.h:2452
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffffffff81fe76e8)
Location: include/net/tcp.h:2648
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff9681)
Location: include/net/tcp.h:2648
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffff800010c82658)
Location: include/net/tcp.h:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f758)
Location: include/net/tcp.h:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (c0d91cd8)
Location: include/net/tcp.h:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_minisocks.c (c0d9f500)
Location: include/net/tcp.h:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (c000000000d8e1f0)
Location: include/net/tcp.h:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9ec38)
Location: include/net/tcp.h:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffffffe0007e4972)
Location: include/net/tcp.h:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efe08)
Location: include/net/tcp.h:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffffffff8196fe2a)
Location: include/net/tcp.h:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c9de)
Location: include/net/tcp.h:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffffffff819298fa)
Location: include/net/tcp.h:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8193649e)
Location: include/net/tcp.h:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffffffff819da5fa)
Location: include/net/tcp.h:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e71ae)
Location: include/net/tcp.h:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp_output.c (ffffffff819e427c)
Location: include/net/tcp.h:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0e7e)
Location: include/net/tcp.h:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
</details>
</li>
</ul>

## Differences

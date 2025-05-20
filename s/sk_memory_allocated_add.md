# Function: <code>sk_memory_allocated_add</code>

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
In net/core/sock.c (ffffffff81702a2a)
Location: include/net/sock.h:1222
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
```
```
In net/ipv4/tcp_output.c (ffffffff81778f5b)
Location: include/net/sock.h:1222
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff81767ef0)
Location: include/net/sock.h:1166
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
```
```
In net/ipv4/tcp_output.c (ffffffff817e6115)
Location: include/net/sock.h:1166
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff81794efb)
Location: include/net/sock.h:1206
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff81816835)
Location: include/net/sock.h:1206
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff817b35de)
Location: include/net/sock.h:1209
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff81836b35)
Location: include/net/sock.h:1209
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff8182b9be)
Location: include/net/sock.h:1213
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff818b61e9)
Location: include/net/sock.h:1213
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff81875536)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff8190ba29)
Location: include/net/sock.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff81895e0c)
Location: include/net/sock.h:1265
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff81939cf9)
Location: include/net/sock.h:1265
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff818e031c)
Location: include/net/sock.h:1268
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff8199dfbe)
Location: include/net/sock.h:1268
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff819124dc)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff819d4a7e)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff819e4359)
Location: include/net/sock.h:1326
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff81ac144f)
Location: include/net/sock.h:1326
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff819e3bdb)
Location: include/net/sock.h:1342
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff81accebf)
Location: include/net/sock.h:1342
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff819c9c6b)
Location: include/net/sock.h:1354
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff81ab808f)
Location: include/net/sock.h:1354
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff81a79109)
Location: include/net/sock.h:1366
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff81b7524f)
Location: include/net/sock.h:1366
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff81bed56c)
Location: include/net/sock.h:1420
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81d04a62)
Location: include/net/sock.h:1420
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff81d9daf1)
Location: include/net/sock.h:1468
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81ec9a67)
Location: include/net/sock.h:1468
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff81e0c371)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81f285b7)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff81ec8d0e)
Location: include/net/sock.h:1434
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81fed047)
Location: include/net/sock.h:1434
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffff800010bacb84)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffff800010c876ac)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (c0cc86a0)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (c0d969e8)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (c000000000c7f904)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (c000000000d941d8)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffe00073d546)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffe0007e8a44)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff818b24dc)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff819748ee)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff8186c42c)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff8192e3ae)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff819034dc)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff819df0be)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff819244bc)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff819e8d5e)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
</details>
</li>
</ul>

## Differences

# Function: <code>sk_prot_mem_limits</code>

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
In net/core/sock.c (ffffffff817028da)
Location: include/net/sock.h:1185
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_schedule
```
```
In net/ipv4/tcp.c (ffffffff8176a1b8)
Location: include/net/sock.h:1185
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff8176aa90)
Location: include/net/sock.h:1185
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
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
In net/core/sock.c (ffffffff8176807a)
Location: include/net/sock.h:1154
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_schedule
```
```
In net/ipv4/tcp.c (ffffffff817d6c4d)
Location: include/net/sock.h:1154
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff817dbd80)
Location: include/net/sock.h:1154
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
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
In net/core/sock.c (ffffffff81795067)
Location: include/net/sock.h:1322
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81806c6d)
Location: include/net/sock.h:1322
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff8180be53)
Location: include/net/sock.h:1322
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
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
In net/core/sock.c (ffffffff817b36d6)
Location: include/net/sock.h:1325
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81827281)
Location: include/net/sock.h:1325
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81827faf)
Location: include/net/sock.h:1325
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
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
In net/core/sock.c (ffffffff8182bac7)
Location: include/net/sock.h:1329
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff818a6081)
Location: include/net/sock.h:1329
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff818a74ca)
Location: include/net/sock.h:1329
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
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
In net/core/sock.c (ffffffff81875602)
Location: include/net/sock.h:1344
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff818fb129)
Location: include/net/sock.h:1344
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81900357)
Location: include/net/sock.h:1344
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
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
In net/core/sock.c (ffffffff81895ee3)
Location: include/net/sock.h:1382
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81929057)
Location: include/net/sock.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff8192a767)
Location: include/net/sock.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
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
In net/core/sock.c (ffffffff818e03f1)
Location: include/net/sock.h:1385
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff8198bf6a)
Location: include/net/sock.h:1385
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff8198d9d4)
Location: include/net/sock.h:1385
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
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
In net/core/sock.c (ffffffff819125b1)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff819c28ba)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff819c4586)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
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
In net/core/sock.c (ffffffff819e5b12)
Location: include/net/sock.h:1443
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81aade67)
Location: include/net/sock.h:1443
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81ab32c6)
Location: include/net/sock.h:1443
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_prune_queue
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
In net/core/sock.c (ffffffff819e55e2)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81ab80f7)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81abe22f)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_prune_queue
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
In net/core/sock.c (ffffffff819cb6f2)
Location: include/net/sock.h:1475
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81aa3434)
Location: include/net/sock.h:1475
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81aa930f)
Location: include/net/sock.h:1475
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
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
In net/core/sock.c (ffffffff81a7ad7c)
Location: include/net/sock.h:1485
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81b5f5ff)
Location: include/net/sock.h:1485
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81b651fb)
Location: include/net/sock.h:1485
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
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
In net/core/sock.c (ffffffff81beec8e)
Location: include/net/sock.h:1558
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp.c (ffffffff81cee06f)
Location: include/net/sock.h:1558
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81cf3b3c)
Location: include/net/sock.h:1558
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
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
In net/core/sock.c (ffffffff81d9e3c1)
Location: include/net/sock.h:1611
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/tcp.c (ffffffff81eb1311)
Location: include/net/sock.h:1611
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81eb853e)
Location: include/net/sock.h:1611
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
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
In net/core/sock.c (ffffffff81e0cc39)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/tcp.c (ffffffff81f0f9a1)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81f169ae)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
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
In net/core/sock.c (ffffffff81ec95b9)
Location: include/net/sock.h:1577
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/tcp.c (ffffffff81fd3b91)
Location: include/net/sock.h:1577
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81fdb81e)
Location: include/net/sock.h:1577
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
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
In net/core/sock.c (ffff800010bacc34)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffff800010c755e4)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffff800010c76fac)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
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
In net/core/sock.c (c0cc879c)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (c0d83d18)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (c0d85508)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
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
In net/core/sock.c (c000000000c7fb24)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (c000000000d7cc78)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (c000000000d7f228)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
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
In net/core/sock.c (ffffffe00073d61e)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffe0007d888a)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffe0007da208)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
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
In net/core/sock.c (ffffffff818b25b1)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff8196272a)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff819643f6)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
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
In net/core/sock.c (ffffffff8186c501)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff8191c21a)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff8191dee6)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
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
In net/core/sock.c (ffffffff819035b1)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff819ccefa)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff819cebc6)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
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
In net/core/sock.c (ffffffff81924591)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff819d6a8a)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff819d8756)
Location: include/net/sock.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
</details>
</li>
</ul>

## Differences

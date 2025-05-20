# Function: <code>sk_memory_allocated</code>

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
In net/core/sock.c (ffffffff817028cb)
Location: include/net/sock.h:1211
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8176a1a5)
Location: include/net/sock.h:1211
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff8176aa7d)
Location: include/net/sock.h:1211
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
In net/core/sock.c (ffffffff81769b30)
Location: include/net/sock.h:1160
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817d6c42)
Location: include/net/sock.h:1160
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff817dbd75)
Location: include/net/sock.h:1160
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
In net/core/sock.c (ffffffff81796a2f)
Location: include/net/sock.h:1200
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81806c62)
Location: include/net/sock.h:1200
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff8180be48)
Location: include/net/sock.h:1200
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
In net/core/sock.c (ffffffff817b4e2f)
Location: include/net/sock.h:1203
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81827276)
Location: include/net/sock.h:1203
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81827fa4)
Location: include/net/sock.h:1203
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
In net/core/sock.c (ffffffff8182d25f)
Location: include/net/sock.h:1207
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818a6076)
Location: include/net/sock.h:1207
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff818a74bf)
Location: include/net/sock.h:1207
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
In net/core/sock.c (ffffffff8187703f)
Location: include/net/sock.h:1221
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818fb114)
Location: include/net/sock.h:1221
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81900342)
Location: include/net/sock.h:1221
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
In net/core/sock.c (ffffffff818977df)
Location: include/net/sock.h:1259
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81929042)
Location: include/net/sock.h:1259
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff8192a752)
Location: include/net/sock.h:1259
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
In net/core/sock.c (ffffffff818e1cf1)
Location: include/net/sock.h:1262
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8198bf55)
Location: include/net/sock.h:1262
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff8198d9bf)
Location: include/net/sock.h:1262
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
In net/core/sock.c (ffffffff81913eb1)
Location: include/net/sock.h:1272
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819c28a5)
Location: include/net/sock.h:1272
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff819c4571)
Location: include/net/sock.h:1272
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
In net/core/sock.c (ffffffff819e5b01)
Location: include/net/sock.h:1320
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
```
```
In net/ipv4/tcp.c (ffffffff81aade52)
Location: include/net/sock.h:1320
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81ab32b1)
Location: include/net/sock.h:1320
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
In net/core/sock.c (ffffffff819e55d1)
Location: include/net/sock.h:1336
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
```
```
In net/ipv4/tcp.c (ffffffff81ab80e2)
Location: include/net/sock.h:1336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81abe219)
Location: include/net/sock.h:1336
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
In net/core/sock.c (ffffffff819cb6e1)
Location: include/net/sock.h:1348
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
```
```
In net/ipv4/tcp.c (ffffffff81aa341f)
Location: include/net/sock.h:1348
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81aa92f9)
Location: include/net/sock.h:1348
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
In net/core/sock.c (ffffffff81a7ad6b)
Location: include/net/sock.h:1360
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
```
```
In net/ipv4/tcp.c (ffffffff81b5f5ea)
Location: include/net/sock.h:1360
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81b651e5)
Location: include/net/sock.h:1360
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
In net/core/sock.c (ffffffff81beec7d)
Location: include/net/sock.h:1414
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
```
```
In net/ipv4/tcp.c (ffffffff81cee05a)
Location: include/net/sock.h:1414
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81cf3b27)
Location: include/net/sock.h:1414
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
In net/core/sock.c (ffffffff81d9e3ae)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/tcp.c (ffffffff81eb12fa)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81eb8527)
Location: include/net/sock.h:1459
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
In net/core/sock.c (ffffffff81e0cc26)
Location: include/net/sock.h:1450
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/tcp.c (ffffffff81f0f98a)
Location: include/net/sock.h:1450
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81f16997)
Location: include/net/sock.h:1450
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
In net/core/sock.c (ffffffff81ec95a6)
Location: include/net/sock.h:1425
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/tcp.c (ffffffff81fd3b7a)
Location: include/net/sock.h:1425
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81fdb807)
Location: include/net/sock.h:1425
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
In net/core/sock.c (ffff800010babb94)
Location: include/net/sock.h:1272
Inline: True
```
```
In net/ipv4/tcp.c (ffff800010c755d0)
Location: include/net/sock.h:1272
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffff800010c76f9c)
Location: include/net/sock.h:1272
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
In net/core/sock.c (c0cca730)
Location: include/net/sock.h:1272
Inline: True
```
```
In net/ipv4/tcp.c (c0d83d04)
Location: include/net/sock.h:1272
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (c0d854f8)
Location: include/net/sock.h:1272
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
In net/core/sock.c (c000000000c820e8)
Location: include/net/sock.h:1272
Inline: True
```
```
In net/ipv4/tcp.c (c000000000d7cc6c)
Location: include/net/sock.h:1272
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (c000000000d7f21c)
Location: include/net/sock.h:1272
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
In net/core/sock.c (ffffffe00073f1da)
Location: include/net/sock.h:1272
Inline: True
```
```
In net/ipv4/tcp.c (ffffffe0007d8884)
Location: include/net/sock.h:1272
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffe0007da204)
Location: include/net/sock.h:1272
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
In net/core/sock.c (ffffffff818b3eb1)
Location: include/net/sock.h:1272
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81962715)
Location: include/net/sock.h:1272
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff819643e1)
Location: include/net/sock.h:1272
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
In net/core/sock.c (ffffffff8186de01)
Location: include/net/sock.h:1272
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8191c205)
Location: include/net/sock.h:1272
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff8191ded1)
Location: include/net/sock.h:1272
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
In net/core/sock.c (ffffffff81904eb1)
Location: include/net/sock.h:1272
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819ccee5)
Location: include/net/sock.h:1272
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff819cebb1)
Location: include/net/sock.h:1272
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
In net/core/sock.c (ffffffff81925f81)
Location: include/net/sock.h:1272
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819d6a75)
Location: include/net/sock.h:1272
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff819d8741)
Location: include/net/sock.h:1272
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
</details>
</li>
</ul>

## Differences

# Function: <code>__inet_lookup</code>

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
In net/ipv4/tcp_ipv4.c (ffffffff8177e8db)
Location: include/net/inet_hashtables.h:300
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff817ebddc)
Location: include/net/inet_hashtables.h:298
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff8181c760)
Location: include/net/inet_hashtables.h:298
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff8183cc6f)
Location: include/net/inet_hashtables.h:303
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff818bc386)
Location: include/net/inet_hashtables.h:305
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81911d76)
Location: include/net/inet_hashtables.h:322
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/core/filter.c (ffffffff818d8cb0)
Location: include/net/inet_hashtables.h:333
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940547)
Location: include/net/inet_hashtables.h:333
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/core/filter.c (ffffffff81926cb5)
Location: include/net/inet_hashtables.h:329
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4a78)
Location: include/net/inet_hashtables.h:329
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/core/filter.c (ffffffff81959375)
Location: include/net/inet_hashtables.h:335
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db778)
Location: include/net/inet_hashtables.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/core/filter.c (ffffffff81a2bd01)
Location: include/net/inet_hashtables.h:341
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac884e)
Location: include/net/inet_hashtables.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/core/filter.c (ffffffff81a2ceb1)
Location: include/net/inet_hashtables.h:342
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad47ff)
Location: include/net/inet_hashtables.h:342
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/core/filter.c (ffffffff81a143f1)
Location: include/net/inet_hashtables.h:342
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf8da)
Location: include/net/inet_hashtables.h:342
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/core/filter.c (ffffffff81ac5cc1)
Location: include/net/inet_hashtables.h:348
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d445)
Location: include/net/inet_hashtables.h:348
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/core/filter.c (ffffffff81c40d88)
Location: include/net/inet_hashtables.h:292
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d372)
Location: include/net/inet_hashtables.h:292
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/core/filter.c (ffffffff81df6499)
Location: include/net/inet_hashtables.h:392
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2dc3)
Location: include/net/inet_hashtables.h:392
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/core/filter.c (ffffffff81e67da9)
Location: include/net/inet_hashtables.h:392
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31ab2)
Location: include/net/inet_hashtables.h:392
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/core/filter.c (ffffffff81f26f79)
Location: include/net/inet_hashtables.h:408
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff4dcf)
Location: include/net/inet_hashtables.h:408
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__inet_lookup_skb
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
In net/core/filter.c (ffff800010bfa834)
Location: include/net/inet_hashtables.h:335
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8eb44)
Location: include/net/inet_hashtables.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/core/filter.c (c0d14320)
Location: include/net/inet_hashtables.h:335
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (c0d9db10)
Location: include/net/inet_hashtables.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/core/filter.c (c000000000ce2b90)
Location: include/net/inet_hashtables.h:335
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d600)
Location: include/net/inet_hashtables.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/core/filter.c (ffffffe00077c556)
Location: include/net/inet_hashtables.h:335
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eed9a)
Location: include/net/inet_hashtables.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/core/filter.c (ffffffff818f9345)
Location: include/net/inet_hashtables.h:335
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b5e8)
Location: include/net/inet_hashtables.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/core/filter.c (ffffffff818b3175)
Location: include/net/inet_hashtables.h:335
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819350a8)
Location: include/net/inet_hashtables.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/core/filter.c (ffffffff8194a375)
Location: include/net/inet_hashtables.h:335
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5db8)
Location: include/net/inet_hashtables.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
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
In net/core/filter.c (ffffffff8196bc85)
Location: include/net/inet_hashtables.h:335
Inline: True
Inline callers:
  - net/core/filter.c:sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819efa7c)
Location: include/net/inet_hashtables.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
</details>
</li>
</ul>

## Differences

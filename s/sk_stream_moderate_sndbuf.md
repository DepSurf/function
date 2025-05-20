# Function: <code>sk_stream_moderate_sndbuf</code>

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
In net/core/sock.c (ffffffff8170203f)
Location: include/net/sock.h:2045
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
```
```
In net/ipv4/tcp.c (ffffffff81768fdc)
Location: include/net/sock.h:2045
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
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
In net/core/sock.c (ffffffff8176813d)
Location: include/net/sock.h:2018
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
```
```
In net/ipv4/tcp.c (ffffffff817d595b)
Location: include/net/sock.h:2018
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
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
In net/core/sock.c (ffffffff8179512c)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81805952)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
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
In net/core/sock.c (ffffffff817b3800)
Location: include/net/sock.h:2108
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81825dec)
Location: include/net/sock.h:2108
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
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
In net/core/sock.c (ffffffff8182bbf6)
Location: include/net/sock.h:2122
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff818a3eae)
Location: include/net/sock.h:2122
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
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
In net/core/sock.c (ffffffff81875749)
Location: include/net/sock.h:2125
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff818f9c09)
Location: include/net/sock.h:2125
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
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
In net/core/sock.c (ffffffff81896051)
Location: include/net/sock.h:2215
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81927b33)
Location: include/net/sock.h:2215
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
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
In net/core/sock.c (ffffffff818e055f)
Location: include/net/sock.h:2221
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff8198aa59)
Location: include/net/sock.h:2221
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
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
In net/core/sock.c (ffffffff8191271f)
Location: include/net/sock.h:2231
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff819c12a8)
Location: include/net/sock.h:2231
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
In net/core/sock.c (ffffffff819e467b)
Location: include/net/sock.h:2280
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81aac9d5)
Location: include/net/sock.h:2280
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/mptcp/protocol.c (ffffffff81baa5c1)
Location: include/net/sock.h:2280
Inline: True
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
In net/core/sock.c (ffffffff819e3ee4)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81ab432b)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/mptcp/protocol.c (ffffffff81bbaf2f)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
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
In net/core/sock.c (ffffffff819c9f71)
Location: include/net/sock.h:2337
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81a9f49b)
Location: include/net/sock.h:2337
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/mptcp/protocol.c (ffffffff81baa4c7)
Location: include/net/sock.h:2337
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
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
In net/core/sock.c (ffffffff81a7943d)
Location: include/net/sock.h:2388
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81b5b24b)
Location: include/net/sock.h:2388
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/mptcp/protocol.c (ffffffff81c777f7)
Location: include/net/sock.h:2388
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
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
In net/core/sock.c (ffffffff81bed84f)
Location: include/net/sock.h:2513
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81ce9bd9)
Location: include/net/sock.h:2513
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
```
```
In net/mptcp/protocol.c (ffffffff81e1c8ac)
Location: include/net/sock.h:2513
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
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
In net/core/sock.c (ffffffff81d9de60)
Location: include/net/sock.h:2561
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81ead881)
Location: include/net/sock.h:2561
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
```
```
In net/mptcp/protocol.c (ffffffff81ff3f2c)
Location: include/net/sock.h:2561
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
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
In net/core/sock.c (ffffffff81e0c6fc)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81f0bfa0)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
```
```
In net/mptcp/protocol.c (ffffffff8207053c)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
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
In net/core/sock.c (ffffffff81ec90b7)
Location: include/net/sock.h:2539
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81fd0060)
Location: include/net/sock.h:2539
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
```
```
In net/mptcp/protocol.c (ffffffff82144b74)
Location: include/net/sock.h:2539
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
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
In net/core/sock.c (ffff800010bacd3c)
Location: include/net/sock.h:2231
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffff800010c7410c)
Location: include/net/sock.h:2231
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
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
In net/core/sock.c (c0cc88d4)
Location: include/net/sock.h:2231
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (c0d82744)
Location: include/net/sock.h:2231
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
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
In net/core/sock.c (c000000000c7fb90)
Location: include/net/sock.h:2231
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (c000000000d7b14c)
Location: include/net/sock.h:2231
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
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
In net/core/sock.c (ffffffe00073d6cc)
Location: include/net/sock.h:2231
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffe0007d769a)
Location: include/net/sock.h:2231
Inline: True
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
In net/core/sock.c (ffffffff818b271f)
Location: include/net/sock.h:2231
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81961118)
Location: include/net/sock.h:2231
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
In net/core/sock.c (ffffffff8186c66f)
Location: include/net/sock.h:2231
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff8191ac08)
Location: include/net/sock.h:2231
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
In net/core/sock.c (ffffffff8190371f)
Location: include/net/sock.h:2231
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff819cb8e8)
Location: include/net/sock.h:2231
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
In net/core/sock.c (ffffffff81924713)
Location: include/net/sock.h:2231
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff819d5478)
Location: include/net/sock.h:2231
Inline: True
```
</details>
</li>
</ul>

## Differences

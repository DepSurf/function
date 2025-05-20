# Function: <code>skb_set_hash_from_sk</code>

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
In net/core/sock.c (ffffffff81702535)
Location: include/net/sock.h:1950
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81775ef5)
Location: include/net/sock.h:1950
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
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
In net/core/sock.c (ffffffff81769765)
Location: include/net/sock.h:1914
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff817e2e86)
Location: include/net/sock.h:1914
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
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
In net/core/sock.c (ffffffff81796685)
Location: include/net/sock.h:1976
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81813536)
Location: include/net/sock.h:1976
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
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
In net/core/sock.c (ffffffff817b4a55)
Location: include/net/sock.h:2000
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81833723)
Location: include/net/sock.h:2000
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
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
In net/core/sock.c (ffffffff8182cc8c)
Location: include/net/sock.h:2014
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/ipv4/tcp_output.c (ffffffff818b2a9b)
Location: include/net/sock.h:2014
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
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
In net/core/sock.c (ffffffff81876a78)
Location: include/net/sock.h:2017
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/ipv4/tcp_output.c (ffffffff81907f94)
Location: include/net/sock.h:2017
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (ffffffff81897248)
Location: include/net/sock.h:2107
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/ipv4/tcp_output.c (ffffffff81936283)
Location: include/net/sock.h:2107
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (ffffffff818e1698)
Location: include/net/sock.h:2113
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/ipv4/tcp_output.c (ffffffff8199a63c)
Location: include/net/sock.h:2113
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (ffffffff81913888)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/ipv4/tcp_output.c (ffffffff819d1088)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (ffffffff819e5f4c)
Location: include/net/sock.h:2172
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/ipv4/tcp_output.c (ffffffff81abe10c)
Location: include/net/sock.h:2172
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (ffffffff819e531c)
Location: include/net/sock.h:2191
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/ipv4/tcp_output.c (ffffffff81ac99e8)
Location: include/net/sock.h:2191
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (ffffffff819cb34b)
Location: include/net/sock.h:2208
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/ipv4/tcp_output.c (ffffffff81ab4bf2)
Location: include/net/sock.h:2208
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (ffffffff81a7a9cc)
Location: include/net/sock.h:2248
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/ipv4/tcp_output.c (ffffffff81b71bad)
Location: include/net/sock.h:2248
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (ffffffff81bee8ac)
Location: include/net/sock.h:2366
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81d01325)
Location: include/net/sock.h:2366
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (ffffffff81d9aedc)
Location: include/net/sock.h:2401
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ec6485)
Location: include/net/sock.h:2401
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (ffffffff81e0a0e5)
Location: include/net/sock.h:2389
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81f24bbf)
Location: include/net/sock.h:2389
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (ffffffff81ec6ad5)
Location: include/net/sock.h:2379
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9391)
Location: include/net/sock.h:2379
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (ffff800010baaac8)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/ipv4/tcp_output.c (ffff800010c83cfc)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (c0cc9d7c)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/ipv4/tcp_output.c (c0d92f7c)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (c000000000c81ab4)
Location: include/net/sock.h:2123
Inline: True
```
```
In net/ipv4/tcp_output.c (c000000000d8f6b8)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (ffffffe00073ec3a)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/ipv4/tcp_output.c (ffffffe0007e57de)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (ffffffff818b3888)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/ipv4/tcp_output.c (ffffffff81970ef8)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (ffffffff8186d7d8)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/ipv4/tcp_output.c (ffffffff8192a9c8)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (ffffffff81904888)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/ipv4/tcp_output.c (ffffffff819db6c8)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (ffffffff81925928)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/ipv4/tcp_output.c (ffffffff819e5348)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
</details>
</li>
</ul>

## Differences

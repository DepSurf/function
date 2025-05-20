# Function: <code>inet_csk_enter_pingpong_mode</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8198a489)
Location: include/net/inet_connection_sock.h:316
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81994ed0)
Location: include/net/inet_connection_sock.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
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
In net/ipv4/tcp.c (ffffffff819bea30)
Location: include/net/inet_connection_sock.h:316
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819cba20)
Location: include/net/inet_connection_sock.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
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
In net/ipv4/tcp.c (ffffffff81aa8f5c)
Location: include/net/inet_connection_sock.h:327
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_quickack
```
```
In net/ipv4/tcp_input.c (ffffffff81ab89cf)
Location: include/net/inet_connection_sock.h:327
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
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
In net/ipv4/tcp.c (ffffffff81ab6d0c)
Location: include/net/inet_connection_sock.h:322
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_quickack
```
```
In net/ipv4/tcp_input.c (ffffffff81ac3d37)
Location: include/net/inet_connection_sock.h:322
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
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
In net/ipv4/tcp.c (ffffffff81aa33bc)
Location: include/net/inet_connection_sock.h:320
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_quickack
```
```
In net/ipv4/tcp_input.c (ffffffff81aaee47)
Location: include/net/inet_connection_sock.h:320
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
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
In net/ipv4/tcp.c (ffffffff81b5d087)
Location: include/net/inet_connection_sock.h:320
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81b6bb27)
Location: include/net/inet_connection_sock.h:320
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
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
In net/ipv4/tcp.c (ffffffff81ceba73)
Location: include/net/inet_connection_sock.h:326
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81cfaccc)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_output.c (ffffffff81d0152f)
Location: include/net/inet_connection_sock.h:326
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
In net/ipv4/tcp.c (ffffffff81eaf903)
Location: include/net/inet_connection_sock.h:329
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81ebf749)
Location: include/net/inet_connection_sock.h:329
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_output.c (ffffffff81ec668f)
Location: include/net/inet_connection_sock.h:329
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
In net/ipv4/tcp.c (ffffffff81f0dd35)
Location: include/net/inet_connection_sock.h:329
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81f1dcb6)
Location: include/net/inet_connection_sock.h:329
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_output.c (ffffffff81f24e0d)
Location: include/net/inet_connection_sock.h:329
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
In net/ipv4/tcp.c (ffffffff81fd1e5b)
Location: include/net/inet_connection_sock.h:330
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81fe2386)
Location: include/net/inet_connection_sock.h:330
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
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
In net/ipv4/tcp.c (ffff800010c720d8)
Location: include/net/inet_connection_sock.h:316
Inline: True
```
```
In net/ipv4/tcp_input.c (ffff800010c7e6ac)
Location: include/net/inet_connection_sock.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
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
In net/ipv4/tcp.c (c0d80c58)
Location: include/net/inet_connection_sock.h:316
Inline: True
```
```
In net/ipv4/tcp_input.c (c0d8d66c)
Location: include/net/inet_connection_sock.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
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
In net/ipv4/tcp.c (c000000000d7a518)
Location: include/net/inet_connection_sock.h:316
Inline: True
```
```
In net/ipv4/tcp_input.c (c000000000d888ec)
Location: include/net/inet_connection_sock.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
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
In net/ipv4/tcp.c (ffffffe0007d6fc2)
Location: include/net/inet_connection_sock.h:316
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffe0007e09d8)
Location: include/net/inet_connection_sock.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
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
In net/ipv4/tcp.c (ffffffff8195e8a0)
Location: include/net/inet_connection_sock.h:316
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8196b890)
Location: include/net/inet_connection_sock.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
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
In net/ipv4/tcp.c (ffffffff81918390)
Location: include/net/inet_connection_sock.h:316
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81925380)
Location: include/net/inet_connection_sock.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
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
In net/ipv4/tcp.c (ffffffff819c9070)
Location: include/net/inet_connection_sock.h:316
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819d6060)
Location: include/net/inet_connection_sock.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
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
In net/ipv4/tcp.c (ffffffff819d2bc0)
Location: include/net/inet_connection_sock.h:316
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819dfc60)
Location: include/net/inet_connection_sock.h:316
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
</details>
</li>
</ul>

## Differences

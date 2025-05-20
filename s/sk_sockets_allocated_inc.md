# Function: <code>sk_sockets_allocated_inc</code>

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
In net/core/sock.c (ffffffff81703ff8)
Location: include/net/sock.h:1261
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81765932)
Location: include/net/sock.h:1261
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
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
In net/core/sock.c (ffffffff8176aa5c)
Location: include/net/sock.h:1182
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff817d1ea4)
Location: include/net/sock.h:1182
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
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
In net/core/sock.c (ffffffff81797b89)
Location: include/net/sock.h:1222
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81801e1d)
Location: include/net/sock.h:1222
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
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
In net/core/sock.c (ffffffff817b577d)
Location: include/net/sock.h:1225
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81821f34)
Location: include/net/sock.h:1225
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
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
In net/core/sock.c (ffffffff8182dc29)
Location: include/net/sock.h:1229
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff818a0fb3)
Location: include/net/sock.h:1229
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
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
In net/core/sock.c (ffffffff81878000)
Location: include/net/sock.h:1243
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff818f5b27)
Location: include/net/sock.h:1243
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
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
In net/core/sock.c (ffffffff818984e2)
Location: include/net/sock.h:1281
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81923787)
Location: include/net/sock.h:1281
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
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
In net/core/sock.c (ffffffff818e2a8f)
Location: include/net/sock.h:1284
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff819861a7)
Location: include/net/sock.h:1284
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
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
In net/core/sock.c (ffffffff81914c6a)
Location: include/net/sock.h:1294
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff819bc937)
Location: include/net/sock.h:1294
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
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
In net/core/sock.c (ffffffff819e71db)
Location: include/net/sock.h:1342
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81aa7853)
Location: include/net/sock.h:1342
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/mptcp/protocol.c (ffffffff81bab4cd)
Location: include/net/sock.h:1342
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
In net/core/sock.c (ffffffff819e6a1f)
Location: include/net/sock.h:1358
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81ab1ef4)
Location: include/net/sock.h:1358
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/mptcp/protocol.c (ffffffff81bbdbca)
Location: include/net/sock.h:1358
Inline: True
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
In net/core/sock.c (ffffffff819cc823)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81a9d183)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/mptcp/protocol.c (ffffffff81bad1fa)
Location: include/net/sock.h:1373
Inline: True
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
In net/core/sock.c (ffffffff81a7bed7)
Location: include/net/sock.h:1385
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81b58ff3)
Location: include/net/sock.h:1385
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/mptcp/protocol.c (ffffffff81c7a09a)
Location: include/net/sock.h:1385
Inline: True
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
In net/core/sock.c (ffffffff81befd28)
Location: include/net/sock.h:1439
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81ce7303)
Location: include/net/sock.h:1439
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/mptcp/protocol.c (ffffffff81e1ea96)
Location: include/net/sock.h:1439
Inline: True
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
In net/core/sock.c (ffffffff81d9cb98)
Location: include/net/sock.h:1503
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81eaaa2f)
Location: include/net/sock.h:1503
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/mptcp/protocol.c (ffffffff81ff5949)
Location: include/net/sock.h:1503
Inline: True
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
In net/core/sock.c (ffffffff81e0b3f0)
Location: include/net/sock.h:1494
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81f0921f)
Location: include/net/sock.h:1494
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/mptcp/protocol.c (ffffffff8206f536)
Location: include/net/sock.h:1494
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_init_sock
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
In net/core/sock.c (ffffffff81ec7de0)
Location: include/net/sock.h:1469
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81fcd686)
Location: include/net/sock.h:1469
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/mptcp/protocol.c (ffffffff82143642)
Location: include/net/sock.h:1469
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_init_sock
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
In net/core/sock.c (ffff800010bad950)
Location: include/net/sock.h:1294
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffff800010c6ec5c)
Location: include/net/sock.h:1294
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
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
In net/core/sock.c (c0ccb518)
Location: include/net/sock.h:1294
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (c0d7d664)
Location: include/net/sock.h:1294
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
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
In net/core/sock.c (c000000000c83250)
Location: include/net/sock.h:1294
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (c000000000d74ba0)
Location: include/net/sock.h:1294
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
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
In net/core/sock.c (ffffffe00073fb2c)
Location: include/net/sock.h:1294
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffe0007d3906)
Location: include/net/sock.h:1294
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
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
In net/core/sock.c (ffffffff818b4c6a)
Location: include/net/sock.h:1294
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff8195c7a7)
Location: include/net/sock.h:1294
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
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
In net/core/sock.c (ffffffff8186ebba)
Location: include/net/sock.h:1294
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81916297)
Location: include/net/sock.h:1294
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
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
In net/core/sock.c (ffffffff81905c6a)
Location: include/net/sock.h:1294
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff819c6f77)
Location: include/net/sock.h:1294
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
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
In net/core/sock.c (ffffffff81926c9f)
Location: include/net/sock.h:1294
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff819d0ac7)
Location: include/net/sock.h:1294
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
```
</details>
</li>
</ul>

## Differences

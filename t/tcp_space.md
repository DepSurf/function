# Function: <code>tcp_space</code>

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
In net/ipv4/tcp_input.c (ffffffff8176b49b)
Location: include/net/tcp.h:1207
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81775ca5)
Location: include/net/tcp.h:1207
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff817db8e8)
Location: include/net/tcp.h:1217
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff817e2bf5)
Location: include/net/tcp.h:1217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff8180b948)
Location: include/net/tcp.h:1274
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81813285)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff8182b7d8)
Location: include/net/tcp.h:1313
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81833475)
Location: include/net/tcp.h:1313
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff818a9f28)
Location: include/net/tcp.h:1294
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff818b2795)
Location: include/net/tcp.h:1294
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff818ff0e8)
Location: include/net/tcp.h:1311
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81907c99)
Location: include/net/tcp.h:1311
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff8192e0f8)
Location: include/net/tcp.h:1369
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81935f69)
Location: include/net/tcp.h:1369
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff81990885)
Location: include/net/tcp.h:1371
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8199a32a)
Location: include/net/tcp.h:1371
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff819c7464)
Location: include/net/tcp.h:1392
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819d0d50)
Location: include/net/tcp.h:1392
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff81ab2be5)
Location: include/net/tcp.h:1406
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81abddaa)
Location: include/net/tcp.h:1406
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/mptcp/subflow.c (ffffffff81bafa0a)
Location: include/net/tcp.h:1406
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
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
In net/ipv4/tcp_input.c (ffffffff81abddf5)
Location: include/net/tcp.h:1413
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81ac968a)
Location: include/net/tcp.h:1413
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/mptcp/protocol.c (ffffffff81bbddf7)
Location: include/net/tcp.h:1413
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mptcp/subflow.c (ffffffff81bc32da)
Location: include/net/tcp.h:1413
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
```
```
In net/mptcp/options.c (ffffffff81bc4ac5)
Location: include/net/tcp.h:1413
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
In net/ipv4/tcp_input.c (ffffffff81aa8978)
Location: include/net/tcp.h:1405
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81ab453a)
Location: include/net/tcp.h:1405
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff81b652f8)
Location: include/net/tcp.h:1398
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81b714b0)
Location: include/net/tcp.h:1398
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff81cf5086)
Location: include/net/tcp.h:1430
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81d00b70)
Location: include/net/tcp.h:1430
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff81eb9ab6)
Location: include/net/tcp.h:1446
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81ec5cc0)
Location: include/net/tcp.h:1446
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff81f17ec6)
Location: include/net/tcp.h:1444
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81f24274)
Location: include/net/tcp.h:1444
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff81fdaab1)
Location: include/net/tcp.h:1509
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81fe8ae1)
Location: include/net/tcp.h:1509
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffff800010c78100)
Location: include/net/tcp.h:1392
Inline: True
```
```
In net/ipv4/tcp_output.c (ffff800010c839e8)
Location: include/net/tcp.h:1392
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (c0d879c4)
Location: include/net/tcp.h:1392
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (c0d92c08)
Location: include/net/tcp.h:1392
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (c000000000d837b8)
Location: include/net/tcp.h:1392
Inline: True
```
```
In net/ipv4/tcp_output.c (c000000000d8f2f0)
Location: include/net/tcp.h:1392
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffe0007dd12e)
Location: include/net/tcp.h:1392
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffe0007e550a)
Location: include/net/tcp.h:1392
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff819672d4)
Location: include/net/tcp.h:1392
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81970bc0)
Location: include/net/tcp.h:1392
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff81920dc4)
Location: include/net/tcp.h:1392
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8192a690)
Location: include/net/tcp.h:1392
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff819d1aa4)
Location: include/net/tcp.h:1392
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819db390)
Location: include/net/tcp.h:1392
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff819db634)
Location: include/net/tcp.h:1392
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819e5010)
Location: include/net/tcp.h:1392
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
```
</details>
</li>
</ul>

## Differences

# Function: <code>tcp_clear_all_retrans_hints</code>

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
In net/ipv4/tcp.c (ffffffff81768167)
Location: include/net/tcp.h:1316
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff8176a85f)
Location: include/net/tcp.h:1316
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177c9cf)
Location: include/net/tcp.h:1316
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In net/ipv4/tcp.c (ffffffff817d4a4d)
Location: include/net/tcp.h:1332
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff817d72e3)
Location: include/net/tcp.h:1332
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea2fb)
Location: include/net/tcp.h:1332
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In net/ipv4/tcp.c (ffffffff8180479a)
Location: include/net/tcp.h:1389
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff818073ef)
Location: include/net/tcp.h:1389
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818b31)
Location: include/net/tcp.h:1389
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In net/ipv4/tcp.c (ffffffff81824a07)
Location: include/net/tcp.h:1429
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81827a3f)
Location: include/net/tcp.h:1429
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81839308)
Location: include/net/tcp.h:1429
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In net/ipv4/tcp.c (ffffffff818a6703)
Location: include/net/tcp.h:1410
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff818a73dd)
Location: include/net/tcp.h:1410
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp.c (ffffffff818fb7a4)
Location: include/net/tcp.h:1427
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff818fc65d)
Location: include/net/tcp.h:1427
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp.c (ffffffff819296f4)
Location: include/net/tcp.h:1487
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff8192a69d)
Location: include/net/tcp.h:1487
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp.c (ffffffff8198c651)
Location: include/net/tcp.h:1489
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff8198d912)
Location: include/net/tcp.h:1489
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp.c (ffffffff819c2fc0)
Location: include/net/tcp.h:1511
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819c4270)
Location: include/net/tcp.h:1511
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp.c (ffffffff81aae616)
Location: include/net/tcp.h:1538
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81aafba3)
Location: include/net/tcp.h:1538
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_timeout_mark_lost
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
In net/ipv4/tcp.c (ffffffff81ab8863)
Location: include/net/tcp.h:1552
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81aba8b3)
Location: include/net/tcp.h:1552
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_timeout_mark_lost
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
In net/ipv4/tcp.c (ffffffff81aa3b63)
Location: include/net/tcp.h:1556
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81aa5b93)
Location: include/net/tcp.h:1556
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp.c (ffffffff81b5fd13)
Location: include/net/tcp.h:1549
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81b61f03)
Location: include/net/tcp.h:1549
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp.c (ffffffff81cee852)
Location: include/net/tcp.h:1596
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81cf0a05)
Location: include/net/tcp.h:1596
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp.c (ffffffff81eb1b48)
Location: include/net/tcp.h:1612
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81eb50c5)
Location: include/net/tcp.h:1612
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp.c (ffffffff81f1016e)
Location: include/net/tcp.h:1625
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81f134f5)
Location: include/net/tcp.h:1625
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp.c (ffffffff81fd436e)
Location: include/net/tcp.h:1695
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81fd79d5)
Location: include/net/tcp.h:1695
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp.c (ffff800010c75d80)
Location: include/net/tcp.h:1511
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffff800010c76f20)
Location: include/net/tcp.h:1511
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp.c (c0d84454)
Location: include/net/tcp.h:1511
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (c0d8541c)
Location: include/net/tcp.h:1511
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp.c (c000000000d7d668)
Location: include/net/tcp.h:1511
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (c000000000d7ed78)
Location: include/net/tcp.h:1511
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp.c (ffffffe0007d8f9c)
Location: include/net/tcp.h:1511
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffe0007d9f38)
Location: include/net/tcp.h:1511
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp.c (ffffffff81962e30)
Location: include/net/tcp.h:1511
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819640e0)
Location: include/net/tcp.h:1511
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp.c (ffffffff8191c920)
Location: include/net/tcp.h:1511
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff8191dbd0)
Location: include/net/tcp.h:1511
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp.c (ffffffff819cd600)
Location: include/net/tcp.h:1511
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819ce8b0)
Location: include/net/tcp.h:1511
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp.c (ffffffff819d7190)
Location: include/net/tcp.h:1511
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819d8440)
Location: include/net/tcp.h:1511
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
</details>
</li>
</ul>

## Differences

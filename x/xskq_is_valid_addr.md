# Function: <code>xskq_is_valid_addr</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff819cc1af)
Location: net/xdp/xsk_queue.h:79
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
  - net/xdp/xsk.c:xsk_umem_peek_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a05390)
Location: net/xdp/xsk_queue.h:80
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
  - net/xdp/xsk.c:xsk_umem_peek_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a74a04)
Location: net/xdp/xsk_queue.h:136
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
  - net/xdp/xsk.c:xsk_umem_peek_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81aaa660)
Location: net/xdp/xsk_queue.h:148
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
  - net/xdp/xsk.c:xsk_umem_peek_addr
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffff800010d7e340)
Location: net/xdp/xsk_queue.h:148
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
  - net/xdp/xsk.c:xsk_umem_peek_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c0e796d0)
Location: net/xdp/xsk_queue.h:148
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
  - net/xdp/xsk.c:xsk_rcv
  - net/xdp/xsk.c:xsk_umem_peek_addr
  - net/xdp/xsk.c:xsk_umem_peek_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c000000000ebeb30)
Location: net/xdp/xsk_queue.h:148
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
  - net/xdp/xsk.c:xsk_umem_peek_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffe0008ac5c4)
Location: net/xdp/xsk_queue.h:148
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
  - net/xdp/xsk.c:xsk_umem_peek_addr
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a499f0)
Location: net/xdp/xsk_queue.h:148
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
  - net/xdp/xsk.c:xsk_umem_peek_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a065e0)
Location: net/xdp/xsk_queue.h:148
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
  - net/xdp/xsk.c:xsk_umem_peek_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ab58a0)
Location: net/xdp/xsk_queue.h:148
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
  - net/xdp/xsk.c:xsk_umem_peek_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ac1959)
Location: net/xdp/xsk_queue.h:148
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
  - net/xdp/xsk.c:xsk_umem_peek_addr
```
</details>
</li>
</ul>

## Differences

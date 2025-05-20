# Function: <code>xsk_umem_extract_offset</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81aaa4a0)
Location: include/net/xdp_sock.h:143
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffff800010d7e268)
Location: include/net/xdp_sock.h:143
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (c0e79758)
Location: include/net/xdp_sock.h:143
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (c000000000ebeb90)
Location: include/net/xdp_sock.h:143
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffe0008ac728)
Location: include/net/xdp_sock.h:143
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffff81a49830)
Location: include/net/xdp_sock.h:143
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffff81a06420)
Location: include/net/xdp_sock.h:143
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffff81ab56e0)
Location: include/net/xdp_sock.h:143
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffff81ac187c)
Location: include/net/xdp_sock.h:143
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_rcv
  - net/xdp/xsk.c:xsk_rcv
  - net/xdp/xsk.c:xsk_umem_peek_addr
```
</details>
</li>
</ul>

## Differences

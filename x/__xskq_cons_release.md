# Function: <code>__xskq_cons_release</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba7a87)
Location: net/xdp/xsk_queue.h:197
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_umem_consume_tx_done
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba962e)
Location: net/xdp/xsk_queue.h:197
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
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
In net/xdp/xsk.c (ffffffff81bb714f)
Location: net/xdp/xsk_queue.h:228
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xsk_tx_release
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9257)
Location: net/xdp/xsk_queue.h:228
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
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
In net/xdp/xsk.c (ffffffff81ba6111)
Location: net/xdp/xsk_queue.h:230
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xsk_tx_release
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba826b)
Location: net/xdp/xsk_queue.h:230
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
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
In net/xdp/xsk.c (ffffffff81c73aa0)
Location: net/xdp/xsk_queue.h:230
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xsk_tx_release
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c75fe8)
Location: net/xdp/xsk_queue.h:230
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
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
In net/xdp/xsk.c (ffffffff81e1829e)
Location: net/xdp/xsk_queue.h:234
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xsk_tx_release
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1a344)
Location: net/xdp/xsk_queue.h:234
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
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
In net/xdp/xsk.c (ffffffff81fef44e)
Location: net/xdp/xsk_queue.h:241
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xsk_tx_release
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff1844)
Location: net/xdp/xsk_queue.h:241
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
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
In net/xdp/xsk.c (ffffffff8206b44a)
Location: net/xdp/xsk_queue.h:235
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xsk_tx_release
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206da7e)
Location: net/xdp/xsk_queue.h:235
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
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
In net/xdp/xsk.c (ffffffff8213f0e7)
Location: net/xdp/xsk_queue.h:279
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xsk_tx_release
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82141abe)
Location: net/xdp/xsk_queue.h:279
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences

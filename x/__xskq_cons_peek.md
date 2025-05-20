# Function: <code>__xskq_cons_peek</code>

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
In net/xdp/xsk.c (ffffffff81ba7a97)
Location: net/xdp/xsk_queue.h:203
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_umem_consume_tx
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba94a5)
Location: net/xdp/xsk_queue.h:203
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
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
In net/xdp/xsk.c (ffffffff81bb7162)
Location: net/xdp/xsk_queue.h:234
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xskq_cons_peek_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb8c81)
Location: net/xdp/xsk_queue.h:234
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
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
In net/xdp/xsk.c (ffffffff81ba611e)
Location: net/xdp/xsk_queue.h:235
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xskq_cons_peek_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba7ea1)
Location: net/xdp/xsk_queue.h:235
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
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
In net/xdp/xsk.c (ffffffff81c73ab0)
Location: net/xdp/xsk_queue.h:235
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c75b31)
Location: net/xdp/xsk_queue.h:235
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
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
In net/xdp/xsk.c (ffffffff81e182ac)
Location: net/xdp/xsk_queue.h:239
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1ab6b)
Location: net/xdp/xsk_queue.h:239
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
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
In net/xdp/xsk.c (ffffffff81fef45c)
Location: net/xdp/xsk_queue.h:246
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff205b)
Location: net/xdp/xsk_queue.h:246
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
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
In net/xdp/xsk.c (ffffffff8206b458)
Location: net/xdp/xsk_queue.h:240
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206e25b)
Location: net/xdp/xsk_queue.h:240
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
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
In net/xdp/xsk.c (ffffffff8213f0f4)
Location: net/xdp/xsk_queue.h:284
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff821422db)
Location: net/xdp/xsk_queue.h:284
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
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

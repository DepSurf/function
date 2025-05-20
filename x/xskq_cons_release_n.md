# Function: <code>xskq_cons_release_n</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb7596)
Location: net/xdp/xsk_queue.h:298
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba654d)
Location: net/xdp/xsk_queue.h:298
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81c74070)
Location: net/xdp/xsk_queue.h:298
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
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
In net/xdp/xsk.c (ffffffff81e1793c)
Location: net/xdp/xsk_queue.h:294
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1a97e)
Location: net/xdp/xsk_queue.h:294
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
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
In net/xdp/xsk.c (ffffffff81fee5f1)
Location: net/xdp/xsk_queue.h:208
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff1e4e)
Location: net/xdp/xsk_queue.h:208
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
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
In net/xdp/xsk.c (ffffffff8206a723)
Location: net/xdp/xsk_queue.h:202
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206e059)
Location: net/xdp/xsk_queue.h:202
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
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
In net/xdp/xsk.c (ffffffff8213de68)
Location: net/xdp/xsk_queue.h:224
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff821420d9)
Location: net/xdp/xsk_queue.h:224
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
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

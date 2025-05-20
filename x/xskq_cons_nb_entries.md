# Function: <code>xskq_cons_nb_entries</code>

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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb69d7)
Location: net/xdp/xsk_queue.h:247
Inline: True
Inline callers:
  - net/xdp/xsk.c:xskq_cons_peek_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb8c77)
Location: net/xdp/xsk_queue.h:247
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
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
In net/xdp/xsk.c (ffffffff81ba5977)
Location: net/xdp/xsk_queue.h:247
Inline: True
Inline callers:
  - net/xdp/xsk.c:xskq_cons_peek_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba7e97)
Location: net/xdp/xsk_queue.h:247
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
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
In net/xdp/xsk.c (ffffffff81c73e90)
Location: net/xdp/xsk_queue.h:247
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c75b27)
Location: net/xdp/xsk_queue.h:247
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
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
In net/xdp/xsk.c (ffffffff81e17753)
Location: net/xdp/xsk_queue.h:251
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1ab61)
Location: net/xdp/xsk_queue.h:251
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
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
In net/xdp/xsk.c (ffffffff81fee493)
Location: net/xdp/xsk_queue.h:258
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff2051)
Location: net/xdp/xsk_queue.h:258
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
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
In net/xdp/xsk.c (ffffffff8206a5bd)
Location: net/xdp/xsk_queue.h:252
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206e251)
Location: net/xdp/xsk_queue.h:252
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
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
In net/xdp/xsk.c (ffffffff8213dd0c)
Location: net/xdp/xsk_queue.h:296
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff821422d1)
Location: net/xdp/xsk_queue.h:296
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
  - net/xdp/xsk_buff_pool.c:xp_can_alloc
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
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

# Function: <code>xskq_cons_release</code>

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
In net/xdp/xsk.c (ffffffff81ba79e8)
Location: net/xdp/xsk_queue.h:245
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_umem_consume_tx
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba95df)
Location: net/xdp/xsk_queue.h:245
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
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
In net/xdp/xsk.c (ffffffff81bb7139)
Location: net/xdp/xsk_queue.h:293
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb91f9)
Location: net/xdp/xsk_queue.h:293
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
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
In net/xdp/xsk.c (ffffffff81ba60d5)
Location: net/xdp/xsk_queue.h:293
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba820c)
Location: net/xdp/xsk_queue.h:293
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
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
In net/xdp/xsk.c (ffffffff81c73a64)
Location: net/xdp/xsk_queue.h:293
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c75f7c)
Location: net/xdp/xsk_queue.h:293
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
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
In net/xdp/xsk.c (ffffffff81e1817d)
Location: net/xdp/xsk_queue.h:289
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1a313)
Location: net/xdp/xsk_queue.h:289
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
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
In net/xdp/xsk.c (ffffffff81fef32d)
Location: net/xdp/xsk_queue.h:296
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff1813)
Location: net/xdp/xsk_queue.h:296
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
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
In net/xdp/xsk.c (ffffffff8206b240)
Location: net/xdp/xsk_queue.h:290
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206da50)
Location: net/xdp/xsk_queue.h:290
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
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
In net/xdp/xsk.c (ffffffff8213f0cd)
Location: net/xdp/xsk_queue.h:334
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82141a90)
Location: net/xdp/xsk_queue.h:334
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_alloc
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

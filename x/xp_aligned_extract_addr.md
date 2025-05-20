# Function: <code>xp_aligned_extract_addr</code>

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
In net/xdp/xsk.c (ffffffff81ba78d0)
Location: include/net/xsk_buff_pool.h:119
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_umem_consume_tx
  - net/xdp/xsk.c:xsk_umem_consume_tx
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba95d2)
Location: include/net/xsk_buff_pool.h:119
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
In net/xdp/xsk.c (ffffffff81bb6fcf)
Location: include/net/xsk_buff_pool.h:157
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xskq_cons_peek_desc_batch
  - net/xdp/xsk.c:xskq_cons_peek_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb91e9)
Location: include/net/xsk_buff_pool.h:157
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
In net/xdp/xsk.c (ffffffff81ba5ef7)
Location: include/net/xsk_buff_pool.h:162
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xskq_cons_peek_desc_batch
  - net/xdp/xsk.c:xskq_cons_peek_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba81f9)
Location: include/net/xsk_buff_pool.h:162
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
In net/xdp/xsk.c (ffffffff81c7388b)
Location: include/net/xsk_buff_pool.h:162
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c75f65)
Location: include/net/xsk_buff_pool.h:162
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
In net/xdp/xsk.c (ffffffff81e18030)
Location: include/net/xsk_buff_pool.h:187
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1a861)
Location: include/net/xsk_buff_pool.h:187
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
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
In net/xdp/xsk.c (ffffffff81fef1e0)
Location: include/net/xsk_buff_pool.h:187
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff1d31)
Location: include/net/xsk_buff_pool.h:187
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
  - net/xdp/xsk_buff_pool.c:__xp_alloc
  - net/xdp/xsk_buff_pool.c:__xp_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff8206df41)
Location: include/net/xsk_buff_pool.h:187
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
  - net/xdp/xsk_buff_pool.c:__xp_alloc
  - net/xdp/xsk_buff_pool.c:__xp_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff82141fc1)
Location: include/net/xsk_buff_pool.h:199
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
  - net/xdp/xsk_buff_pool.c:xp_alloc_new_from_fq
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

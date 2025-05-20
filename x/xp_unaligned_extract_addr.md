# Function: <code>xp_unaligned_extract_addr</code>

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
In net/xdp/xsk.c (ffffffff81ba7864)
Location: include/net/xsk_buff_pool.h:124
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_umem_consume_tx
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba953f)
Location: include/net/xsk_buff_pool.h:124
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_raw_get_dma
  - net/xdp/xsk_buff_pool.c:xp_raw_get_data
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
In net/xdp/xsk.c (ffffffff81bb6f1c)
Location: include/net/xsk_buff_pool.h:162
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xskq_cons_peek_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb8d42)
Location: include/net/xsk_buff_pool.h:162
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_raw_get_dma
  - net/xdp/xsk_buff_pool.c:xp_raw_get_data
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
In net/xdp/xsk.c (ffffffff81ba5e32)
Location: include/net/xsk_buff_pool.h:167
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xskq_cons_peek_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba7f52)
Location: include/net/xsk_buff_pool.h:167
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_raw_get_dma
  - net/xdp/xsk_buff_pool.c:xp_raw_get_data
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
In net/xdp/xsk.c (ffffffff81c737ca)
Location: include/net/xsk_buff_pool.h:167
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c75d1c)
Location: include/net/xsk_buff_pool.h:167
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_raw_get_dma
  - net/xdp/xsk_buff_pool.c:xp_raw_get_data
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
In net/xdp/xsk.c (ffffffff81e17f8a)
Location: include/net/xsk_buff_pool.h:192
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1a01c)
Location: include/net/xsk_buff_pool.h:192
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_raw_get_dma
  - net/xdp/xsk_buff_pool.c:xp_raw_get_data
  - net/xdp/xsk_buff_pool.c:xp_check_unaligned
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
In net/xdp/xsk.c (ffffffff81fef13a)
Location: include/net/xsk_buff_pool.h:192
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff146c)
Location: include/net/xsk_buff_pool.h:192
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_raw_get_dma
  - net/xdp/xsk_buff_pool.c:xp_raw_get_data
  - net/xdp/xsk_buff_pool.c:xp_check_unaligned
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
In net/xdp/xsk.c (ffffffff8206b0d1)
Location: include/net/xsk_buff_pool.h:192
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206d68c)
Location: include/net/xsk_buff_pool.h:192
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_raw_get_dma
  - net/xdp/xsk_buff_pool.c:xp_raw_get_data
  - net/xdp/xsk_buff_pool.c:xp_check_unaligned
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
In net/xdp/xsk.c (ffffffff8213efbc)
Location: include/net/xsk_buff_pool.h:204
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8214152c)
Location: include/net/xsk_buff_pool.h:204
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_raw_get_dma
  - net/xdp/xsk_buff_pool.c:xp_raw_get_data
  - net/xdp/xsk_buff_pool.c:xp_check_unaligned
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

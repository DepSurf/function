# Function: <code>xp_desc_crosses_non_contig_pg</code>

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
In net/xdp/xsk.c (ffffffff81ba7a07)
Location: include/net/xsk_buff_pool.h:107
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_umem_consume_tx
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba9689)
Location: include/net/xsk_buff_pool.h:107
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
In net/xdp/xsk.c (ffffffff81bb718b)
Location: include/net/xsk_buff_pool.h:145
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xskq_cons_peek_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb92cc)
Location: include/net/xsk_buff_pool.h:145
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
In net/xdp/xsk.c (ffffffff81ba6137)
Location: include/net/xsk_buff_pool.h:145
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_desc
  - net/xdp/xsk.c:xskq_cons_peek_desc_batch
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba82dc)
Location: include/net/xsk_buff_pool.h:145
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
In net/xdp/xsk.c (ffffffff81c73ace)
Location: include/net/xsk_buff_pool.h:145
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c76065)
Location: include/net/xsk_buff_pool.h:145
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
In net/xdp/xsk.c (ffffffff81e182c7)
Location: include/net/xsk_buff_pool.h:170
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e19e0a)
Location: include/net/xsk_buff_pool.h:170
Inline: True
Inline callers:
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
In net/xdp/xsk.c (ffffffff81fef477)
Location: include/net/xsk_buff_pool.h:170
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff120a)
Location: include/net/xsk_buff_pool.h:170
Inline: True
Inline callers:
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
In net/xdp/xsk.c (ffffffff8206b111)
Location: include/net/xsk_buff_pool.h:175
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206d42a)
Location: include/net/xsk_buff_pool.h:175
Inline: True
Inline callers:
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
In net/xdp/xsk.c (ffffffff8213f008)
Location: include/net/xsk_buff_pool.h:182
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:xsk_tx_peek_desc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff821412ca)
Location: include/net/xsk_buff_pool.h:182
Inline: True
Inline callers:
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

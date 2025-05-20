# Function: <code>dma_sync_single_range_for_cpu</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba97b2)
Location: include/linux/dma-mapping.h:603
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81bb93fa)
Location: include/linux/dma-mapping.h:289
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow
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
In net/xdp/xsk_buff_pool.c (ffffffff81ba83fa)
Location: include/linux/dma-mapping.h:332
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow
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
In net/xdp/xsk_buff_pool.c (ffffffff81c75c6a)
Location: include/linux/dma-mapping.h:340
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81e19f5a)
Location: include/linux/dma-mapping.h:340
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ff138a)
Location: include/linux/dma-mapping.h:345
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow
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
In net/xdp/xsk_buff_pool.c (ffffffff8206d5aa)
Location: include/linux/dma-mapping.h:346
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow
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
In drivers/virtio/virtio_ring.c (ffffffff81aa5e79)
Location: include/linux/dma-mapping.h:351
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_dma_sync_single_range_for_cpu
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8214144a)
Location: include/linux/dma-mapping.h:351
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow
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

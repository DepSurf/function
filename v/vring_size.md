# Function: <code>vring_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (0)
Location: include/uapi/linux/virtio_ring.h:153
Inline: True
```
```
In drivers/virtio/virtio_pci_modern.c (0)
Location: include/uapi/linux/virtio_ring.h:153
Inline: True
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: include/uapi/linux/virtio_ring.h:153
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8150f88d)
Location: include/uapi/linux/virtio_ring.h:153
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153ba3d)
Location: include/uapi/linux/virtio_ring.h:153
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154f375)
Location: include/uapi/linux/virtio_ring.h:153
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b2b35)
Location: include/uapi/linux/virtio_ring.h:153
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815eaf6c)
Location: include/uapi/linux/virtio_ring.h:153
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81605e59)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81637fd9)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81659dc9)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f45e2)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff818f6e5e)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170b370)
Location: include/uapi/linux/virtio_ring.h:203
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca792)
Location: include/uapi/linux/virtio_ring.h:203
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819ccf1e)
Location: include/uapi/linux/virtio_ring.h:203
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
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
In drivers/virtio/virtio_ring.c (ffffffff817281d0)
Location: include/uapi/linux/virtio_ring.h:203
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9c18)
Location: include/uapi/linux/virtio_ring.h:203
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819cc76e)
Location: include/uapi/linux/virtio_ring.h:203
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
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
In drivers/virtio/virtio_ring.c (ffffffff8170c700)
Location: include/uapi/linux/virtio_ring.h:203
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819aec2c)
Location: include/uapi/linux/virtio_ring.h:203
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819b191e)
Location: include/uapi/linux/virtio_ring.h:203
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
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
In drivers/virtio/virtio_ring.c (ffffffff81788af0)
Location: include/uapi/linux/virtio_ring.h:203
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5d20b)
Location: include/uapi/linux/virtio_ring.h:203
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81a600a8)
Location: include/uapi/linux/virtio_ring.h:203
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
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
In drivers/virtio/virtio_ring.c (ffffffff818bf16e)
Location: include/uapi/linux/virtio_ring.h:203
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcd30f)
Location: include/uapi/linux/virtio_ring.h:203
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81bd0531)
Location: include/uapi/linux/virtio_ring.h:203
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
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
In drivers/virtio/virtio_ring.c (ffffffff81a0d952)
Location: include/uapi/linux/virtio_ring.h:209
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_split
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_split
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_split
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d78c43)
Location: include/uapi/linux/virtio_ring.h:209
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81d7b932)
Location: include/uapi/linux/virtio_ring.h:209
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
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
In drivers/virtio/virtio_ring.c (ffffffff81a568b9)
Location: include/uapi/linux/virtio_ring.h:209
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_split
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_split
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_split
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de6b93)
Location: include/uapi/linux/virtio_ring.h:209
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81de9afa)
Location: include/uapi/linux/virtio_ring.h:209
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
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
In drivers/virtio/virtio_ring.c (ffffffff81aa79d9)
Location: include/uapi/linux/virtio_ring.h:209
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_split
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_split
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_split
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9cd73)
Location: include/uapi/linux/virtio_ring.h:209
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81e9fd3a)
Location: include/uapi/linux/virtio_ring.h:209
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010824304)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b80770)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffff800010b830dc)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c09415e8)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
```
In drivers/remoteproc/remoteproc_core.c (c0c63d48)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
```
In drivers/remoteproc/remoteproc_virtio.c (c0c66420)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cc244)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5cf24)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
```
In drivers/remoteproc/remoteproc_virtio.c (c000000000c604c4)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
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
In drivers/virtio/virtio_ring.c (ffffffe00051a1a2)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8161fc69)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81895912)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff8189818e)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
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
In drivers/virtio/virtio_ring.c (ffffffff816141f9)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
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
In drivers/virtio/virtio_ring.c (ffffffff8164dc09)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81668299)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81906072)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819088ee)
Location: include/uapi/linux/virtio_ring.h:177
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
</details>
</li>
</ul>

## Differences

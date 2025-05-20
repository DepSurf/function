# Function: <code>blk_rq_nr_phys_segments</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8141e4da)
Location: include/linux/blkdev.h:1184
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffffffff81636053)
Location: include/linux/blkdev.h:1184
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8142bda8)
Location: include/linux/blkdev.h:1209
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164b094)
Location: include/linux/blkdev.h:1209
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8145716a)
Location: include/linux/blkdev.h:1224
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b43e4)
Location: include/linux/blkdev.h:1224
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8148ab55)
Location: include/linux/blkdev.h:1259
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f0518)
Location: include/linux/blkdev.h:1259
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814a46aa)
Location: include/linux/blkdev.h:1084
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffffffff81713c79)
Location: include/linux/blkdev.h:1084
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d246d)
Location: include/linux/blkdev.h:1098
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffffffff8174e3fe)
Location: include/linux/blkdev.h:1098
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
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
In block/blk-merge.c (ffffffff814eb7ed)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffffffff817725ae)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
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
In block/blk-merge.c (ffffffff8154b540)
Location: include/linux/blkdev.h:1145
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffffffff81836db3)
Location: include/linux/blkdev.h:1145
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
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
In block/blk-merge.c (ffffffff815675f0)
Location: include/linux/blkdev.h:1199
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffffffff81847823)
Location: include/linux/blkdev.h:1199
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
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
In block/blk-merge.c (ffffffff8156f9dd)
Location: include/linux/blkdev.h:1184
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182a8a3)
Location: include/linux/blkdev.h:1184
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
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
In block/blk-merge.c (ffffffff815d407d)
Location: include/linux/blkdev.h:1158
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b6313)
Location: include/linux/blkdev.h:1158
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
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
In block/blk-merge.c (ffffffff8167fed1)
Location: include/linux/blk-mq.h:1094
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a01872)
Location: include/linux/blk-mq.h:1094
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
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
In block/blk-merge.c (ffffffff8173d271)
Location: include/linux/blk-mq.h:1125
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7fed2)
Location: include/linux/blk-mq.h:1125
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
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
In block/blk-merge.c (ffffffff81779811)
Location: include/linux/blk-mq.h:1125
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
```
In drivers/block/virtio_blk.c (ffffffff81b802ac)
Location: include/linux/blk-mq.h:1125
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:virtblk_complete_batch
  - drivers/block/virtio_blk.c:virtio_queue_rqs
  - drivers/block/virtio_blk.c:virtio_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd3f32)
Location: include/linux/blk-mq.h:1125
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
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
In block/blk-merge.c (ffffffff817bbbe1)
Location: include/linux/blk-mq.h:1122
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
```
In drivers/block/virtio_blk.c (ffffffff81bd40eb)
Location: include/linux/blk-mq.h:1122
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:virtblk_complete_batch
  - drivers/block/virtio_blk.c:virtio_queue_rqs
  - drivers/block/virtio_blk.c:virtio_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c28ba2)
Location: include/linux/blk-mq.h:1122
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
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
In block/blk-merge.c (ffff8000105ea204)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffff800010975af8)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
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
In block/blk-merge.c (c07967cc)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (c0a4a3a4)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
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
In block/blk-merge.c (c00000000077f09c)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (c000000000a2fd84)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffe00042a60e)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005de232)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
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
In block/blk-merge.c (ffffffff814e3dcd)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffffffff81726c9e)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
```
In drivers/nvme/host/pci.c (ffffffff8174e669)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_pci_complete_rq
  - drivers/nvme/host/pci.c:nvme_queue_rq
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_unmap_data
  - drivers/nvme/host/pci.c:nvme_unmap_data
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d46ad)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffffffff817000ce)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
```
In drivers/nvme/host/pci.c (ffffffff8172e509)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_pci_complete_rq
  - drivers/nvme/host/pci.c:nvme_queue_rq
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_unmap_data
  - drivers/nvme/host/pci.c:nvme_unmap_data
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814dfe5d)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffffffff81765a6e)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
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
In block/blk-merge.c (ffffffff814f8cbd)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In drivers/scsi/scsi_lib.c (ffffffff817810fe)
Location: include/linux/blkdev.h:1125
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
</details>
</li>
</ul>

## Differences

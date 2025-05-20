# Function: <code>virtio_find_vqs</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81554459)
Location: include/linux/virtio_config.h:185
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
```
```
In drivers/char/virtio_console.c (ffffffff815a96a7)
Location: include/linux/virtio_config.h:185
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
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
In drivers/virtio/virtio_balloon.c (ffffffff815b7ed9)
Location: include/linux/virtio_config.h:186
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
```
```
In drivers/char/virtio_console.c (ffffffff8160ffc7)
Location: include/linux/virtio_config.h:186
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
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
In drivers/virtio/virtio_balloon.c (ffffffff815f04bb)
Location: include/linux/virtio_config.h:186
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
```
```
In drivers/char/virtio_console.c (ffffffff8164c691)
Location: include/linux/virtio_config.h:186
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
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
In drivers/char/virtio_console.c (ffffffff8166a431)
Location: include/linux/virtio_config.h:192
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
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
In drivers/char/virtio_console.c (ffffffff816a0225)
Location: include/linux/virtio_config.h:192
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816c2fd5)
Location: include/linux/virtio_config.h:192
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff817769ca)
Location: include/linux/virtio_config.h:192
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
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
In drivers/char/virtio_console.c (ffffffff817916fa)
Location: include/linux/virtio_config.h:201
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
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
In drivers/char/virtio_console.c (ffffffff817736f8)
Location: include/linux/virtio_config.h:201
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
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
In drivers/virtio/virtio_balloon.c (ffffffff8178d4a3)
Location: include/linux/virtio_config.h:202
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
```
```
In drivers/char/virtio_console.c (ffffffff817f9538)
Location: include/linux/virtio_config.h:202
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8182f55d)
Location: include/linux/virtio_config.h:202
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
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
In drivers/virtio/virtio_balloon.c (ffffffff818c560c)
Location: include/linux/virtio_config.h:208
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
```
```
In drivers/char/virtio_console.c (ffffffff8193956a)
Location: include/linux/virtio_config.h:208
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8197073f)
Location: include/linux/virtio_config.h:208
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
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
In drivers/virtio/virtio_balloon.c (ffffffff81a15f0c)
Location: include/linux/virtio_config.h:222
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
```
```
In drivers/char/virtio_console.c (ffffffff81a996fa)
Location: include/linux/virtio_config.h:222
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81adb55f)
Location: include/linux/virtio_config.h:222
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
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
In drivers/virtio/virtio_balloon.c (ffffffff81a5efbc)
Location: include/linux/virtio_config.h:224
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
```
```
In drivers/char/virtio_console.c (ffffffff81ae4f6a)
Location: include/linux/virtio_config.h:224
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b2981f)
Location: include/linux/virtio_config.h:224
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/block/virtio_blk.c (ffffffff81b80810)
Location: include/linux/virtio_config.h:224
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:init_vq
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be304c)
Location: include/linux/virtio_config.h:224
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_init
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
In drivers/virtio/virtio_balloon.c (ffffffff81ab171c)
Location: include/linux/virtio_config.h:228
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
```
```
In drivers/char/virtio_console.c (ffffffff81b3833a)
Location: include/linux/virtio_config.h:228
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b8080f)
Location: include/linux/virtio_config.h:228
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/block/virtio_blk.c (ffffffff81bd4618)
Location: include/linux/virtio_config.h:228
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:init_vq
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c384b1)
Location: include/linux/virtio_config.h:228
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_init
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
In drivers/char/virtio_console.c (ffff8000108b2d8c)
Location: include/linux/virtio_config.h:192
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
```
```
In drivers/iommu/virtio-iommu.c (ffff8000108dbf18)
Location: include/linux/virtio_config.h:192
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c09affd8)
Location: include/linux/virtio_config.h:192
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c00000000094f968)
Location: include/linux/virtio_config.h:192
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
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
In drivers/char/virtio_console.c (ffffffe000566d94)
Location: include/linux/virtio_config.h:192
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81688a25)
Location: include/linux/virtio_config.h:192
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
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
In drivers/char/virtio_console.c (ffffffff816664d5)
Location: include/linux/virtio_config.h:192
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
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
In drivers/char/virtio_console.c (ffffffff816b6ca5)
Location: include/linux/virtio_config.h:192
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81772b8b)
Location: include/linux/virtio_config.h:192
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816d12b5)
Location: include/linux/virtio_config.h:192
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:init_vqs
```
</details>
</li>
</ul>

## Differences

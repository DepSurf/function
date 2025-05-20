# Function: <code>virtio_cread16</code>

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
In drivers/char/virtio_console.c (ffffffff81517490)
Location: include/linux/virtio_config.h:348
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
```
In drivers/block/virtio_blk.c (ffffffff81572251)
Location: include/linux/virtio_config.h:348
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:init_vq
  - drivers/block/virtio_blk.c:virtblk_probe
```
```
In drivers/net/virtio_net.c (ffffffff815f3c14)
Location: include/linux/virtio_config.h:348
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8156a1b0)
Location: include/linux/virtio_config.h:361
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
```
In drivers/block/virtio_blk.c (ffffffff815c8421)
Location: include/linux/virtio_config.h:361
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:init_vq
  - drivers/block/virtio_blk.c:virtblk_getgeo
```
```
In drivers/net/virtio_net.c (ffffffff81654191)
Location: include/linux/virtio_config.h:361
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_config_changed_work
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
In drivers/char/virtio_console.c (ffffffff815968f0)
Location: include/linux/virtio_config.h:361
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (ffffffff815aa656)
Location: include/linux/virtio_config.h:386
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (ffffffff81610fc6)
Location: include/linux/virtio_config.h:387
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (ffffffff8164aa60)
Location: include/linux/virtio_config.h:387
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (ffffffff81668d20)
Location: include/linux/virtio_config.h:393
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (ffffffff8169e67b)
Location: include/linux/virtio_config.h:399
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (ffffffff816c172b)
Location: include/linux/virtio_config.h:399
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (ffffffff81774fa5)
Location: include/linux/virtio_config.h:399
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff81c51729)
Location: include/linux/virtio_config.h:544
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_validate
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
In drivers/net/virtio_net.c (ffffffff81d079ba)
Location: include/linux/virtio_config.h:548
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_validate
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffff8000108b375c)
Location: include/linux/virtio_config.h:399
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (c09aee10)
Location: include/linux/virtio_config.h:399
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (c00000000094cc34)
Location: include/linux/virtio_config.h:399
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (ffffffe0005656ac)
Location: include/linux/virtio_config.h:399
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (ffffffff8168717b)
Location: include/linux/virtio_config.h:399
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (ffffffff81664d6b)
Location: include/linux/virtio_config.h:399
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/char/virtio_console.c (ffffffff816b54bb)
Location: include/linux/virtio_config.h:399
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81772eb2)
Location: include/linux/virtio_config.h:399
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
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
In drivers/char/virtio_console.c (ffffffff816cff56)
Location: include/linux/virtio_config.h:399
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
</details>
</li>
</ul>

## Differences

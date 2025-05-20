# Function: <code>virtio_cread32</code>

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
In drivers/virtio/virtio_balloon.c (ffffffff814c40a0)
Location: include/linux/virtio_config.h:363
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:balloon
```
```
In drivers/char/virtio_console.c (ffffffff81518bf8)
Location: include/linux/virtio_config.h:363
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/block/virtio_blk.c (ffffffff81572aaa)
Location: include/linux/virtio_config.h:363
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
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
In drivers/virtio/virtio_balloon.c (ffffffff81514b6f)
Location: include/linux/virtio_config.h:376
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
```
```
In drivers/char/virtio_console.c (ffffffff8156b910)
Location: include/linux/virtio_config.h:376
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/block/virtio_blk.c (ffffffff815c8284)
Location: include/linux/virtio_config.h:376
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81540fff)
Location: include/linux/virtio_config.h:376
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff8159807d)
Location: include/linux/virtio_config.h:376
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio_balloon.c (ffffffff81554e8f)
Location: include/linux/virtio_config.h:401
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff815abfa3)
Location: include/linux/virtio_config.h:401
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio_balloon.c (ffffffff815b83bf)
Location: include/linux/virtio_config.h:402
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff8161294f)
Location: include/linux/virtio_config.h:402
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio_balloon.c (ffffffff815f098f)
Location: include/linux/virtio_config.h:402
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff8164c9b6)
Location: include/linux/virtio_config.h:402
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio_balloon.c (ffffffff8160b66f)
Location: include/linux/virtio_config.h:408
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (ffffffff8166a886)
Location: include/linux/virtio_config.h:408
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio_balloon.c (ffffffff8163f55b)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (ffffffff816a06ab)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio_balloon.c (ffffffff8166197b)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (ffffffff816c3462)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio_balloon.c (ffffffff81710b9b)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
```
```
In drivers/char/virtio_console.c (ffffffff81776eae)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/net/virtio_net.c (ffffffff81c51fe9)
Location: include/linux/virtio_config.h:564
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
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
In drivers/net/virtio_net.c (ffffffff81d08217)
Location: include/linux/virtio_config.h:568
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
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
In drivers/virtio/virtio_balloon.c (ffff80001082abc8)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (ffff8000108b5868)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/iommu/virtio-iommu.c (ffff8000108dc298)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
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
In drivers/virtio/virtio_balloon.c (c0948b18)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (c09b04c4)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio_balloon.c (c0000000008d7e94)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (c00000000094ff94)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio_balloon.c (ffffffe000520b28)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (ffffffe000566fde)
Location: include/linux/virtio_config.h:417
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff816277eb)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (ffffffff81688eb2)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio_balloon.c (ffffffff8161be6b)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (ffffffff81666973)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio_balloon.c (ffffffff816557bb)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (ffffffff816b7149)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81772e6e)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
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
In drivers/virtio/virtio_balloon.c (ffffffff81670392)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (ffffffff816d1720)
Location: include/linux/virtio_config.h:417
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
</details>
</li>
</ul>

## Differences

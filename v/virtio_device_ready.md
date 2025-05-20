# Function: <code>virtio_device_ready</code>

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
In drivers/virtio/virtio.c (ffffffff814bf0bc)
Location: include/linux/virtio_config.h:174
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff814c3ddd)
Location: include/linux/virtio_config.h:174
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
```
```
In drivers/char/virtio_console.c (ffffffff81517ffd)
Location: include/linux/virtio_config.h:174
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/block/virtio_blk.c (ffffffff81572561)
Location: include/linux/virtio_config.h:174
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_restore
  - drivers/block/virtio_blk.c:virtblk_probe
```
```
In drivers/net/virtio_net.c (ffffffff815f41bb)
Location: include/linux/virtio_config.h:174
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_restore
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
In drivers/virtio/virtio.c (ffffffff8150edba)
Location: include/linux/virtio_config.h:187
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81514b47)
Location: include/linux/virtio_config.h:187
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff8156ad2b)
Location: include/linux/virtio_config.h:187
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/block/virtio_blk.c (ffffffff815c7d41)
Location: include/linux/virtio_config.h:187
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_restore
  - drivers/block/virtio_blk.c:virtblk_probe
```
```
In drivers/net/virtio_net.c (ffffffff81653de5)
Location: include/linux/virtio_config.h:187
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_probe
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
In drivers/virtio/virtio.c (ffffffff8153af1a)
Location: include/linux/virtio_config.h:187
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81540fd7)
Location: include/linux/virtio_config.h:187
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff8159749b)
Location: include/linux/virtio_config.h:187
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
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
In drivers/virtio/virtio.c (ffffffff8154e8e2)
Location: include/linux/virtio_config.h:212
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81554e67)
Location: include/linux/virtio_config.h:212
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff815ab4bb)
Location: include/linux/virtio_config.h:212
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
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
In drivers/virtio/virtio.c (ffffffff815b2059)
Location: include/linux/virtio_config.h:213
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815b838b)
Location: include/linux/virtio_config.h:213
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff81611e4b)
Location: include/linux/virtio_config.h:213
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
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
In drivers/virtio/virtio.c (ffffffff815ea4b3)
Location: include/linux/virtio_config.h:213
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815f095b)
Location: include/linux/virtio_config.h:213
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff8164cb5b)
Location: include/linux/virtio_config.h:213
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
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
In drivers/virtio/virtio.c (ffffffff816049c3)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160b63b)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff8166a58b)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio.c (ffffffff816372bb)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163f521)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff816a038b)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio.c (ffffffff8165901b)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81661941)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff816c313b)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio.c (ffffffff817099df)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710b61)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff81776b27)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio.c (ffffffff8172698f)
Location: include/linux/virtio_config.h:228
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d73b)
Location: include/linux/virtio_config.h:228
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff81791857)
Location: include/linux/virtio_config.h:228
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio.c (ffffffff8170a62f)
Location: include/linux/virtio_config.h:228
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8171116b)
Location: include/linux/virtio_config.h:228
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff81773dc7)
Location: include/linux/virtio_config.h:228
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio.c (ffffffff81786061)
Location: include/linux/virtio_config.h:229
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178d6eb)
Location: include/linux/virtio_config.h:229
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff817fa19b)
Location: include/linux/virtio_config.h:229
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8182f6ea)
Location: include/linux/virtio_config.h:229
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
In drivers/virtio/virtio.c (ffffffff818bcb7a)
Location: include/linux/virtio_config.h:254
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c5b17)
Location: include/linux/virtio_config.h:254
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff819396e7)
Location: include/linux/virtio_config.h:254
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/iommu/virtio-iommu.c (ffffffff819708e9)
Location: include/linux/virtio_config.h:254
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
In drivers/virtio/virtio.c (ffffffff81a0b89a)
Location: include/linux/virtio_config.h:268
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16217)
Location: include/linux/virtio_config.h:268
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff81a99887)
Location: include/linux/virtio_config.h:268
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81adb70c)
Location: include/linux/virtio_config.h:268
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
In drivers/virtio/virtio.c (ffffffff81a5472a)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5f2c7)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff81ae50f7)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b299cc)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/block/virtio_blk.c (ffffffff81b80a19)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_restore
  - drivers/block/virtio_blk.c:virtblk_probe
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be32b9)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_restore
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
```
```
In drivers/net/virtio_net.c (ffffffff81c5443d)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_probe
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
In drivers/virtio/virtio.c (ffffffff81aa53e5)
Location: include/linux/virtio_config.h:274
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab26d7)
Location: include/linux/virtio_config.h:274
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff81b384c7)
Location: include/linux/virtio_config.h:274
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b809bc)
Location: include/linux/virtio_config.h:274
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/block/virtio_blk.c (ffffffff81bd4849)
Location: include/linux/virtio_config.h:274
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_restore
  - drivers/block/virtio_blk.c:virtblk_probe
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c38719)
Location: include/linux/virtio_config.h:274
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_restore
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
```
```
In drivers/net/virtio_net.c (ffffffff81d0ab5b)
Location: include/linux/virtio_config.h:274
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_restore
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
In drivers/virtio/virtio.c (ffff800010821694)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082ab90)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffff8000108b51c4)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/iommu/virtio-iommu.c (ffff8000108dc088)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
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
In drivers/virtio/virtio.c (c093f334)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (c0948ae0)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (c09b0170)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio.c (c0000000008cb268)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d7e40)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (c00000000094fb40)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
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
In drivers/virtio/virtio.c (ffffffe000518454)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffe000520af8)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffe000566e58)
Location: include/linux/virtio_config.h:219
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
In drivers/virtio/virtio.c (ffffffff8161eebb)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816277b1)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff81688b8b)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio.c (ffffffff8161359b)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161be31)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff8166663b)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio.c (ffffffff8164ce5b)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81655781)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff816b6e0b)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81772dac)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_restore
  - drivers/scsi/virtio_scsi.c:virtscsi_restore
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
In drivers/virtio/virtio.c (ffffffff81667554)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8167035d)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff816d141b)
Location: include/linux/virtio_config.h:219
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
</details>
</li>
</ul>

## Differences

# Function: <code>virtio32_to_cpu</code>

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
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/virtio_config.h:225
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:225
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:225
Inline: True
```
```
In drivers/block/virtio_blk.c (0)
Location: include/linux/virtio_config.h:225
Inline: True
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
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/virtio_config.h:238
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:238
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:238
Inline: True
```
```
In drivers/block/virtio_blk.c (0)
Location: include/linux/virtio_config.h:238
Inline: True
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
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/virtio_config.h:238
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:238
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:238
Inline: True
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
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/virtio_config.h:263
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:263
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:263
Inline: True
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
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/virtio_config.h:264
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:264
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:264
Inline: True
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
In drivers/virtio/virtio_ring.c (ffffffff815eb3ef)
Location: include/linux/virtio_config.h:264
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:detach_buf
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815f09ac)
Location: include/linux/virtio_config.h:264
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff8164c9e0)
Location: include/linux/virtio_config.h:264
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
In drivers/virtio/virtio_ring.c (ffffffff8160599d)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160b68c)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (ffffffff8166a8b0)
Location: include/linux/virtio_config.h:270
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
In drivers/virtio/virtio_ring.c (ffffffff8163abb1)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163f580)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (ffffffff816a06d8)
Location: include/linux/virtio_config.h:270
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
In drivers/virtio/virtio_ring.c (ffffffff8165d071)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816619a0)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (ffffffff816c348f)
Location: include/linux/virtio_config.h:270
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
In drivers/virtio/virtio_ring.c (ffffffff8170a6d2)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710bbd)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
```
```
In drivers/char/virtio_console.c (ffffffff81776edb)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff81727542)
Location: include/linux/virtio_config.h:288
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d9d9)
Location: include/linux/virtio_config.h:288
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/char/virtio_console.c (ffffffff81791c03)
Location: include/linux/virtio_config.h:288
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff8170af82)
Location: include/linux/virtio_config.h:288
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81711ef9)
Location: include/linux/virtio_config.h:288
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/char/virtio_console.c (ffffffff817746f0)
Location: include/linux/virtio_config.h:288
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff81786e78)
Location: include/linux/virtio_config.h:289
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178e969)
Location: include/linux/virtio_config.h:289
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/char/virtio_console.c (ffffffff817faaf0)
Location: include/linux/virtio_config.h:289
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio_ring.c (ffffffff818bdea8)
Location: include/linux/virtio_config.h:336
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c68a9)
Location: include/linux/virtio_config.h:336
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/char/virtio_console.c (ffffffff81939aa2)
Location: include/linux/virtio_config.h:336
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio_ring.c (ffffffff81a0c9a8)
Location: include/linux/virtio_config.h:350
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a17219)
Location: include/linux/virtio_config.h:350
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/char/virtio_console.c (ffffffff81a99bdd)
Location: include/linux/virtio_config.h:350
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio_ring.c (ffffffff81a556a8)
Location: include/linux/virtio_config.h:352
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a602a9)
Location: include/linux/virtio_config.h:352
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/char/virtio_console.c (ffffffff81ae544d)
Location: include/linux/virtio_config.h:352
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/block/virtio_blk.c (ffffffff81b80ca3)
Location: include/linux/virtio_config.h:352
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be33e4)
Location: include/linux/virtio_config.h:352
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
```
```
In drivers/net/virtio_net.c (ffffffff81c52015)
Location: include/linux/virtio_config.h:352
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff81aa6718)
Location: include/linux/virtio_config.h:356
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab2ae9)
Location: include/linux/virtio_config.h:356
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/char/virtio_console.c (ffffffff81b38846)
Location: include/linux/virtio_config.h:356
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/block/virtio_blk.c (ffffffff81bd4b02)
Location: include/linux/virtio_config.h:356
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c38844)
Location: include/linux/virtio_config.h:356
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
```
```
In drivers/net/virtio_net.c (ffffffff81d08244)
Location: include/linux/virtio_config.h:356
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
In drivers/virtio/virtio_ring.c (ffff800010822ddc)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082abec)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (ffff8000108b588c)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/iommu/virtio-iommu.c (ffff8000108dc2bc)
Location: include/linux/virtio_config.h:270
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
In drivers/virtio/virtio_ring.c (c0940e28)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (c0948b3c)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (c09b04e8)
Location: include/linux/virtio_config.h:270
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
In drivers/virtio/virtio_ring.c (c0000000008d0bbc)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d7ec4)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (c00000000094ffc8)
Location: include/linux/virtio_config.h:270
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
In drivers/virtio/virtio_ring.c (ffffffe000519a94)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffe000520b46)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (ffffffe000566ffc)
Location: include/linux/virtio_config.h:270
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
In drivers/virtio/virtio_ring.c (ffffffff81622f11)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81627810)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (ffffffff81688edf)
Location: include/linux/virtio_config.h:270
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
In drivers/virtio/virtio_ring.c (ffffffff81617561)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161be90)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (ffffffff816669a0)
Location: include/linux/virtio_config.h:270
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
In drivers/virtio/virtio_ring.c (ffffffff81650eb1)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816557e0)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (ffffffff816b7176)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81772e9a)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
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
In drivers/virtio/virtio_ring.c (ffffffff8166b541)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816703af)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/char/virtio_console.c (ffffffff816d1748)
Location: include/linux/virtio_config.h:270
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
</details>
</li>
</ul>

## Differences

# Function: <code>blk_mq_free_tag_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c3aa0)
Location: block/blk-mq.c:2310
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_release_gendisk
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff813c3aa0-ffffffff813c3b00: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814075d0)
Location: block/blk-mq.c:2368
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff814075d0-ffffffff81407631: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81421c70)
Location: block/blk-mq.c:2420
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81421c70-ffffffff81421ce8: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814325b0)
Location: block/blk-mq.c:2566
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff814325b0-ffffffff81432609: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145e180)
Location: block/blk-mq.c:2733
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff8145e180-ffffffff8145e1d9: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81491ab0)
Location: block/blk-mq.c:2795
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81491ab0-ffffffff81491b09: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ab4f0)
Location: block/blk-mq.c:3076
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff814ab4f0-ffffffff814ab571: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d96e0)
Location: block/blk-mq.c:3109
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff814d96e0-ffffffff814d9761: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f2aa0)
Location: block/blk-mq.c:3129
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff814f2aa0-ffffffff814f2b21: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81552fc0)
Location: block/blk-mq.c:3349
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_sq_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_exit_cb
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81552fc0-ffffffff81553097: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156f610)
Location: block/blk-mq.c:3474
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_sq_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_exit_cb
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_init_blk_queue
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff8156f610-ffffffff8156f71d: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815774c0)
Location: block/blk-mq.c:3536
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_sq_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_exit_cb
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_init_blk_queue
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff815774c0-ffffffff815775cd: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815dc220)
Location: block/blk-mq.c:3584
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff815dc220-ffffffff815dc2e2: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8168a090)
Location: block/blk-mq.c:4335
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff8168a090-ffffffff8168a1a1: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81748630)
Location: block/blk-mq.c:4547
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_free_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81748630-ffffffff8174877b: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81784d40)
Location: block/blk-mq.c:4546
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_free_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81784d40-ffffffff81784e8d: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c7250)
Location: block/blk-mq.c:4573
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_free_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff817c7250-ffffffff817c739d: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f22b8)
Location: block/blk-mq.c:3129
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/mmc/core/queue.c:mmc_cleanup_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffff8000105f22b8-ffff8000105f235c: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079e3c0)
Location: block/blk-mq.c:3129
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/mtd/mtd_blkdevs.c:blktrans_dev_release
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/mmc/core/queue.c:mmc_cleanup_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
c079e3c0-c079e460: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000789460)
Location: block/blk-mq.c:3129
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
c000000000789460-c000000000789560: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe000430bd2)
Location: block/blk-mq.c:3129
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/mmc/core/queue.c:mmc_cleanup_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffffffe000430bd2-ffffffe000430c68: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814eb080)
Location: block/blk-mq.c:3129
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_pci_free_ctrl
  - drivers/nvme/host/pci.c:nvme_dev_remove_admin
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff814eb080-ffffffff814eb101: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814db5d0)
Location: block/blk-mq.c:3129
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_pci_free_ctrl
  - drivers/nvme/host/pci.c:nvme_dev_remove_admin
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff814db5d0-ffffffff814db651: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e7110)
Location: block/blk-mq.c:3129
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff814e7110-ffffffff814e7191: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815000b0)
Location: block/blk-mq.c:3129
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags
  - drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff815000b0-ffffffff81500131: blk_mq_free_tag_set (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

# Function: <code>put_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff813ca050)
Location: block/genhd.c:1326
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:blkdev_get
  - block/blk-cgroup.c:blkg_conf_finish
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/block/brd.c:brd_free
  - drivers/block/loop.c:loop_remove
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_release_gendisk
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff813ca050-ffffffff813ca06a: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8140e2c0)
Location: block/genhd.c:1355
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/blk-cgroup.c:blkg_conf_finish
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - drivers/block/brd.c:brd_free
  - drivers/block/loop.c:loop_remove
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff8140e2c0-ffffffff8140e2da: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81429650)
Location: block/genhd.c:1355
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/blk-cgroup.c:blkg_conf_finish
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81429650-ffffffff8142966a: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81437990)
Location: block/genhd.c:1378
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/blk-cgroup.c:blkg_conf_finish
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81437990-ffffffff814379ab: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81463c9e)
Location: block/genhd.c:1462
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/blk-cgroup.c:blkg_conf_finish
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814637a0-ffffffff814637bb: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81497869)
Location: block/genhd.c:1483
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814971b0-ffffffff814971ca: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b1789)
Location: block/genhd.c:1508
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814b10d0-ffffffff814b10ea: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814dfb25)
Location: block/genhd.c:1529
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814df2f0-ffffffff814df30a: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f8f55)
Location: block/genhd.c:1538
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814f8720-ffffffff814f873a: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8155aec7)
Location: block/genhd.c:1751
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_exit_cb
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81559230-ffffffff8155924d: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81575e80)
Location: block/genhd.c:1623
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_put
  - fs/block_dev.c:blkdev_get_no_open
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_exit_cb
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81575e80-ffffffff81575e9e: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8157d460)
Location: block/genhd.c:1327
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_put
  - fs/block_dev.c:blkdev_get_no_open
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_exit_cb
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff8157d460-ffffffff8157d47e: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815e3686)
Location: block/genhd.c:1358
Inline: True
Inline callers:
  - block/genhd.c:blk_cleanup_disk
Direct callers:
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:part_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff815e28b0-ffffffff815e28ce: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81692ac6)
Location: block/genhd.c:1424
Inline: True
Inline callers:
  - block/genhd.c:blk_cleanup_disk
  - block/genhd.c:blk_cleanup_disk
Direct callers:
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:part_release
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81692bc0-ffffffff81692bea: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81750f30)
Location: block/genhd.c:1450
Inline: True
Direct callers:
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:part_release
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_kobj_release
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81750f30-ffffffff81750f5a: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8178d500)
Location: block/genhd.c:1413
Inline: True
Direct callers:
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:part_release
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_kobj_release
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff8178d500-ffffffff8178d52d: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817cfd60)
Location: block/genhd.c:1426
Inline: True
Direct callers:
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:part_release
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_kobj_release
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff817cfd60-ffffffff817cfd8d: put_disk (STB_GLOBAL)
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
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105fa4d8)
Location: block/genhd.c:1538
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
  - drivers/mmc/core/block.c:mmc_blk_put
```
**Symbols:**

```
ffff8000105f9b10-ffff8000105f9b40: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a549c)
Location: block/genhd.c:1538
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev
  - drivers/mtd/mtd_blkdevs.c:blktrans_dev_release
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
  - drivers/mmc/core/block.c:mmc_blk_put
```
**Symbols:**

```
c07a4de0-c07a4e08: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (c000000000793518)
Location: block/genhd.c:1538
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
c000000000792750-c000000000792790: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe000436ab2)
Location: block/genhd.c:1538
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
  - drivers/mmc/core/block.c:mmc_blk_put
```
**Symbols:**

```
ffffffe0004362d4-ffffffe000436302: put_disk (STB_GLOBAL)
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
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f1535)
Location: block/genhd.c:1538
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_free_ns
  - drivers/nvme/host/multipath.c:nvme_mpath_remove_disk
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814f0d00-ffffffff814f0d1a: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e1a75)
Location: block/genhd.c:1538
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
Direct callers:
  - drivers/block/loop.c:loop_remove
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/pmem.c:pmem_release_disk
  - drivers/nvdimm/btt.c:nvdimm_namespace_detach_btt
  - drivers/nvdimm/blk.c:nd_blk_release_disk
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/nvme/host/core.c:nvme_free_ns
  - drivers/nvme/host/multipath.c:nvme_mpath_remove_disk
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814e1240-ffffffff814e125a: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814ed5c5)
Location: block/genhd.c:1538
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814ecd90-ffffffff814ecdaa: put_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void put_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815067d5)
Location: block/genhd.c:1538
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81505e00-ffffffff81505e1a: put_disk (STB_GLOBAL)
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

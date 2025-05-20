# Function: <code>set_capacity</code>

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
In block/genhd.c (ffffffff813cb8f4)
Location: include/linux/genhd.h:462
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffffffff813cdb49)
Location: include/linux/genhd.h:462
Inline: True
Inline callers:
  - block/partition-generic.c:invalidate_partitions
```
```
In drivers/lightnvm/core.c (ffffffff815433a7)
Location: include/linux/genhd.h:462
Inline: True
```
```
In drivers/block/brd.c (ffffffff8156d204)
Location: include/linux/genhd.h:462
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_alloc
```
```
In drivers/block/loop.c (ffffffff8156e02b)
Location: include/linux/genhd.h:462
Inline: True
Inline callers:
  - drivers/block/loop.c:figure_loop_size
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/block/virtio_blk.c (ffffffff81572129)
Location: include/linux/genhd.h:462
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_config_changed_work
  - drivers/block/virtio_blk.c:virtblk_probe
```
```
In drivers/block/xen-blkfront.c (ffffffff81573745)
Location: include/linux/genhd.h:462
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/block/xen-blkfront.c:blkback_changed
```
```
In drivers/scsi/sd.c (ffffffff815be221)
Location: include/linux/genhd.h:462
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (ffffffff815bfde1)
Location: include/linux/genhd.h:462
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_done
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/md/md.c (ffffffff8168f93a)
Location: include/linux/genhd.h:462
Inline: True
Inline callers:
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:do_md_stop
```
```
In drivers/md/dm.c (ffffffff816a43c5)
Location: include/linux/genhd.h:462
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In block/genhd.c (ffffffff8140fbb4)
Location: include/linux/genhd.h:451
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffffffff81411f79)
Location: include/linux/genhd.h:451
Inline: True
Inline callers:
  - block/partition-generic.c:invalidate_partitions
```
```
In drivers/block/brd.c (0)
Location: include/linux/genhd.h:451
Inline: True
```
```
In drivers/block/loop.c (ffffffff815c5948)
Location: include/linux/genhd.h:451
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:figure_loop_size
```
```
In drivers/block/virtio_blk.c (ffffffff815c8071)
Location: include/linux/genhd.h:451
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_config_changed_work
```
```
In drivers/block/xen-blkfront.c (ffffffff815cdab0)
Location: include/linux/genhd.h:451
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/scsi/sd.c (ffffffff81616b86)
Location: include/linux/genhd.h:451
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (ffffffff81618580)
Location: include/linux/genhd.h:451
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/md.c (ffffffff816f9df0)
Location: include/linux/genhd.h:451
Inline: True
Inline callers:
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:array_size_store
```
```
In drivers/md/dm.c (ffffffff81704575)
Location: include/linux/genhd.h:451
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In block/genhd.c (ffffffff8142af44)
Location: include/linux/genhd.h:442
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffffffff8142d3d3)
Location: include/linux/genhd.h:442
Inline: True
Inline callers:
  - block/partition-generic.c:invalidate_partitions
```
```
In drivers/block/loop.c (ffffffff815f3fbf)
Location: include/linux/genhd.h:442
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:figure_loop_size
```
```
In drivers/block/xen-blkfront.c (ffffffff815fa38f)
Location: include/linux/genhd.h:442
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/scsi/sd.c (ffffffff8164661e)
Location: include/linux/genhd.h:442
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (ffffffff81649200)
Location: include/linux/genhd.h:442
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/md.c (ffffffff8172b665)
Location: include/linux/genhd.h:442
Inline: True
Inline callers:
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:array_size_store
```
```
In drivers/md/dm.c (ffffffff81736453)
Location: include/linux/genhd.h:442
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In block/genhd.c (ffffffff8143915b)
Location: include/linux/genhd.h:436
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffffffff8143a6c3)
Location: include/linux/genhd.h:436
Inline: True
Inline callers:
  - block/partition-generic.c:invalidate_partitions
```
```
In drivers/lightnvm/core.c (ffffffff815d8d61)
Location: include/linux/genhd.h:436
Inline: True
```
```
In drivers/block/loop.c (ffffffff816084ba)
Location: include/linux/genhd.h:436
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:figure_loop_size
```
```
In drivers/block/xen-blkfront.c (ffffffff8160e77f)
Location: include/linux/genhd.h:436
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/scsi/sd.c (ffffffff8165b14f)
Location: include/linux/genhd.h:436
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (ffffffff8165db28)
Location: include/linux/genhd.h:436
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/md.c (ffffffff81739a9e)
Location: include/linux/genhd.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
```
```
In drivers/md/dm.c (ffffffff8174f82d)
Location: include/linux/genhd.h:436
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In block/genhd.c (ffffffff81465137)
Location: include/linux/genhd.h:428
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffffffff814666e3)
Location: include/linux/genhd.h:428
Inline: True
Inline callers:
  - block/partition-generic.c:invalidate_partitions
```
```
In drivers/lightnvm/core.c (ffffffff8163fafb)
Location: include/linux/genhd.h:428
Inline: True
```
```
In drivers/block/loop.c (ffffffff81671075)
Location: include/linux/genhd.h:428
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:figure_loop_size
```
```
In drivers/block/xen-blkfront.c (ffffffff81676fff)
Location: include/linux/genhd.h:428
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/scsi/sd.c (ffffffff816c4820)
Location: include/linux/genhd.h:428
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (ffffffff816c7108)
Location: include/linux/genhd.h:428
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/md.c (ffffffff817ac246)
Location: include/linux/genhd.h:428
Inline: True
Inline callers:
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
```
```
In drivers/md/dm.c (ffffffff817c1a36)
Location: include/linux/genhd.h:428
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In block/genhd.c (ffffffff81498a82)
Location: include/linux/genhd.h:436
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffffffff81499efd)
Location: include/linux/genhd.h:436
Inline: True
Inline callers:
  - block/partition-generic.c:invalidate_partitions
```
```
In drivers/lightnvm/core.c (ffffffff8167b29d)
Location: include/linux/genhd.h:436
Inline: True
```
```
In drivers/block/loop.c (ffffffff816ac5f9)
Location: include/linux/genhd.h:436
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:figure_loop_size
```
```
In drivers/block/xen-blkfront.c (ffffffff816b337c)
Location: include/linux/genhd.h:436
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/scsi/sd.c (ffffffff81700d4a)
Location: include/linux/genhd.h:436
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (ffffffff81704a20)
Location: include/linux/genhd.h:436
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/md.c (ffffffff817f8d43)
Location: include/linux/genhd.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
```
```
In drivers/md/dm.c (ffffffff8180a148)
Location: include/linux/genhd.h:436
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In block/genhd.c (ffffffff814b2bd2)
Location: include/linux/genhd.h:459
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffffffff814b420d)
Location: include/linux/genhd.h:459
Inline: True
Inline callers:
  - block/partition-generic.c:invalidate_partitions
```
```
In drivers/lightnvm/core.c (ffffffff8169ac15)
Location: include/linux/genhd.h:459
Inline: True
```
```
In drivers/block/loop.c (ffffffff816ce209)
Location: include/linux/genhd.h:459
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:figure_loop_size
```
```
In drivers/block/xen-blkfront.c (ffffffff816d45de)
Location: include/linux/genhd.h:459
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/scsi/sd.c (ffffffff81723b6f)
Location: include/linux/genhd.h:459
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (ffffffff81726e97)
Location: include/linux/genhd.h:459
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/md.c (ffffffff81824da1)
Location: include/linux/genhd.h:459
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
```
```
In drivers/md/dm.c (ffffffff81836148)
Location: include/linux/genhd.h:459
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In block/genhd.c (ffffffff814e1094)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffffffff814e26f2)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/partition-generic.c:invalidate_partitions
```
```
In drivers/lightnvm/core.c (ffffffff816d33e6)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (ffffffff8170705d)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
```
In drivers/block/xen-blkfront.c (ffffffff8170fe19)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/scsi/sd.c (ffffffff8175f043)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (ffffffff8176259e)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/md.c (ffffffff81867215)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
```
```
In drivers/md/dm.c (ffffffff81878d74)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In block/genhd.c (ffffffff814fa4c4)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffffffff814fbab2)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/partition-generic.c:invalidate_partitions
```
```
In drivers/lightnvm/core.c (ffffffff816f72c7)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (ffffffff8172b2ad)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
```
In drivers/block/xen-blkfront.c (ffffffff81734103)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/scsi/sd.c (ffffffff81782f2c)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (ffffffff8178658e)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/md.c (ffffffff81898fa5)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
```
In drivers/md/dm.c (ffffffff818aabb4)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In fs/block_dev.c (ffffffff813601ea)
Location: include/linux/genhd.h:335
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/genhd.c (ffffffff8155b458)
Location: include/linux/genhd.h:335
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In drivers/lightnvm/core.c (ffffffff817b00ff)
Location: include/linux/genhd.h:335
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (ffffffff817e7236)
Location: include/linux/genhd.h:335
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
```
```
In drivers/block/xen-blkfront.c (ffffffff817efa2d)
Location: include/linux/genhd.h:335
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/scsi/sr.c (ffffffff8184a144)
Location: include/linux/genhd.h:335
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/md.c (ffffffff819682dd)
Location: include/linux/genhd.h:335
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
```
In drivers/md/dm.c (ffffffff81977278)
Location: include/linux/genhd.h:335
Inline: True
Inline callers:
  - drivers/md/dm.c:__bind
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void set_capacity(struct gendisk *disk, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815776ea)
Location: block/genhd.c:45
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_done
  - drivers/md/dm.c:__bind
```
**Symbols:**

```
ffffffff815750d0-ffffffff81575112: set_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_capacity(struct gendisk *disk, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8157f45a)
Location: block/genhd.c:43
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_done
  - drivers/md/dm.c:__bind
```
**Symbols:**

```
ffffffff8157e780-ffffffff8157e7c1: set_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void set_capacity(struct gendisk *disk, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815e44e5)
Location: block/genhd.c:55
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_done
  - drivers/md/dm.c:__bind
```
**Symbols:**

```
ffffffff815e3fc0-ffffffff815e4001: set_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void set_capacity(struct gendisk *disk, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81692c5e)
Location: block/genhd.c:58
Inline: True
Inline callers:
  - block/genhd.c:invalidate_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_done
  - drivers/md/dm.c:__bind
```
**Symbols:**

```
ffffffff816913a0-ffffffff816913f5: set_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void set_capacity(struct gendisk *disk, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817519ae)
Location: block/genhd.c:58
Inline: True
Inline callers:
  - block/genhd.c:invalidate_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_done
  - drivers/md/dm.c:__bind
```
**Symbols:**

```
ffffffff8174ffe0-ffffffff81750035: set_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void set_capacity(struct gendisk *disk, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8178cc20)
Location: block/genhd.c:59
Inline: True
Inline callers:
  - block/genhd.c:invalidate_disk
  - block/genhd.c:blk_mark_disk_dead
  - block/genhd.c:set_capacity_and_notify
Direct callers:
  - block/partitions/core.c:bdev_disk_changed
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_done
  - drivers/md/dm.c:__bind
```
**Symbols:**

```
ffffffff8178c2f0-ffffffff8178c30c: set_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void set_capacity(struct gendisk *disk, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817cf450)
Location: block/genhd.c:59
Inline: True
Inline callers:
  - block/genhd.c:invalidate_disk
  - block/genhd.c:__blk_mark_disk_dead
  - block/genhd.c:set_capacity_and_notify
Direct callers:
  - block/partitions/core.c:bdev_disk_changed
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_done
  - drivers/md/dm.c:__bind
```
**Symbols:**

```
ffffffff817cea90-ffffffff817ceaac: set_capacity (STB_GLOBAL)
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
In block/genhd.c (ffff8000105fc08c)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffff8000105fdb9c)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/partition-generic.c:invalidate_partitions
```
```
In drivers/lightnvm/core.c (ffff8000108e11a8)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (ffff800010923704)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
```
In drivers/block/xen-blkfront.c (ffff800010929e88)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/scsi/sd.c (ffff800010989b10)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (ffff80001098cce4)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/md.c (ffff800010aecea8)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
```
In drivers/md/dm.c (ffff800010b00cdc)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
```
In drivers/mmc/core/block.c (ffff800010b3fa08)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
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
In block/genhd.c (c07a70e0)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (c07a8af8)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/partition-generic.c:invalidate_partitions
```
```
In drivers/lightnvm/core.c (c09cfc90)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (c0a06640)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
```
In drivers/scsi/sd.c (c0a5bd00)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (c0a5f2c4)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/mtd/mtd_blkdevs.c (c0a9807c)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev
```
```
In drivers/md/md.c (c0bca488)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
```
In drivers/md/dm.c (c0be05c8)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
```
In drivers/mmc/core/block.c (c0c1a19c)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
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
In block/genhd.c (c000000000795510)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (c0000000007975d4)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/partition-generic.c:invalidate_partitions
```
```
In drivers/lightnvm/core.c (c000000000974f70)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (c0000000009c6218)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
```
In drivers/scsi/sd.c (c000000000a49f20)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (c000000000a4e374)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/md.c (c000000000bd2cbc)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
```
In drivers/md/dm.c (c000000000befed4)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In block/genhd.c (ffffffe000438066)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffffffe00043960a)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/partition-generic.c:invalidate_partitions
```
```
In drivers/lightnvm/core.c (ffffffe00057694e)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (ffffffe00059fcc6)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
```
In drivers/scsi/sd.c (ffffffe0005ede4a)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (ffffffe0005f1786)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/md.c (ffffffe0006e10ae)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
```
In drivers/md/dm.c (ffffffe0006f0e56)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
```
In drivers/mmc/core/block.c (ffffffe000717886)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
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
In block/genhd.c (ffffffff814f2aa4)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffffffff814f4092)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/partition-generic.c:invalidate_partitions
```
```
In drivers/lightnvm/core.c (ffffffff816bcab7)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (ffffffff816f108d)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
```
In drivers/block/xen-blkfront.c (ffffffff816fa197)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/scsi/sd.c (ffffffff8173761c)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (ffffffff8173ac7e)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/nvme/host/core.c (ffffffff817453a1)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_revalidate_disk
  - drivers/nvme/host/core.c:nvme_update_disk_info
```
```
In drivers/md/md.c (ffffffff8183ee25)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
```
In drivers/md/dm.c (ffffffff81850a34)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In block/genhd.c (ffffffff814e2fd4)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffffffff814e45a2)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/partition-generic.c:invalidate_partitions
```
```
In drivers/block/loop.c (ffffffff816cb197)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
```
In drivers/nvdimm/pmem.c (ffffffff816eb180)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_attach_disk
```
```
In drivers/nvdimm/btt.c (ffffffff816ee7b0)
Location: include/linux/genhd.h:466
Inline: True
```
```
In drivers/nvdimm/blk.c (ffffffff816ef006)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/nvdimm/blk.c:nd_blk_probe
```
```
In drivers/scsi/sd.c (ffffffff817192bc)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (ffffffff8171c91e)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/nvme/host/core.c (ffffffff81727031)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_revalidate_disk
  - drivers/nvme/host/core.c:nvme_update_disk_info
```
```
In drivers/md/md.c (ffffffff81806485)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
```
In drivers/md/dm.c (ffffffff81818044)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In block/genhd.c (ffffffff814eeb34)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffffffff814f0122)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/partition-generic.c:invalidate_partitions
```
```
In drivers/lightnvm/core.c (ffffffff816eaf87)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (ffffffff8171e76d)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
```
In drivers/block/xen-blkfront.c (ffffffff817275c3)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/scsi/sd.c (ffffffff81777dac)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (ffffffff8177b40e)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/md.c (ffffffff8188e455)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
```
In drivers/md/dm.c (ffffffff818a0064)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In block/genhd.c (ffffffff81507bde)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partition-generic.c (ffffffff815091b2)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - block/partition-generic.c:invalidate_partitions
```
```
In drivers/lightnvm/core.c (ffffffff817057c7)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (ffffffff81739ba4)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
```
```
In drivers/block/xen-blkfront.c (ffffffff81742a10)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/scsi/sd.c (ffffffff81791bcc)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (ffffffff81794f7c)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/md.c (ffffffff818a766a)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
```
```
In drivers/md/dm.c (ffffffff818bc2d6)
Location: include/linux/genhd.h:466
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

# Function: <code>queue_flag_set_unlocked</code>

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
In block/blk-core.c (ffffffff813b5d0f)
Location: include/linux/blkdev.h:508
Inline: True
```
```
In block/blk-tag.c (ffffffff813bc30d)
Location: include/linux/blkdev.h:508
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
```
```
In block/blk-sysfs.c (ffffffff813bd312)
Location: include/linux/blkdev.h:508
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_register_queue
```
```
In block/bsg-lib.c (ffffffff813d6c3c)
Location: include/linux/blkdev.h:508
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_setup_queue
```
```
In drivers/block/brd.c (ffffffff8156d18c)
Location: include/linux/blkdev.h:508
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_alloc
```
```
In drivers/block/loop.c (ffffffff8156e4d4)
Location: include/linux/blkdev.h:508
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_add
```
```
In drivers/block/xen-blkfront.c (ffffffff8157386c)
Location: include/linux/blkdev.h:508
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/scsi/sd.c (ffffffff815ba1bf)
Location: include/linux/blkdev.h:508
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/md/dm-table.c (ffffffff816a6cc0)
Location: include/linux/blkdev.h:508
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
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
In block/blk-tag.c (ffffffff8140010d)
Location: include/linux/blkdev.h:525
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
```
```
In block/blk-sysfs.c (ffffffff81401240)
Location: include/linux/blkdev.h:525
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_register_queue
```
```
In block/bsg-lib.c (ffffffff8141c92c)
Location: include/linux/blkdev.h:525
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_setup_queue
```
```
In drivers/block/brd.c (ffffffff815c29a5)
Location: include/linux/blkdev.h:525
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_alloc
  - drivers/block/brd.c:brd_alloc
```
```
In drivers/block/loop.c (ffffffff815c4ee8)
Location: include/linux/blkdev.h:525
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
```
```
In drivers/block/xen-blkfront.c (ffffffff815ca102)
Location: include/linux/blkdev.h:525
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
```
```
In drivers/scsi/sd.c (ffffffff816170a1)
Location: include/linux/blkdev.h:525
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
```
```
In drivers/md/dm.c (ffffffff81704167)
Location: include/linux/blkdev.h:525
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
```
In drivers/md/dm-table.c (ffffffff817070e9)
Location: include/linux/blkdev.h:525
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
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
In block/blk-tag.c (ffffffff814199ad)
Location: include/linux/blkdev.h:620
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
```
```
In block/blk-sysfs.c (ffffffff8141ae6e)
Location: include/linux/blkdev.h:620
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_register_queue
```
```
In block/bsg-lib.c (ffffffff81437eac)
Location: include/linux/blkdev.h:620
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_setup_queue
```
```
In drivers/block/loop.c (ffffffff815f3618)
Location: include/linux/blkdev.h:620
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
```
```
In drivers/block/xen-blkfront.c (ffffffff815f6d62)
Location: include/linux/blkdev.h:620
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
```
```
In drivers/scsi/sd.c (ffffffff816474f4)
Location: include/linux/blkdev.h:620
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
```
```
In drivers/md/md.c (ffffffff8172a66b)
Location: include/linux/blkdev.h:620
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm.c (ffffffff81736037)
Location: include/linux/blkdev.h:620
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
```
In drivers/md/dm-table.c (ffffffff81738fc4)
Location: include/linux/blkdev.h:620
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
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
In block/blk-tag.c (ffffffff814278de)
Location: include/linux/blkdev.h:659
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
```
```
In block/blk-sysfs.c (ffffffff81428d4f)
Location: include/linux/blkdev.h:659
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
```
```
In block/bsg-lib.c (ffffffff814456ac)
Location: include/linux/blkdev.h:659
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_setup_queue
  - block/bsg-lib.c:bsg_setup_queue
```
```
In drivers/block/loop.c (ffffffff81607994)
Location: include/linux/blkdev.h:659
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
```
```
In drivers/block/xen-blkfront.c (ffffffff8160affe)
Location: include/linux/blkdev.h:659
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
```
```
In drivers/scsi/scsi_lib.c (ffffffff81649cbb)
Location: include/linux/blkdev.h:659
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
```
In drivers/scsi/sd.c (ffffffff8165b5df)
Location: include/linux/blkdev.h:659
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
```
```
In drivers/md/md.c (ffffffff817432fc)
Location: include/linux/blkdev.h:659
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm.c (ffffffff8174f4d7)
Location: include/linux/blkdev.h:659
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
```
In drivers/md/dm-table.c (ffffffff81752799)
Location: include/linux/blkdev.h:659
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
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
In block/blk-tag.c (ffffffff814528de)
Location: include/linux/blkdev.h:676
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
```
```
In block/blk-sysfs.c (ffffffff81453e1f)
Location: include/linux/blkdev.h:676
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
```
```
In block/bsg-lib.c (ffffffff81472189)
Location: include/linux/blkdev.h:676
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_setup_queue
  - block/bsg-lib.c:bsg_setup_queue
```
```
In drivers/block/loop.c (ffffffff81670042)
Location: include/linux/blkdev.h:676
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/block/xen-blkfront.c (ffffffff816738ce)
Location: include/linux/blkdev.h:676
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b2e0b)
Location: include/linux/blkdev.h:676
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
```
In drivers/scsi/sd.c (ffffffff816c4c59)
Location: include/linux/blkdev.h:676
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
```
```
In drivers/md/md.c (ffffffff817b543a)
Location: include/linux/blkdev.h:676
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm.c (ffffffff817c1705)
Location: include/linux/blkdev.h:676
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
```
In drivers/md/dm-table.c (ffffffff817c4724)
Location: include/linux/blkdev.h:676
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
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
In block/blk-core.c (ffffffff8147facd)
Location: block/blk.h:57
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue_node
```
```
In block/blk-tag.c (ffffffff81485cb6)
Location: block/blk.h:57
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
```
```
In block/blk-sysfs.c (ffffffff81486d9f)
Location: block/blk.h:57
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
```
```
In block/blk-mq.c (ffffffff81492227)
Location: block/blk.h:57
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences

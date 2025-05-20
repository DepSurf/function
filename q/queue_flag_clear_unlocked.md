# Function: <code>queue_flag_clear_unlocked</code>

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
In block/blk-tag.c (ffffffff813bbd29)
Location: include/linux/blkdev.h:546
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_free_tags
  - block/blk-tag.c:__blk_queue_free_tags
```
```
In drivers/block/loop.c (ffffffff8156e324)
Location: include/linux/blkdev.h:546
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
```
```
In drivers/scsi/sd.c (ffffffff815ba194)
Location: include/linux/blkdev.h:546
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/md/dm.c (ffffffff816a3475)
Location: include/linux/blkdev.h:546
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_setup_md_queue
```
```
In drivers/md/dm-table.c (ffffffff816a6c36)
Location: include/linux/blkdev.h:546
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
In block/blk-tag.c (ffffffff813ffb39)
Location: include/linux/blkdev.h:563
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_free_tags
  - block/blk-tag.c:__blk_queue_free_tags
```
```
In drivers/block/loop.c (ffffffff815c3c22)
Location: include/linux/blkdev.h:563
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
```
```
In drivers/scsi/sd.c (ffffffff816170b7)
Location: include/linux/blkdev.h:563
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
```
```
In drivers/md/dm.c (ffffffff81703d1b)
Location: include/linux/blkdev.h:563
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_init_normal_md_queue
```
```
In drivers/md/dm-table.c (ffffffff81706eb7)
Location: include/linux/blkdev.h:563
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
```
In drivers/md/dm-rq.c (ffffffff8170fbb9)
Location: include/linux/blkdev.h:563
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_start_queue
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
In block/blk-tag.c (ffffffff814193e9)
Location: include/linux/blkdev.h:658
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_free_tags
  - block/blk-tag.c:__blk_queue_free_tags
```
```
In drivers/block/loop.c (ffffffff815f2360)
Location: include/linux/blkdev.h:658
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
```
```
In drivers/scsi/sd.c (ffffffff816474fe)
Location: include/linux/blkdev.h:658
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
```
```
In drivers/md/md.c (ffffffff8172a989)
Location: include/linux/blkdev.h:658
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm.c (ffffffff81735be0)
Location: include/linux/blkdev.h:658
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_init_normal_md_queue
```
```
In drivers/md/dm-table.c (ffffffff81738d92)
Location: include/linux/blkdev.h:658
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
In block/blk-tag.c (ffffffff81427319)
Location: include/linux/blkdev.h:697
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_free_tags
  - block/blk-tag.c:__blk_queue_free_tags
```
```
In block/blk-sysfs.c (ffffffff81428f11)
Location: include/linux/blkdev.h:697
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_unregister_queue
```
```
In drivers/block/loop.c (ffffffff81606545)
Location: include/linux/blkdev.h:697
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
```
```
In drivers/scsi/sd.c (ffffffff8165b5e8)
Location: include/linux/blkdev.h:697
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
```
```
In drivers/md/md.c (ffffffff81743040)
Location: include/linux/blkdev.h:697
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm.c (ffffffff8174f44d)
Location: include/linux/blkdev.h:697
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-table.c (ffffffff81752517)
Location: include/linux/blkdev.h:697
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
In block/blk-tag.c (ffffffff814523d9)
Location: include/linux/blkdev.h:714
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_free_tags
  - block/blk-tag.c:__blk_queue_free_tags
```
```
In block/blk-sysfs.c (ffffffff81453ff0)
Location: include/linux/blkdev.h:714
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_unregister_queue
```
```
In drivers/block/loop.c (ffffffff8166e968)
Location: include/linux/blkdev.h:714
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/scsi/sd.c (ffffffff816c4c62)
Location: include/linux/blkdev.h:714
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
```
```
In drivers/md/md.c (ffffffff817b5179)
Location: include/linux/blkdev.h:714
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm-table.c (ffffffff817c4844)
Location: include/linux/blkdev.h:714
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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-tag.c (ffffffff81485865)
Location: block/blk.h:66
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_free_tags
  - block/blk-tag.c:__blk_queue_free_tags
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

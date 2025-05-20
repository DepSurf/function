# Function: <code>bdev_is_partition</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811cdbec)
Location: include/linux/blkdev.h:1376
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In fs/block_dev.c (ffffffff8136dc4c)
Location: include/linux/blkdev.h:1376
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
```
```
In block/blk-lib.c (ffffffff81569dd4)
Location: include/linux/blkdev.h:1376
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff81574b2e)
Location: include/linux/blkdev.h:1376
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/scsi_ioctl.c (ffffffff81581cca)
Location: include/linux/blkdev.h:1376
Inline: True
```
```
In block/blk-cgroup.c (ffffffff815865b6)
Location: include/linux/blkdev.h:1376
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_conf_open_bdev
```
```
In drivers/md/dm-table.c (ffffffff8197fda9)
Location: include/linux/blkdev.h:1376
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_is_rq_stackable
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
In kernel/trace/blktrace.c (ffffffff811cf28c)
Location: include/linux/blkdev.h:1361
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In fs/block_dev.c (ffffffff813745ec)
Location: include/linux/blkdev.h:1361
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bdev_free_inode
```
```
In block/blk-lib.c (ffffffff81571d41)
Location: include/linux/blkdev.h:1361
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff8157cba4)
Location: include/linux/blkdev.h:1361
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/genhd.c (ffffffff8157e44d)
Location: include/linux/blkdev.h:1361
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:disk_uevent
```
```
In block/scsi_ioctl.c (ffffffff81588bba)
Location: include/linux/blkdev.h:1361
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8158d2c7)
Location: include/linux/blkdev.h:1361
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_conf_open_bdev
```
```
In drivers/md/dm-table.c (ffffffff81963f29)
Location: include/linux/blkdev.h:1361
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_is_rq_stackable
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
In kernel/trace/blktrace.c (ffffffff811fb8ec)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In block/bdev.c (ffffffff815c4651)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:bdev_free_inode
```
```
In block/blk-settings.c (ffffffff815d1aea)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_set_zoned
```
```
In block/blk-lib.c (ffffffff815d6451)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff815e2185)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/genhd.c (ffffffff815e3374)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:disk_uevent
```
```
In block/blk-cgroup.c (ffffffff815f2d27)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_conf_open_bdev
```
```
In drivers/scsi/sd.c (ffffffff818c2394)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_ioctl
```
```
In drivers/scsi/sr.c (ffffffff818ca10d)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_ioctl
```
```
In drivers/md/dm-table.c (ffffffff81a0bed9)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_is_rq_stackable
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
In kernel/trace/blktrace.c (ffffffff81235be7)
Location: include/linux/blkdev.h:1142
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In block/bdev.c (ffffffff8166ed63)
Location: include/linux/blkdev.h:1142
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:bdev_free_inode
```
```
In block/blk-settings.c (ffffffff8167d3c3)
Location: include/linux/blkdev.h:1142
Inline: True
Inline callers:
  - block/blk-settings.c:bdev_discard_alignment
  - block/blk-settings.c:bdev_alignment_offset
  - block/blk-settings.c:blk_queue_set_zoned
```
```
In block/blk-lib.c (ffffffff81681c54)
Location: include/linux/blkdev.h:1142
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff81690612)
Location: include/linux/blkdev.h:1142
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/genhd.c (ffffffff816925a5)
Location: include/linux/blkdev.h:1142
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:disk_uevent
```
```
In block/blk-cgroup.c (ffffffff816a4069)
Location: include/linux/blkdev.h:1142
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_conf_open_bdev
```
```
In drivers/scsi/sd.c (ffffffff81a0eef1)
Location: include/linux/blkdev.h:1142
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_ioctl
```
```
In drivers/scsi/sr.c (ffffffff81a174d8)
Location: include/linux/blkdev.h:1142
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_ioctl
```
```
In drivers/md/dm-table.c (ffffffff81b744c9)
Location: include/linux/blkdev.h:1142
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_is_rq_stackable
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
In kernel/trace/blktrace.c (ffffffff81282627)
Location: include/linux/blkdev.h:1090
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In block/bdev.c (ffffffff8172a036)
Location: include/linux/blkdev.h:1090
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:bdev_free_inode
```
```
In block/blk-settings.c (ffffffff81739e83)
Location: include/linux/blkdev.h:1090
Inline: True
Inline callers:
  - block/blk-settings.c:bdev_discard_alignment
  - block/blk-settings.c:bdev_alignment_offset
  - block/blk-settings.c:disk_set_zoned
```
```
In block/blk-lib.c (ffffffff8173f285)
Location: include/linux/blkdev.h:1090
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff8174f1ed)
Location: include/linux/blkdev.h:1090
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/genhd.c (ffffffff817518a5)
Location: include/linux/blkdev.h:1090
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:disk_uevent
```
```
In block/blk-cgroup.c (ffffffff81762de9)
Location: include/linux/blkdev.h:1090
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_conf_open_bdev
```
```
In drivers/scsi/sd.c (ffffffff81b8ee61)
Location: include/linux/blkdev.h:1090
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_ioctl
```
```
In drivers/scsi/sr.c (ffffffff81b98418)
Location: include/linux/blkdev.h:1090
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_ioctl
```
```
In drivers/md/dm-table.c (ffffffff81d11379)
Location: include/linux/blkdev.h:1090
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_is_rq_stackable
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
In kernel/trace/blktrace.c (ffffffff8129f2c7)
Location: include/linux/blkdev.h:1070
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In block/bdev.c (ffffffff817663f7)
Location: include/linux/blkdev.h:1070
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:bdev_free_inode
```
```
In block/blk-settings.c (ffffffff8177655d)
Location: include/linux/blkdev.h:1070
Inline: True
Inline callers:
  - block/blk-settings.c:bdev_discard_alignment
  - block/blk-settings.c:bdev_alignment_offset
  - block/blk-settings.c:disk_set_zoned
```
```
In block/blk-lib.c (ffffffff8177b7ec)
Location: include/linux/blkdev.h:1070
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff8178b699)
Location: include/linux/blkdev.h:1070
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_pr_preempt
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/genhd.c (ffffffff8178de25)
Location: include/linux/blkdev.h:1070
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:disk_uevent
```
```
In block/early-lookup.c (ffffffff836fe4ca)
Location: include/linux/blkdev.h:1070
Inline: True
Inline callers:
  - block/early-lookup.c:printk_all_partitions
  - block/early-lookup.c:printk_all_partitions
```
```
In block/blk-cgroup.c (ffffffff817a22d4)
Location: include/linux/blkdev.h:1070
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_open_bdev
```
```
In drivers/scsi/sd.c (ffffffff81be4fac)
Location: include/linux/blkdev.h:1070
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_ioctl
```
```
In drivers/scsi/sr.c (ffffffff81bee9b3)
Location: include/linux/blkdev.h:1070
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_ioctl
```
```
In drivers/md/dm-table.c (ffffffff81d7a809)
Location: include/linux/blkdev.h:1070
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_is_rq_stackable
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
In kernel/trace/blktrace.c (ffffffff812ba9d6)
Location: include/linux/blkdev.h:1048
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In block/bdev.c (ffffffff817a7ef4)
Location: include/linux/blkdev.h:1048
Inline: True
Inline callers:
  - block/bdev.c:bdev_release
  - block/bdev.c:bdev_open_by_dev
  - block/bdev.c:bdev_free_inode
```
```
In block/blk-settings.c (ffffffff817b888d)
Location: include/linux/blkdev.h:1048
Inline: True
Inline callers:
  - block/blk-settings.c:bdev_discard_alignment
  - block/blk-settings.c:bdev_alignment_offset
```
```
In block/blk-lib.c (ffffffff817bdbdc)
Location: include/linux/blkdev.h:1048
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff817cddf9)
Location: include/linux/blkdev.h:1048
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_pr_preempt
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/genhd.c (ffffffff817d0685)
Location: include/linux/blkdev.h:1048
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:disk_uevent
```
```
In block/early-lookup.c (ffffffff83931baa)
Location: include/linux/blkdev.h:1048
Inline: True
Inline callers:
  - block/early-lookup.c:printk_all_partitions
  - block/early-lookup.c:printk_all_partitions
```
```
In block/blk-cgroup.c (ffffffff817e5e14)
Location: include/linux/blkdev.h:1048
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_open_bdev
```
```
In drivers/scsi/sd.c (ffffffff81c3a10c)
Location: include/linux/blkdev.h:1048
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_ioctl
```
```
In drivers/scsi/sr.c (ffffffff81c440f3)
Location: include/linux/blkdev.h:1048
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_ioctl
```
```
In drivers/md/dm-table.c (ffffffff81e319a9)
Location: include/linux/blkdev.h:1048
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_is_rq_stackable
```
</details>
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

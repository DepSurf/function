# Function: <code>bdev_nr_sectors</code>

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
In kernel/trace/blktrace.c (ffffffff811ce162)
Location: include/linux/genhd.h:273
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In fs/block_dev.c (ffffffff8136de3a)
Location: include/linux/genhd.h:273
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/bio.c (ffffffff8155bc88)
Location: include/linux/genhd.h:273
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
```
```
In block/blk-core.c (ffffffff81560442)
Location: include/linux/genhd.h:273
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
```
```
In block/genhd.c (ffffffff81575798)
Location: include/linux/genhd.h:273
Inline: True
Inline callers:
  - block/genhd.c:part_size_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:register_disk
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_part_iter_next
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff81579b82)
Location: include/linux/genhd.h:273
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
  - block/partitions/core.c:partition_overlaps
```
```
In block/partitions/cmdline.c (ffffffff8157b4ea)
Location: include/linux/genhd.h:273
Inline: True
Inline callers:
  - block/partitions/cmdline.c:cmdline_partition
```
```
In block/blk-zoned.c (ffffffff81595a65)
Location: include/linux/genhd.h:273
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/block/xen-blkfront.c (ffffffff81800add)
Location: include/linux/genhd.h:273
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_getgeo
```
```
In drivers/scsi/sd.c (ffffffff818540cb)
Location: include/linux/genhd.h:273
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81859e44)
Location: include/linux/genhd.h:273
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/dm.c (ffffffff8197bf3f)
Location: include/linux/genhd.h:273
Inline: True
Inline callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In drivers/md/dm-stats.c (ffffffff8198a5ad)
Location: include/linux/genhd.h:273
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In kernel/trace/blktrace.c (ffffffff811cedd2)
Location: include/linux/genhd.h:245
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In fs/block_dev.c (ffffffff81374836)
Location: include/linux/genhd.h:245
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/bio.c (ffffffff815642c5)
Location: include/linux/genhd.h:245
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
```
```
In block/blk-core.c (ffffffff815684dc)
Location: include/linux/genhd.h:245
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/genhd.c (ffffffff8157e457)
Location: include/linux/genhd.h:245
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_size_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:register_disk
  - block/genhd.c:disk_uevent
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff815818c8)
Location: include/linux/genhd.h:245
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
  - block/partitions/core.c:blk_add_partitions
  - block/partitions/core.c:blk_add_partitions
  - block/partitions/core.c:partition_overlaps
```
```
In block/partitions/cmdline.c (ffffffff81583139)
Location: include/linux/genhd.h:245
Inline: True
Inline callers:
  - block/partitions/cmdline.c:cmdline_partition
```
```
In block/blk-zoned.c (ffffffff8159c805)
Location: include/linux/genhd.h:245
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/block/xen-blkfront.c (ffffffff817e56ad)
Location: include/linux/genhd.h:245
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_getgeo
```
```
In drivers/scsi/sd.c (ffffffff81837b0b)
Location: include/linux/genhd.h:245
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff8183ce66)
Location: include/linux/genhd.h:245
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/dm.c (ffffffff8195fde3)
Location: include/linux/genhd.h:245
Inline: True
Inline callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In drivers/md/dm-stats.c (ffffffff8196eb4d)
Location: include/linux/genhd.h:245
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In kernel/trace/blktrace.c (ffffffff811fbcb2)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In fs/ext4/super.c (ffffffff814a465a)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In block/bdev.c (ffffffff815c4df1)
Location: include/linux/genhd.h:239
Inline: True
```
```
In block/bio.c (ffffffff815c8755)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
```
```
In block/blk-core.c (ffffffff815ccb0a)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/genhd.c (ffffffff815e337d)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_size_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:device_add_disk
  - block/genhd.c:disk_uevent
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff815e6cc4)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
  - block/partitions/core.c:partition_overlaps
```
```
In block/partitions/atari.c (ffffffff815e72dc)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff815e7e3b)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff815e8a20)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - block/partitions/cmdline.c:cmdline_partition
```
```
In block/partitions/ldm.c (ffffffff815ea4e9)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/efi.c (ffffffff815ed44b)
Location: include/linux/genhd.h:239
Inline: True
```
```
In block/blk-zoned.c (ffffffff81604eb5)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/block/xen-blkfront.c (ffffffff81871d9d)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_getgeo
```
```
In drivers/scsi/sd.c (ffffffff818c4607)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff818c97f4)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/dm-zone.c (ffffffff81a05cfd)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm-ima.c (ffffffff81a07906)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_rename
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_clear
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_remove
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_resume
```
```
In drivers/md/dm.c (ffffffff81a07d93)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
```
```
In drivers/md/dm-stats.c (ffffffff81a1743d)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In kernel/trace/blktrace.c (ffffffff81235ff7)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In fs/buffer.c (0)
Location: include/linux/blkdev.h:792
Inline: True
```
```
In fs/ext4/super.c (ffffffff8152cf9b)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/squashfs/super.c (ffffffff81550442)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff8155f955)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_static_bpb
```
```
In block/bdev.c (ffffffff8166f812)
Location: include/linux/blkdev.h:792
Inline: True
```
```
In block/fops.c (ffffffff8166ff3e)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_write_iter
```
```
In block/bio.c (ffffffff816734b5)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
```
```
In block/blk-core.c (ffffffff816796de)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/ioctl.c (ffffffff816912a8)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/genhd.c (ffffffff816925af)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_size_show
  - block/genhd.c:show_partition
  - block/genhd.c:show_partition
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:device_add_disk
  - block/genhd.c:disk_uevent
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff81695e52)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
  - block/partitions/core.c:partition_overlaps
```
```
In block/partitions/atari.c (ffffffff81696696)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff81696fe5)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - block/partitions/aix.c:read_lba
```
```
In block/partitions/cmdline.c (ffffffff81698097)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - block/partitions/cmdline.c:cmdline_partition
```
```
In block/partitions/ldm.c (ffffffff81699f49)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/efi.c (ffffffff8169e07b)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In block/blk-ia-ranges.c (ffffffff8169ffed)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - block/blk-ia-ranges.c:disk_set_independent_access_ranges
```
```
In block/blk-zoned.c (ffffffff816b86b1)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/block/xen-blkfront.c (ffffffff819b9e61)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_getgeo
```
```
In drivers/dax/super.c (ffffffff819e9413)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
```
In drivers/scsi/sd.c (ffffffff81a11270)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81a16b67)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/md.c (ffffffff81b6695b)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_rdev_size_change
```
```
In drivers/md/dm-zone.c (ffffffff81b6da1d)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm-ima.c (ffffffff81b6f689)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_rename
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_clear
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_remove
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_resume
```
```
In drivers/md/dm.c (ffffffff81b718db)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
```
```
In drivers/md/dm-table.c (ffffffff81b74955)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-linear.c (ffffffff81b77be2)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_prepare_ioctl
```
```
In drivers/md/dm-stats.c (ffffffff81b801dc)
Location: include/linux/blkdev.h:792
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In kernel/trace/blktrace.c (ffffffff81282907)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In fs/buffer.c (0)
Location: include/linux/blkdev.h:780
Inline: True
```
```
In fs/ext4/super.c (ffffffff815c530d)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_geometry_check
```
```
In fs/squashfs/super.c (ffffffff815f107c)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff81601d05)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_static_bpb
```
```
In block/bdev.c (ffffffff8172abf8)
Location: include/linux/blkdev.h:780
Inline: True
```
```
In block/fops.c (ffffffff8172b49e)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_write_iter
```
```
In block/bio.c (ffffffff8172f055)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
```
```
In block/blk-core.c (ffffffff81735baa)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/ioctl.c (ffffffff8174fed5)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/genhd.c (ffffffff817518af)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_size_show
  - block/genhd.c:show_partition
  - block/genhd.c:show_partition
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:device_add_disk
  - block/genhd.c:disk_uevent
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff81755200)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
  - block/partitions/core.c:partition_overlaps
```
```
In block/partitions/atari.c (ffffffff81755886)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff81755f45)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - block/partitions/aix.c:read_lba
```
```
In block/partitions/cmdline.c (ffffffff81756fe7)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - block/partitions/cmdline.c:cmdline_partition
```
```
In block/partitions/ldm.c (ffffffff81759290)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/efi.c (ffffffff8175cabb)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In block/blk-ia-ranges.c (ffffffff8175ea13)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - block/blk-ia-ranges.c:disk_set_independent_access_ranges
```
```
In block/blk-zoned.c (ffffffff81778052)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:bdev_nr_zones
```
```
In drivers/block/xen-blkfront.c (ffffffff81b2f331)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_getgeo
```
```
In drivers/dax/super.c (ffffffff81b65c5c)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
```
In drivers/scsi/sd.c (ffffffff81b91500)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81b979b7)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/md.c (ffffffff81d02157)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_rdev_size_change
```
```
In drivers/md/dm-zone.c (ffffffff81d09da4)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm-ima.c (ffffffff81d0bc69)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_rename
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_clear
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_remove
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_resume
```
```
In drivers/md/dm.c (ffffffff81d0d0bb)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - drivers/md/dm.c:__bind
```
```
In drivers/md/dm-table.c (ffffffff81d1197a)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-linear.c (ffffffff81d15102)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_prepare_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff81d17b4f)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
```
```
In drivers/md/dm-stats.c (ffffffff81d1d90c)
Location: include/linux/blkdev.h:780
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In kernel/trace/blktrace.c (ffffffff8129f5a7)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In fs/buffer.c (0)
Location: include/linux/blkdev.h:764
Inline: True
```
```
In fs/ext4/super.c (ffffffff815fcde2)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_geometry
```
```
In fs/squashfs/super.c (ffffffff816290e1)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff81639c05)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_static_bpb
```
```
In block/bdev.c (ffffffff81766e83)
Location: include/linux/blkdev.h:764
Inline: True
```
```
In block/fops.c (ffffffff817687fb)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_write_iter
```
```
In block/bio.c (ffffffff8176b2a5)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
```
```
In block/blk-core.c (ffffffff81772059)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/ioctl.c (ffffffff8178c17e)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/genhd.c (ffffffff8178de2c)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_size_show
  - block/genhd.c:show_partition
  - block/genhd.c:show_partition
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/genhd.c:disk_uevent
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff817914de)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_add_partition
  - block/partitions/core.c:partition_overlaps
```
```
In block/partitions/atari.c (ffffffff81792316)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff81792c55)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/partitions/aix.c:read_lba
```
```
In block/partitions/cmdline.c (ffffffff817941a2)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/partitions/cmdline.c:cmdline_partition
```
```
In block/partitions/ldm.c (ffffffff81796790)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/efi.c (ffffffff8179b356)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In block/blk-ia-ranges.c (ffffffff8179d913)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/blk-ia-ranges.c:disk_set_independent_access_ranges
```
```
In block/early-lookup.c (ffffffff836fe3d6)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/early-lookup.c:printk_all_partitions
  - block/early-lookup.c:printk_all_partitions
```
```
In block/blk-zoned.c (ffffffff817b7eb5)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:bdev_nr_zones
```
```
In drivers/block/virtio_blk.c (ffffffff81b7f864)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/block/virtio_blk.c:virtblk_parse_zone
```
```
In drivers/block/xen-blkfront.c (ffffffff81b82781)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_getgeo
```
```
In drivers/dax/super.c (ffffffff81bb927c)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
```
In drivers/scsi/sd.c (ffffffff81be7a25)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81bedf43)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/md.c (ffffffff81d6b287)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_rdev_size_change
```
```
In drivers/md/dm-zone.c (ffffffff81d72ef3)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm-ima.c (ffffffff81d74d99)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_rename
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_clear
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_remove
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_resume
```
```
In drivers/md/dm.c (ffffffff81d75e7b)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - drivers/md/dm.c:__bind
```
```
In drivers/md/dm-table.c (ffffffff81d7add5)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-linear.c (ffffffff81d7e272)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_prepare_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff81d80dcf)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
```
```
In drivers/md/dm-stats.c (ffffffff81d86afc)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In kernel/trace/blktrace.c (ffffffff812bace5)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In fs/buffer.c (0)
Location: include/linux/blkdev.h:742
Inline: True
```
```
In fs/ext4/super.c (ffffffff81635902)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_geometry
```
```
In fs/squashfs/super.c (ffffffff81662330)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff816730f5)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_static_bpb
```
```
In block/bdev.c (ffffffff817a8b4a)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - block/bdev.c:bdev_open_by_dev
```
```
In block/fops.c (ffffffff817aa69e)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_write_iter
```
```
In block/bio.c (ffffffff817ad735)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
```
```
In block/blk-core.c (ffffffff817b42d8)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/ioctl.c (ffffffff817ce91e)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/genhd.c (ffffffff817d068c)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_size_show
  - block/genhd.c:show_partition
  - block/genhd.c:show_partition
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/genhd.c:disk_uevent
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff817d4de0)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:blk_add_partitions
  - block/partitions/core.c:blk_add_partitions
  - block/partitions/core.c:bdev_add_partition
  - block/partitions/core.c:partition_overlaps
```
```
In block/partitions/atari.c (ffffffff817d5c26)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff817d6565)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - block/partitions/aix.c:read_lba
```
```
In block/partitions/cmdline.c (ffffffff817d7b02)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - block/partitions/cmdline.c:cmdline_partition
```
```
In block/partitions/ldm.c (ffffffff817da18e)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/efi.c (ffffffff817dedb6)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In block/blk-ia-ranges.c (ffffffff817e1363)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - block/blk-ia-ranges.c:disk_set_independent_access_ranges
```
```
In block/early-lookup.c (ffffffff83931ab6)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - block/early-lookup.c:printk_all_partitions
  - block/early-lookup.c:printk_all_partitions
```
```
In block/blk-zoned.c (ffffffff817fc594)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:bdev_nr_zones
```
```
In drivers/block/virtio_blk.c (ffffffff81bd36e4)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/block/virtio_blk.c:virtblk_parse_zone
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd6641)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_getgeo
```
```
In drivers/dax/super.c (ffffffff81c0d8d9)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
```
In drivers/scsi/sd.c (ffffffff81c3cd9f)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81c43650)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/md/md.c (ffffffff81e1cc77)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_rdev_size_change
```
```
In drivers/md/dm-zone.c (ffffffff81e29ff3)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm-ima.c (ffffffff81e2bea9)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_rename
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_clear
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_remove
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_resume
```
```
In drivers/md/dm.c (ffffffff81e2d0ab)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - drivers/md/dm.c:__bind
```
```
In drivers/md/dm-table.c (ffffffff81e32c7c)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-linear.c (ffffffff81e35872)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_prepare_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff81e3842f)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
```
```
In drivers/md/dm-stats.c (ffffffff81e3e20c)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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

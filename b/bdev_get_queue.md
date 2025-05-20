# Function: <code>bdev_get_queue</code>

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
In kernel/trace/blktrace.c (ffffffff8115b882)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff811d66d7)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
```
```
In fs/super.c (ffffffff8120e752)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super
```
```
In fs/buffer.c (ffffffff81243c1b)
Location: include/linux/blkdev.h:823
Inline: True
```
```
In fs/block_dev.c (ffffffff8124742f)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:sb_min_blocksize
```
```
In fs/direct-io.c (ffffffff8124a15d)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/ext4/ioctl.c (ffffffff812a0d23)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81322a00)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff812fd818)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-core.c (ffffffff813b45a5)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - block/blk-core.c:blk_get_backing_dev_info
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:submit_bio
```
```
In block/blk-flush.c (ffffffff813bda71)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-settings.c (ffffffff813bea83)
Location: include/linux/blkdev.h:823
Inline: True
```
```
In block/blk-lib.c (ffffffff813c2693)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_zeroout
```
```
In block/ioctl.c (ffffffff813c918d)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partitions/msdos.c (ffffffff813d2925)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff813d3989)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
```
In block/compat_ioctl.c (ffffffff813e5f98)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/bio-integrity.c (ffffffff813e71fc)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In drivers/block/loop.c (ffffffff8156e0e2)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/bitmap.c (ffffffff8169bb6b)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_sb_page
  - drivers/md/bitmap.c:write_page
```
```
In drivers/md/dm.c (ffffffff816a0d28)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-table.c (ffffffff816a4d0f)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_is_nonrot
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:queue_supports_sg_merge
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:device_discard_capable
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_any_congested
```
```
In drivers/md/dm-io.c (ffffffff816aaed5)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff816abdff)
Location: include/linux/blkdev.h:823
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff81167305)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff811f480f)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
```
```
In fs/super.c (ffffffff81235182)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super
```
```
In fs/buffer.c (ffffffff8126c9cc)
Location: include/linux/blkdev.h:842
Inline: True
```
```
In fs/block_dev.c (ffffffff81270633)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:bdev_direct_access
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff81272c49)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff812868e9)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - fs/dax.c:__dax_zero_page_range
```
```
In fs/ext4/ioctl.c (ffffffff812cfa51)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff812ed32f)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff813313af)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-core.c (ffffffff813fdc1f)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_get_backing_dev_info
```
```
In block/blk-flush.c (ffffffff814019da)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-settings.c (ffffffff814029e0)
Location: include/linux/blkdev.h:842
Inline: True
```
```
In block/blk-lib.c (ffffffff814066bc)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff8140d4b0)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partitions/atari.c (ffffffff81413b82)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8141844c)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff8141a15a)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff8142c248)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/bio-integrity.c (ffffffff8142d478)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In drivers/block/loop.c (ffffffff815c39d2)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/bitmap.c (ffffffff816fea04)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
  - drivers/md/bitmap.c:read_sb_page
```
```
In drivers/md/dm.c (ffffffff8170208d)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-table.c (ffffffff81707472)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_discard_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:queue_supports_sg_merge
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_nonrot
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:device_supports_dax
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff8170b381)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff8170c31b)
Location: include/linux/blkdev.h:842
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff81171c65)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff81205362)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
```
```
In fs/super.c (ffffffff81247d22)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super
```
```
In fs/buffer.c (ffffffff8127fca6)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81283f41)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:bdev_direct_access
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff8128674b)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8129a879)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - fs/dax.c:__dax_zero_page_range
```
```
In fs/iomap.c (ffffffff812b0c52)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_actor
```
```
In fs/ext4/ioctl.c (ffffffff812e57f6)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81303725)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff81347141)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-core.c (ffffffff8141755e)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_get_backing_dev_info
```
```
In block/blk-flush.c (ffffffff8141b63a)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-settings.c (ffffffff8141c680)
Location: include/linux/blkdev.h:963
Inline: True
```
```
In block/blk-lib.c (ffffffff814209f6)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff81428862)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partition-generic.c (ffffffff8142d166)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/partitions/atari.c (ffffffff8142f0b2)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8143397c)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff8143568a)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff81446048)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/bio-integrity.c (ffffffff81447258)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-zoned.c (ffffffff8144921a)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/block/loop.c (ffffffff815f20b2)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff8172a632)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/bitmap.c (ffffffff8173065f)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
  - drivers/md/bitmap.c:read_sb_page
```
```
In drivers/md/dm.c (ffffffff81733f6f)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-table.c (ffffffff81739342)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_discard_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:queue_supports_sg_merge
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_nonrot
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:device_supports_dax
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff8173d30e)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff8173e34b)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff81174ff0)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/page_io.c (ffffffff8120b8ba)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swapfile.c (ffffffff812109ec)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
```
```
In fs/buffer.c (ffffffff8128d256)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81291642)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff81293dcf)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff812a9465)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - fs/dax.c:__dax_zero_page_range
```
```
In fs/iomap.c (ffffffff812be058)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_actor
```
```
In fs/ext4/ioctl.c (ffffffff813091fa)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81337bdc)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff8135bba2)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/bio.c (ffffffff8141dab2)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff814253bd)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-flush.c (ffffffff8142932a)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-settings.c (ffffffff8142a5e0)
Location: include/linux/blkdev.h:996
Inline: True
```
```
In block/blk-lib.c (ffffffff8142e966)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff81436c61)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partition-generic.c (ffffffff8143a482)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/partitions/atari.c (ffffffff8143c2f2)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8144078a)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814421df)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff81454696)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/bio-integrity.c (ffffffff81455698)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-zoned.c (ffffffff8145774a)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/block/loop.c (ffffffff816062c2)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff81743000)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/bitmap.c (ffffffff8174850c)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
  - drivers/md/bitmap.c:read_sb_page
```
```
In drivers/md/dm.c (ffffffff8174d08c)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-table.c (ffffffff81752bb5)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_discard_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:queue_supports_sg_merge
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_nonrot
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_matches_zone_sectors
  - drivers/md/dm-table.c:device_is_zoned_model
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:device_supports_dax
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff81756fe3)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff8175800c)
Location: include/linux/blkdev.h:996
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff811823d0)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff81227eec)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapoff
```
```
In fs/buffer.c (ffffffff812afd96)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff812b4392)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff812b6d2f)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff812cca35)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - fs/dax.c:__dax_zero_page_range
```
```
In fs/iomap.c (ffffffff812e1afd)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_actor
```
```
In fs/ext4/ioctl.c (ffffffff8132de55)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8135cfc2)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff813808ac)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-flush.c (ffffffff8145442e)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-settings.c (ffffffff81455820)
Location: include/linux/blkdev.h:1009
Inline: True
```
```
In block/blk-lib.c (ffffffff81459e45)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814629fa)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partition-generic.c (ffffffff814664a5)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/partitions/atari.c (ffffffff814683d2)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8146ce21)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff8146eb4f)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff81480326)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff8148347a)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/block/loop.c (ffffffff8166e6c2)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff817b513d)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffffffff817ba79c)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-table.c (ffffffff817c4df8)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:queue_supports_sg_merge
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_nonrot
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_matches_zone_sectors
  - drivers/md/dm-table.c:device_is_zoned_model
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:device_supports_dax
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff817c9202)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff817ca280)
Location: include/linux/blkdev.h:1009
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff8119153c)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff8124d8e2)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/buffer.c (ffffffff812d7fe5)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff812db9b8)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff812df71f)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff812f7125)
Location: include/linux/blkdev.h:1020
Inline: True
```
```
In fs/iomap.c (ffffffff8130e226)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_actor
```
```
In fs/ext4/ioctl.c (ffffffff8135c229)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813865a9)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff813aeeb3)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-flush.c (ffffffff8148787e)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-settings.c (ffffffff81488b85)
Location: include/linux/blkdev.h:1020
Inline: True
```
```
In block/blk-lib.c (ffffffff8148d59e)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814966ea)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partition-generic.c (ffffffff81499d8a)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/partitions/atari.c (ffffffff8149c262)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff814a0cf6)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814a2b1c)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:find_valid_gpt
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff814b53cc)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff814b8224)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/block/loop.c (ffffffff816aa1a2)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/dax/super.c (ffffffff816e2053)
Location: include/linux/blkdev.h:1020
Inline: True
```
```
In drivers/md/md.c (ffffffff817fcd26)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffffffff81802752)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-table.c (ffffffff8180d9ca)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:queue_supports_sg_merge
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_nonrot
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_matches_zone_sectors
  - drivers/md/dm-table.c:device_is_zoned_model
  - drivers/md/dm-table.c:device_is_rq_based
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff81811f7f)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff8181307f)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff8119e7ac)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff81262b4e)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/buffer.c (ffffffff812ed055)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff812f10a8)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffff812f422f)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8130c1d5)
Location: include/linux/blkdev.h:864
Inline: True
```
```
In fs/iomap.c (ffffffff81323a50)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_actor
  - fs/iomap.c:iomap_dio_bio_actor
  - fs/iomap.c:iomap_dio_bio_actor
```
```
In fs/ext4/ioctl.c (ffffffff81374ad4)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8139f0a9)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/file.c (ffffffff813c5e27)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff813c8092)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-flush.c (ffffffff814a19de)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-settings.c (ffffffff814a2aa5)
Location: include/linux/blkdev.h:864
Inline: True
```
```
In block/blk-lib.c (ffffffff814a6e2e)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814b05ff)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partition-generic.c (ffffffff814b409a)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/partitions/atari.c (ffffffff814b6582)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff814bb0b6)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814bccfe)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff814c8c89)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff814cc164)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/block/loop.c (ffffffff816cad92)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/dax/super.c (ffffffff81705473)
Location: include/linux/blkdev.h:864
Inline: True
```
```
In drivers/md/md.c (ffffffff81828e2b)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffffffff8182ea3b)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-table.c (ffffffff8183991a)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:queue_supports_sg_merge
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_nonrot
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_matches_zone_sectors
  - drivers/md/dm-table.c:device_is_zoned_model
  - drivers/md/dm-table.c:device_is_rq_based
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff8183deea)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff8183f04f)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff811ac48c)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff8127da21)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/buffer.c (ffffffff8130e806)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81312fac)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffff81316948)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff81333720)
Location: include/linux/blkdev.h:881
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8134d7fb)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/ioctl.c (ffffffff8139d982)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813c90be)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/file.c (ffffffff813f0dfc)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff813f2c67)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-flush.c (ffffffff814cfb23)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-settings.c (ffffffff814d0b85)
Location: include/linux/blkdev.h:881
Inline: True
```
```
In block/blk-lib.c (ffffffff814d4d4e)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814de904)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partition-generic.c (ffffffff814e2586)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/partitions/atari.c (ffffffff814e4ac2)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff814e971c)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814eb38a)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff814f761a)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff814faa04)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/block/loop.c (ffffffff817088b3)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/dax/super.c (ffffffff8173f40f)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/md.c (ffffffff8186b44c)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffffffff81870f24)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-table.c (ffffffff8187c45a)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_requires_stable_pages
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_nonrot
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_matches_zone_sectors
  - drivers/md/dm-table.c:device_is_zoned_model
  - drivers/md/dm-table.c:device_is_rq_based
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff81880bcb)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81881d84)
Location: include/linux/blkdev.h:881
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff811b7cf0)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff8128d4c1)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/buffer.c (ffffffff81321826)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81325ed7)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffff813297c8)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff813472e0)
Location: include/linux/blkdev.h:898
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff81365abb)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/ioctl.c (ffffffff813b6452)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813e246e)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/file.c (ffffffff8140acdc)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff8140cc3d)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-flush.c (ffffffff814e8e83)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-settings.c (ffffffff814e9f05)
Location: include/linux/blkdev.h:898
Inline: True
```
```
In block/blk-lib.c (ffffffff814ee03e)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814f7d43)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partition-generic.c (ffffffff814fb946)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/partitions/atari.c (ffffffff814fde82)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff81502ae6)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff81504752)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff815151c6)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff81518984)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/block/loop.c (ffffffff8172cb13)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/dax/super.c (ffffffff817635ef)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/md.c (ffffffff8189d22e)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffffffff818a2d0d)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-table.c (ffffffff818ae23a)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_requires_stable_pages
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_nonrot
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_matches_zone_sectors
  - drivers/md/dm-table.c:device_is_zoned_model
  - drivers/md/dm-table.c:device_is_rq_based
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff818b2a8b)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff818b3c24)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff811d0e40)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff812bff83)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - mm/swapfile.c:cgroup_throttle_swaprate
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/buffer.c (ffffffff8135be25)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
```
```
In fs/block_dev.c (ffffffff8135f277)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffff813635b1)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813acf05)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
```
```
In fs/ext4/ioctl.c (ffffffff81402437)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8142e52a)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/file.c (ffffffff81457b1e)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_fitrim
```
```
In fs/fat/inode.c (ffffffff8145aa86)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-settings.c (ffffffff81548f92)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - block/blk-settings.c:disk_stack_limits
```
```
In block/blk-lib.c (ffffffff8154d9a7)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff815588e1)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/partitions/atari.c (ffffffff8155e5c9)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8156337e)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/efi.c (ffffffff815651a1)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:alloc_read_gpt_header
  - block/partitions/efi.c:read_lba
```
```
In block/blk-zoned.c (ffffffff81578db8)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/block/loop.c (ffffffff817ea414)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/dax/super.c (ffffffff8182348f)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/md.c (ffffffff8196d563)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffffffff81972838)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-table.c (ffffffff8197e49a)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_requires_stable_pages
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_nonrot
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_matches_zone_sectors
  - drivers/md/dm-table.c:device_is_zoned_model
  - drivers/md/dm-table.c:device_is_rq_stackable
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff81983028)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
```
```
In drivers/md/dm-kcopyd.c (ffffffff81984ac4)
Location: include/linux/blkdev.h:916
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff811ce1f1)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff812cbb3e)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - mm/swapfile.c:cgroup_throttle_swaprate
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/buffer.c (ffffffff8136a3c5)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
```
```
In fs/block_dev.c (ffffffff8136e3ee)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff81370861)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/io_uring.c (ffffffff8138999b)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - fs/io_uring.c:io_file_supports_async
  - fs/io_uring.c:io_file_supports_async
```
```
In fs/crypto/inline_crypt.c (ffffffff813a7849)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
```
```
In fs/iomap/direct-io.c (ffffffff813be5f5)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
```
```
In fs/ext4/ioctl.c (ffffffff81414d12)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81447207)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/file.c (ffffffff81473e6e)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_fitrim
```
```
In fs/fat/inode.c (ffffffff81476dd6)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-settings.c (ffffffff81564c9c)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - block/blk-settings.c:disk_stack_limits
```
```
In block/blk-lib.c (ffffffff81569b27)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff81574ee5)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/partitions/atari.c (ffffffff8157a209)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8157e4be)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/efi.c (ffffffff8158029e)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:alloc_read_gpt_header
  - block/partitions/efi.c:read_lba
```
```
In block/blk-zoned.c (ffffffff81595818)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/block/loop.c (ffffffff817fee79)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/dax/super.c (ffffffff818321bf)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/md.c (ffffffff8197446b)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffffffff81977754)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-table.c (ffffffff81980105)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_nowait_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_rotational
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_not_matches_zone_sectors
  - drivers/md/dm-table.c:device_not_zoned_model
  - drivers/md/dm-table.c:device_is_rq_stackable
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff81987148)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
```
```
In drivers/md/dm-kcopyd.c (ffffffff81988b64)
Location: include/linux/blkdev.h:964
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff811cf715)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff812d26c3)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - mm/swapfile.c:cgroup_throttle_swaprate
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/buffer.c (ffffffff81371026)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81374cfb)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff81377130)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/io_uring.c (ffffffff813907b1)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - fs/io_uring.c:__io_file_supports_async
  - fs/io_uring.c:__io_file_supports_async
```
```
In fs/crypto/inline_crypt.c (ffffffff813ae890)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
```
```
In fs/iomap/direct-io.c (ffffffff813c5be5)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
```
```
In fs/ext4/ioctl.c (ffffffff8141adb7)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff8142384b)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/ext4/super.c (ffffffff8144ca07)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/file.c (ffffffff8147a6dd)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff8147c84a)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-settings.c (ffffffff8156d2ec)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - block/blk-settings.c:disk_stack_limits
```
```
In block/blk-lib.c (ffffffff81571a7e)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff8157cf75)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/partitions/atari.c (ffffffff81581f39)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8158604e)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/efi.c (ffffffff81587e17)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/blk-zoned.c (ffffffff8159c5b8)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/block/loop.c (ffffffff817e31b0)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_config_discard
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/dax/super.c (ffffffff8181579f)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/md.c (ffffffff8195849b)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffffffff8195b6ae)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-table.c (ffffffff81964215)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_nowait_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_rotational
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_not_matches_zone_sectors
  - drivers/md/dm-table.c:device_not_zoned_model
  - drivers/md/dm-table.c:device_intersect_crypto_modes
  - drivers/md/dm-table.c:dm_keyslot_evict_callback
  - drivers/md/dm-table.c:device_is_rq_stackable
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff8196b81f)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
```
```
In drivers/md/dm-kcopyd.c (ffffffff8196d244)
Location: include/linux/blkdev.h:947
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff811fbd65)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff81317fc3)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - mm/swapfile.c:__cgroup_throttle_swaprate
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/buffer.c (ffffffff813c09f6)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff813c3a96)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/io_uring.c (ffffffff813ddd61)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - fs/io_uring.c:__io_file_supports_nowait
  - fs/io_uring.c:__io_file_supports_nowait
```
```
In fs/crypto/inline_crypt.c (ffffffff813fe430)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
```
```
In fs/iomap/direct-io.c (ffffffff81415578)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
```
```
In fs/ext4/ioctl.c (ffffffff8146e10b)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff81479d2e)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/ext4/super.c (ffffffff814a0a97)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/jbd2/journal.c (ffffffff814c0722)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_erase
```
```
In fs/fat/file.c (ffffffff814d1d4d)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff814d3f3f)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/bdev.c (ffffffff815c40c6)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
```
```
In block/fops.c (ffffffff815c54fa)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:blkdev_iopoll
  - block/fops.c:__blkdev_direct_IO_simple
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/blk-settings.c (ffffffff815d1915)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - block/blk-settings.c:disk_stack_limits
```
```
In block/blk-lib.c (ffffffff815d618e)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff815e2575)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/blk-zoned.c (ffffffff81604c26)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/block/loop.c (ffffffff8186e35c)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_config_discard
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff819fdc28)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffffffff81a00e9e)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-zone.c (ffffffff81a061c3)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio_end
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:device_not_zone_append_capable
```
```
In drivers/md/dm-table.c (ffffffff81a0c1c5)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_nowait_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_rotational
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_not_matches_zone_sectors
  - drivers/md/dm-table.c:device_not_zoned_model
  - drivers/md/dm-table.c:device_intersect_crypto_modes
  - drivers/md/dm-table.c:dm_keyslot_evict_callback
  - drivers/md/dm-table.c:device_is_rq_stackable
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff81a13cdf)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
```
```
In drivers/md/dm-kcopyd.c (ffffffff81a1531c)
Location: include/linux/blkdev.h:905
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff812360be)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff81383684)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - mm/swapfile.c:__cgroup_throttle_swaprate
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/super.c (ffffffff813f4d88)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/buffer.c (ffffffff814459d8)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff8144a951)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/crypto/inline_crypt.c (ffffffff81471f52)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
```
```
In fs/iomap/direct-io.c (ffffffff8148ccd8)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/ioctl.c (ffffffff814ee4bf)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff814fbf0f)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/ext4/super.c (ffffffff81527559)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/jbd2/journal.c (ffffffff8154b113)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_erase
```
```
In fs/fat/file.c (ffffffff8155ea9c)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff81561178)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/bdev.c (ffffffff8166f36b)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_read_page
  - block/bdev.c:bdev_read_page
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
```
```
In block/fops.c (ffffffff8166ff6b)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/bio.c (ffffffff816726f8)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_bvec_set
  - block/bio.c:bio_add_zone_append_page
```
```
In block/blk-core.c (ffffffff81679eb5)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:bio_poll
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio
```
```
In block/blk-settings.c (ffffffff8167d3b5)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - block/blk-settings.c:bdev_discard_alignment
  - block/blk-settings.c:bdev_alignment_offset
  - block/blk-settings.c:disk_stack_limits
```
```
In block/blk-merge.c (ffffffff81680660)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-lib.c (ffffffff816823a3)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-mq.c (ffffffff8168972e)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_get_new_requests
```
```
In block/ioctl.c (ffffffff816911c2)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/genhd.c (ffffffff816926a3)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_stat_show
```
```
In block/blk-cgroup.c (ffffffff816a2607)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_finish
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In block/blk-throttle.c (ffffffff816aa985)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
```
```
In block/blk-iocost.c (ffffffff816ae7d6)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
```
In block/bio-integrity.c (ffffffff816b4d7f)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-zoned.c (ffffffff816b8424)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:blkdev_report_zones
```
```
In block/blk-crypto.c (ffffffff816c1b83)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In io_uring/io_uring.c (ffffffff816c7427)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_file_get_flags
  - io_uring/io_uring.c:io_file_get_flags
```
```
In drivers/block/loop.c (ffffffff819b7b85)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff81b668f9)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffffffff81b67bb9)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-zone.c (ffffffff81b6de35)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:device_not_zone_append_capable
```
```
In drivers/md/dm.c (ffffffff81b72f44)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-table.c (ffffffff81b74885)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_nowait_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_rotational
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_not_matches_zone_sectors
  - drivers/md/dm-table.c:device_not_zoned_model
  - drivers/md/dm-table.c:device_not_poll_capable
  - drivers/md/dm-table.c:device_intersect_crypto_capabilities
  - drivers/md/dm-table.c:dm_keyslot_evict_callback
  - drivers/md/dm-table.c:device_is_rq_stackable
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff81b7c5fb)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
```
```
In drivers/md/dm-kcopyd.c (ffffffff81b7e168)
Location: include/linux/blkdev.h:896
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff812829de)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff813fcab6)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/super.c (ffffffff8147ded8)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/buffer.c (ffffffff814d4a58)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff814d904c)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff81520263)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/inode.c (ffffffff81580868)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_getattr
  - fs/ext4/inode.c:ext4_getattr
```
```
In fs/ext4/ioctl.c (ffffffff815883bf)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff8159668f)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/ext4/super.c (ffffffff815c5639)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/jbd2/journal.c (ffffffff815ead68)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_erase
```
```
In fs/fat/file.c (ffffffff81600c9c)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff816036fa)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/bdev.c (ffffffff8172b0ca)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - block/bdev.c:bdev_statx_dioalign
  - block/bdev.c:bdev_statx_dioalign
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_read_page
  - block/bdev.c:bdev_read_page
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
```
```
In block/fops.c (ffffffff8172b4cb)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
```
```
In block/bio.c (ffffffff8172e078)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_iov_bvec_set
  - block/bio.c:bio_add_zone_append_page
```
```
In block/blk-core.c (ffffffff8173637b)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:bio_poll
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio
```
```
In block/blk-settings.c (ffffffff81739e75)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - block/blk-settings.c:bdev_discard_alignment
  - block/blk-settings.c:bdev_alignment_offset
  - block/blk-settings.c:disk_stack_limits
```
```
In block/blk-merge.c (ffffffff8173ef23)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
  - block/blk-merge.c:bio_split_to_limits
```
```
In block/blk-lib.c (ffffffff8173fa39)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-mq.c (ffffffff81747bdc)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_get_new_requests
```
```
In block/ioctl.c (ffffffff8174fde5)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/genhd.c (ffffffff81750d42)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_stat_show
```
```
In block/blk-cgroup.c (ffffffff8175ffb5)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_finish
```
```
In block/blk-throttle.c (ffffffff81769425)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
```
```
In block/blk-iocost.c (ffffffff8176da37)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
```
```
In block/bio-integrity.c (ffffffff8177485b)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-zoned.c (ffffffff817788f4)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:bdev_nr_zones
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In block/blk-crypto.c (ffffffff81782805)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_evict_key
  - block/blk-crypto.c:blk_crypto_start_using_key
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In io_uring/io_uring.c (ffffffff8179004d)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_file_get_flags
  - io_uring/io_uring.c:io_file_get_flags
```
```
In drivers/block/loop.c (ffffffff81b2cec5)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff81d02208)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffffffff81d03569)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-zone.c (ffffffff81d0a309)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:device_not_zone_append_capable
```
```
In drivers/md/dm.c (ffffffff81d0eed1)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-table.c (ffffffff81d117d5)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_nowait_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_rotational
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_not_matches_zone_sectors
  - drivers/md/dm-table.c:device_not_zoned_model
  - drivers/md/dm-table.c:device_not_poll_capable
  - drivers/md/dm-table.c:device_intersect_crypto_capabilities
  - drivers/md/dm-table.c:device_is_rq_stackable
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff81d1a44d)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d1c170)
Location: include/linux/blkdev.h:876
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff8129f681)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff8142fe38)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/super.c (ffffffff814b2c65)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/buffer.c (ffffffff8150c505)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
```
```
In fs/direct-io.c (ffffffff81511eea)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff815582d0)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/inode.c (ffffffff815b7e28)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_getattr
  - fs/ext4/inode.c:ext4_getattr
```
```
In fs/ext4/ioctl.c (ffffffff815bf1d6)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff815cd0d5)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/ext4/super.c (ffffffff815fd25d)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/jbd2/journal.c (ffffffff816227e8)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_erase
```
```
In fs/fat/file.c (ffffffff81638b8f)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff8163b61a)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/bdev.c (ffffffff8176733a)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - block/bdev.c:bdev_statx_dioalign
  - block/bdev.c:bdev_statx_dioalign
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
```
```
In block/fops.c (ffffffff81768824)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_open
```
```
In block/bio.c (ffffffff8176a341)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_iov_bvec_set
  - block/bio.c:bio_add_zone_append_page
```
```
In block/blk-core.c (ffffffff817729d3)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio
```
```
In block/blk-settings.c (ffffffff81776555)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - block/blk-settings.c:bdev_discard_alignment
  - block/blk-settings.c:bdev_alignment_offset
  - block/blk-settings.c:disk_stack_limits
```
```
In block/blk-merge.c (ffffffff8177b495)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
  - block/blk-merge.c:bio_split_to_limits
```
```
In block/blk-lib.c (ffffffff8177bf69)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-mq.c (ffffffff81781e5b)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_get_new_requests
```
```
In block/ioctl.c (ffffffff8178c008)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/genhd.c (ffffffff8178d312)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_stat_show
```
```
In block/blk-cgroup.c (ffffffff8179efa4)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_exit
```
```
In block/blk-throttle.c (ffffffff817a85e5)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
```
```
In block/blk-iocost.c (ffffffff817acf40)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
```
```
In block/bio-integrity.c (ffffffff817b44b1)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-zoned.c (ffffffff817b84c1)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:bdev_nr_zones
```
```
In block/blk-crypto.c (ffffffff817c2945)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_evict_key
  - block/blk-crypto.c:blk_crypto_start_using_key
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In drivers/block/loop.c (ffffffff81b7d0f3)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff81d6b33b)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffffffff81d6d345)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:__write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-zone.c (ffffffff81d73449)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:device_not_zone_append_capable
```
```
In drivers/md/dm.c (ffffffff81d780ea)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-table.c (ffffffff81d7ac35)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_nowait_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_rotational
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_not_matches_zone_sectors
  - drivers/md/dm-table.c:device_not_zoned_model
  - drivers/md/dm-table.c:device_not_poll_capable
  - drivers/md/dm-table.c:device_intersect_crypto_capabilities
  - drivers/md/dm-table.c:device_is_rq_stackable
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff81d835aa)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d852ec)
Location: include/linux/blkdev.h:857
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff812badb1)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff81469452)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/super.c (ffffffff814e410e)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - fs/super.c:setup_bdev_super
```
```
In fs/buffer.c (ffffffff81541145)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
```
```
In fs/direct-io.c (ffffffff815463b1)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8158e900)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/inode.c (ffffffff815f0bbc)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_getattr
  - fs/ext4/inode.c:ext4_getattr
```
```
In fs/ext4/ioctl.c (ffffffff815f7f7c)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff816059b5)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/ext4/super.c (ffffffff81635d9c)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_journal_blkdev
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/jbd2/journal.c (ffffffff8165b848)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_erase
```
```
In fs/fat/file.c (ffffffff8167207f)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff81674b79)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/bdev.c (ffffffff817a900a)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - block/bdev.c:bdev_statx_dioalign
  - block/bdev.c:bdev_statx_dioalign
  - block/bdev.c:bdev_add
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
```
```
In block/fops.c (ffffffff817aa6c7)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_open
  - block/fops.c:blkdev_iomap_begin
```
```
In block/bio.c (ffffffff817ac7a1)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_iov_bvec_set
  - block/bio.c:bio_add_zone_append_page
```
```
In block/blk-core.c (ffffffff817b4d73)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio
```
```
In block/blk-settings.c (ffffffff817b8885)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - block/blk-settings.c:bdev_discard_alignment
  - block/blk-settings.c:bdev_alignment_offset
  - block/blk-settings.c:disk_stack_limits
```
```
In block/blk-merge.c (ffffffff817bc41d)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - block/blk-merge.c:bio_split_to_limits
```
```
In block/blk-lib.c (ffffffff817be359)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-mq.c (ffffffff817c659d)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/ioctl.c (ffffffff817ce7a8)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/genhd.c (ffffffff817cfb72)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_stat_show
```
```
In block/partitions/core.c (0)
Location: include/linux/blkdev.h:835
Inline: True
```
```
In block/blk-cgroup.c (ffffffff817e2a74)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_exit
```
```
In block/blk-throttle.c (ffffffff817ec355)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
```
```
In block/blk-iocost.c (ffffffff817f0d40)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
```
```
In block/bio-integrity.c (ffffffff817f9329)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_map_user
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-zoned.c (ffffffff817fcba9)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
```
In block/blk-crypto.c (ffffffff818075d5)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_evict_key
  - block/blk-crypto.c:blk_crypto_start_using_key
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In drivers/block/loop.c (ffffffff81bd107e)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
```
```
In drivers/md/md.c (ffffffff81e1cd28)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffffffff81e24566)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:__write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-zone.c (0)
Location: include/linux/blkdev.h:835
Inline: True
```
```
In drivers/md/dm.c (ffffffff81e2f3cb)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-table.c (ffffffff81e31d45)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_nowait_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_rotational
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_not_poll_capable
  - drivers/md/dm-table.c:device_intersect_crypto_capabilities
  - drivers/md/dm-table.c:device_is_rq_stackable
  - drivers/md/dm-table.c:dm_set_device_limits
```
```
In drivers/md/dm-io.c (ffffffff81e3ac8a)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
```
```
In drivers/md/dm-kcopyd.c (ffffffff81e3cbec)
Location: include/linux/blkdev.h:835
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffff800010235eb4)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffff800010328d60)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/buffer.c (ffff8000103da1b8)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffff8000103e00f4)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffff8000103e4c38)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffff80001040785c)
Location: include/linux/blkdev.h:898
Inline: True
```
```
In fs/iomap/direct-io.c (ffff80001042c978)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/ioctl.c (ffff80001048bc3c)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffff8000104bb850)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/file.c (ffff8000104eb32c)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffff8000104ed82c)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-flush.c (ffff8000105e6dfc)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-settings.c (ffff8000105e821c)
Location: include/linux/blkdev.h:898
Inline: True
```
```
In block/blk-lib.c (ffff8000105ecc34)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffff8000105f893c)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partition-generic.c (ffff8000105fd8f8)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/partitions/atari.c (ffff8000105ffa34)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffff800010604900)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffff800010606808)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffff80001061c44c)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffff800010620408)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/block/loop.c (ffff800010922990)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/dax/super.c (ffff8000109632c0)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/md.c (ffff800010af19c8)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffff800010af8804)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-table.c (ffff800010b04d28)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_requires_stable_pages
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_nonrot
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_matches_zone_sectors
  - drivers/md/dm-table.c:device_is_zoned_model
  - drivers/md/dm-table.c:device_is_rq_based
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffff800010b0a21c)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0bcb0)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (c0472310)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (c05400e4)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/buffer.c (c05b36dc)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
```
```
In fs/block_dev.c (c05b8f50)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (c05bcaf4)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (c05f555c)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
```
```
In fs/ext4/ioctl.c (c064d598)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (c067efb4)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/file.c (c06a90f8)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (c06ab618)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-flush.c (c0793b24)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-settings.c (c0794e08)
Location: include/linux/blkdev.h:898
Inline: True
```
```
In block/blk-lib.c (c0799148)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (c07a3c1c)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partition-generic.c (c07a87ec)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/partitions/atari.c (c07aace0)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (c07afb68)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (c07b1808)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:last_lba
```
```
In block/blk-zoned.c (c07c7eb4)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/block/loop.c (c0a06274)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/dax/super.c (c0a3a6bc)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/md.c (c0bd2f28)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (c0bd8928)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-table.c (c0be3cd0)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_requires_stable_pages
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_nonrot
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_matches_zone_sectors
  - drivers/md/dm-table.c:device_is_zoned_model
  - drivers/md/dm-table.c:device_is_rq_based
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (c0be86bc)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (c0be972c)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (c0000000002c1dc8)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (c000000000400178)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/buffer.c (c0000000004df1a0)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (c0000000004e5c78)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (c0000000004eaef8)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (c000000000513140)
Location: include/linux/blkdev.h:898
Inline: True
```
```
In fs/iomap/direct-io.c (c00000000053e018)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/ioctl.c (c0000000005b2580)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (c0000000005f174c)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/file.c (c00000000062960c)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (c00000000062c698)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-flush.c (c00000000077b6b8)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-settings.c (c00000000077ce00)
Location: include/linux/blkdev.h:898
Inline: True
```
```
In block/blk-lib.c (c0000000007825fc)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (c000000000790d08)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partition-generic.c (c0000000007972d4)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/partitions/atari.c (c000000000799e00)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (c0000000007a0690)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (c0000000007a2f30)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:find_valid_gpt
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (c0000000007badc8)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (c0000000007bfb54)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/block/loop.c (c0000000009c82ac)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/dax/super.c (c000000000a19ad0)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/md.c (c000000000bddf9c)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (c000000000be4818)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-table.c (c000000000bf49f8)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_requires_stable_pages
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_nonrot
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_matches_zone_sectors
  - drivers/md/dm-table.c:device_is_zoned_model
  - drivers/md/dm-table.c:device_is_rq_based
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (c000000000bfbc58)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (c000000000bfd8d0)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffe00018d38e)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffe000228ada)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/buffer.c (ffffffe000292fcc)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffe000296ec4)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffe00029a7f0)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffe0002b2480)
Location: include/linux/blkdev.h:898
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffe0002c9d56)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/ioctl.c (ffffffe000311ff2)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffe000337b84)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/file.c (ffffffe00035ba74)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffe00035dde4)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-flush.c (ffffffe000427b70)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-settings.c (ffffffe000428ee2)
Location: include/linux/blkdev.h:898
Inline: True
```
```
In block/blk-lib.c (ffffffe00042c6d0)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffe000435510)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partition-generic.c (ffffffe000439414)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/partitions/atari.c (ffffffe00043afd4)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffe00043f8b0)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffe000441730)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/blk-zoned.c (ffffffe000452af2)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/block/loop.c (ffffffe0005a168a)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/dax/super.c (ffffffe0005d09f4)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/md.c (ffffffe0006e572c)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffffffe0006e9808)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-table.c (ffffffe0006f3e30)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_requires_stable_pages
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_nonrot
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_matches_zone_sectors
  - drivers/md/dm-table.c:device_is_zoned_model
  - drivers/md/dm-table.c:device_is_rq_based
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffe0006f8252)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffffffe0006f9256)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff811b0310)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff81285aa1)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/buffer.c (ffffffff81319e06)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8131e4b7)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffff81321da8)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8133f8c0)
Location: include/linux/blkdev.h:898
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8135e09b)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/ioctl.c (ffffffff813aea32)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813daa4e)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/file.c (ffffffff814032bc)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff8140521d)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-flush.c (ffffffff814e1463)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-settings.c (ffffffff814e24e5)
Location: include/linux/blkdev.h:898
Inline: True
```
```
In block/blk-lib.c (ffffffff814e661e)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814f0323)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partition-generic.c (ffffffff814f3f26)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/partitions/atari.c (ffffffff814f6462)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff814fb0c6)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814fcd32)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff8150d7a6)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff81510f64)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/block/loop.c (ffffffff816f28f3)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/dax/super.c (ffffffff81717cdf)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/md.c (ffffffff818430ae)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffffffff81848b8d)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-table.c (ffffffff818540ba)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_requires_stable_pages
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_nonrot
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_matches_zone_sectors
  - drivers/md/dm-table.c:device_is_zoned_model
  - drivers/md/dm-table.c:device_is_rq_based
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff8185890b)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81859aa4)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff811a3160)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff81277911)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/buffer.c (ffffffff8130a9a6)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8130f057)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffff81312948)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff81330580)
Location: include/linux/blkdev.h:898
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8134ed3b)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/ioctl.c (ffffffff8139f4c2)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813cb4ce)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/file.c (ffffffff813f3d3c)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff813f5c9d)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-flush.c (ffffffff814d1df3)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-settings.c (ffffffff814d2e75)
Location: include/linux/blkdev.h:898
Inline: True
```
```
In block/blk-lib.c (ffffffff814d6b8e)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814e0863)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partition-generic.c (ffffffff814e4436)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/partitions/atari.c (ffffffff814e6972)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff814eb5d6)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814ed242)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff814fdbd6)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff81501284)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/block/loop.c (ffffffff816cc9f3)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/dax/super.c (ffffffff816f020f)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/md.c (ffffffff8180a70e)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffffffff818101ed)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-table.c (ffffffff8181b6ca)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_requires_stable_pages
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_nonrot
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_matches_zone_sectors
  - drivers/md/dm-table.c:device_is_zoned_model
  - drivers/md/dm-table.c:device_is_rq_based
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff8181ff1b)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff818210b4)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff811ae0e0)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff812838b1)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/buffer.c (ffffffff813178d6)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8131bf87)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffff8131f878)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8133d390)
Location: include/linux/blkdev.h:898
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8135bb6b)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/ioctl.c (ffffffff813ac292)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813d7eee)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/file.c (ffffffff8140063c)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff8140259d)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-flush.c (ffffffff814dd4f3)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-settings.c (ffffffff814de575)
Location: include/linux/blkdev.h:898
Inline: True
```
```
In block/blk-lib.c (ffffffff814e26ae)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814ec3b3)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partition-generic.c (ffffffff814effb6)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/partitions/atari.c (ffffffff814f24f2)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff814f7156)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814f8dc2)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff81509836)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff8150cff4)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/block/loop.c (ffffffff8171ffd3)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/dax/super.c (ffffffff81756aaf)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/md.c (ffffffff818926de)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffffffff818981bd)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-table.c (ffffffff818a36ea)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_requires_stable_pages
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_nonrot
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_matches_zone_sectors
  - drivers/md/dm-table.c:device_is_zoned_model
  - drivers/md/dm-table.c:device_is_rq_based
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff818a7f3b)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff818a90d4)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In kernel/trace/blktrace.c (ffffffff811bbfb0)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:blk_trace_ioctl
```
```
In mm/swapfile.c (ffffffff812935c2)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/buffer.c (ffffffff813294d1)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8132e097)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffff81331598)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff81350f80)
Location: include/linux/blkdev.h:898
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8136f2bb)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/ioctl.c (ffffffff813c0c32)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813ed18e)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/file.c (ffffffff8141626c)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff8141856d)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-flush.c (ffffffff814f6353)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-settings.c (ffffffff814f73d5)
Location: include/linux/blkdev.h:898
Inline: True
```
```
In block/blk-lib.c (ffffffff814fb52e)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff815053c3)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partition-generic.c (ffffffff81509046)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/partitions/atari.c (ffffffff8150b552)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff815101b6)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff81511e22)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff81522ea6)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff815266d4)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/block/loop.c (ffffffff8173b393)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/dax/super.c (ffffffff81771f0f)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/md.c (ffffffff818ae2bb)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/md-bitmap.c (ffffffff818b43d8)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-table.c (ffffffff818bf92a)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_requires_stable_pages
  - drivers/md/dm-table.c:device_not_secure_erase_capable
  - drivers/md/dm-table.c:device_not_discard_capable
  - drivers/md/dm-table.c:device_not_write_zeroes_capable
  - drivers/md/dm-table.c:device_not_write_same_capable
  - drivers/md/dm-table.c:device_is_not_random
  - drivers/md/dm-table.c:device_is_nonrot
  - drivers/md/dm-table.c:device_flush_capable
  - drivers/md/dm-table.c:device_matches_zone_sectors
  - drivers/md/dm-table.c:device_is_zoned_model
  - drivers/md/dm-table.c:device_is_rq_based
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-io.c (ffffffff818c417b)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff818c54e4)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
</details>
</li>
</ul>

## Differences

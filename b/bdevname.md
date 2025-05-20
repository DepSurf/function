# Function: <code>bdevname</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff813cd1d0)
Location: block/partition-generic.c:46
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/super.c:mount_bdev
  - fs/buffer.c:do_thaw_one
  - fs/buffer.c:__find_get_block_slow
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_table_any_congested
```
**Symbols:**

```
ffffffff813cd1d0-ffffffff813cd1f7: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81411610)
Location: block/partition-generic.c:47
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
ffffffff81411610-ffffffff81411634: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff8142c9a0)
Location: block/partition-generic.c:47
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
ffffffff8142c9a0-ffffffff8142c9c4: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81439cb0)
Location: block/partition-generic.c:46
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
ffffffff81439cb0-ffffffff81439cd4: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81465cd0)
Location: block/partition-generic.c:47
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
ffffffff81465cd0-ffffffff81465cf4: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814996a0)
Location: block/partition-generic.c:47
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_no_partial_completion
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
ffffffff814996a0-ffffffff814996c4: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814b3900)
Location: block/partition-generic.c:47
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_no_partial_completion
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
ffffffff814b3900-ffffffff814b3924: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814e1e90)
Location: block/partition-generic.c:47
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_no_partial_completion
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
ffffffff814e1e90-ffffffff814e1eb4: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814fb250)
Location: block/partition-generic.c:47
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_no_partial_completion
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
ffffffff814fb250-ffffffff814fb274: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8155a120)
Location: block/genhd.c:89
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:bdev_write_inode
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/blk-settings.c:disk_stack_limits
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_no_partial_completion
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
ffffffff8155a120-ffffffff8155a175: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81576990)
Location: block/genhd.c:106
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:bdev_write_inode
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/blk-settings.c:disk_stack_limits
  - block/blk-lib.c:__blkdev_issue_discard
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
ffffffff81576990-ffffffff815769e2: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8157e290)
Location: block/genhd.c:103
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/bio.c:bio_devname
  - block/blk-settings.c:disk_stack_limits
  - block/blk-lib.c:__blkdev_issue_discard
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
ffffffff8157e290-ffffffff8157e2e2: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:107
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/bdev.c:blkdev_flush_mapping
  - block/bio.c:bio_devname
  - block/blk-lib.c:__blkdev_issue_discard
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
ffffffff81cd8878-ffffffff81cd8890: bdevname.cold (STB_LOCAL)
ffffffff815e27b0-ffffffff815e28ab: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:111
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/bdev.c:blkdev_flush_mapping
  - block/blk-lib.c:__blkdev_issue_discard
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff81e8c310-ffffffff81e8c328: bdevname.cold (STB_LOCAL)
ffffffff81691480-ffffffff816915aa: bdevname (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffff8000105fd218)
Location: block/partition-generic.c:47
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_no_partial_completion
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
ffff8000105fd218-ffff8000105fd254: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (c07a8148)
Location: block/partition-generic.c:47
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_no_partial_completion
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
c07a8148-c07a8174: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (c000000000796a00)
Location: block/partition-generic.c:47
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_no_partial_completion
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
c000000000796a00-c000000000796a24: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffe000438e64)
Location: block/partition-generic.c:47
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_no_partial_completion
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
ffffffe000438e64-ffffffe000438e9c: bdevname (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814f3830)
Location: block/partition-generic.c:47
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_no_partial_completion
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
ffffffff814f3830-ffffffff814f3854: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814e3d40)
Location: block/partition-generic.c:47
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_no_partial_completion
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
ffffffff814e3d40-ffffffff814e3d64: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814ef8c0)
Location: block/partition-generic.c:47
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_no_partial_completion
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
ffffffff814ef8c0-ffffffff814ef8e4: bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *bdevname(struct block_device *bdev, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81508950)
Location: block/partition-generic.c:47
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:device_no_partial_completion
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:dm_set_device_limits
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
  - drivers/md/dm-table.c:device_area_is_invalid
```
**Symbols:**

```
ffffffff81508950-ffffffff81508974: bdevname (STB_GLOBAL)
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

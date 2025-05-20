# Function: <code>filemap_invalidate_lock</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (0)
Location: include/linux/fs.h:829
Inline: True
```
```
In fs/ext4/extents.c (ffffffff8144d3d8)
Location: include/linux/fs.h:829
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff8145381c)
Location: include/linux/fs.h:829
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff8145f3cb)
Location: include/linux/fs.h:829
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8146bdaa)
Location: include/linux/fs.h:829
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff8146d536)
Location: include/linux/fs.h:829
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/fuse/dir.c (ffffffff814ed380)
Location: include/linux/fs.h:829
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff814f2690)
Location: include/linux/fs.h:829
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff814fb244)
Location: include/linux/fs.h:829
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_break_layouts
```
```
In block/fops.c (ffffffff815c5520)
Location: include/linux/fs.h:829
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
```
```
In block/ioctl.c (ffffffff815e1f98)
Location: include/linux/fs.h:829
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
```
In block/blk-zoned.c (ffffffff81604d05)
Location: include/linux/fs.h:829
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
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
In mm/secretmem.c (ffffffff813e33d3)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_setattr
```
```
In fs/open.c (0)
Location: include/linux/fs.h:784
Inline: True
```
```
In fs/ext4/extents.c (ffffffff814c9eb5)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff814d13c3)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff814dc3a9)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff814ebe45)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff814eddff)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/fuse/dir.c (ffffffff8157c1e0)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81582098)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff8158b733)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_break_layouts
```
```
In block/fops.c (ffffffff8166ff8c)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
```
```
In block/ioctl.c (ffffffff81690a03)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/blk-zoned.c (ffffffff816b84ee)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
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
In mm/secretmem.c (ffffffff8146ad63)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_setattr
```
```
In fs/open.c (0)
Location: include/linux/fs.h:799
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8151bfa9)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
```
```
In fs/ext4/extents.c (ffffffff81562549)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff81569eeb)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff81575359)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff81585b9e)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff81587cc6)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/fuse/dir.c (ffffffff81621bf0)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81627e35)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff81631f93)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_break_layouts
```
```
In block/fops.c (ffffffff8172b4ec)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
```
```
In block/ioctl.c (ffffffff8174f5e1)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/blk-zoned.c (ffffffff817789be)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
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
In mm/secretmem.c (ffffffff8149fbf3)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_setattr
```
```
In fs/open.c (0)
Location: include/linux/fs.h:814
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff815541e6)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
```
```
In fs/ext4/extents.c (ffffffff8159a28d)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff815a1ce2)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff815acf8a)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff815bc29c)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff815be546)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/fuse/dir.c (ffffffff8165a049)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81660211)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff8166a1d3)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_break_layouts
```
```
In block/fops.c (ffffffff81768845)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
```
```
In block/ioctl.c (ffffffff8178b522)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/blk-zoned.c (ffffffff817b8582)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
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
In mm/secretmem.c (ffffffff814cf343)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_setattr
```
```
In fs/open.c (0)
Location: include/linux/fs.h:847
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8158a1c2)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
```
```
In fs/ext4/extents.c (ffffffff815d30dd)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff815dabac)
Location: include/linux/fs.h:847
Inline: True
```
```
In fs/ext4/inline.c (ffffffff815e5d3a)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff815f507c)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff815f72ff)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/fuse/dir.c (ffffffff81693ccf)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff8169a071)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff816a4513)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_break_layouts
```
```
In block/fops.c (ffffffff817aa6e4)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
```
```
In block/ioctl.c (ffffffff817cdc82)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/blk-zoned.c (ffffffff817fd069)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
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

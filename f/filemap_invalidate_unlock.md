# Function: <code>filemap_invalidate_unlock</code>

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
Location: include/linux/fs.h:834
Inline: True
```
```
In fs/ext4/extents.c (ffffffff8144d428)
Location: include/linux/fs.h:834
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff8145383d)
Location: include/linux/fs.h:834
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff8145f3eb)
Location: include/linux/fs.h:834
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8146be0e)
Location: include/linux/fs.h:834
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff8146d818)
Location: include/linux/fs.h:834
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/fuse/dir.c (ffffffff814ed32b)
Location: include/linux/fs.h:834
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff814f265c)
Location: include/linux/fs.h:834
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff814fb232)
Location: include/linux/fs.h:834
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_break_layouts
```
```
In block/fops.c (ffffffff815c5583)
Location: include/linux/fs.h:834
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
```
```
In block/ioctl.c (ffffffff815e1fe2)
Location: include/linux/fs.h:834
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
```
In block/blk-zoned.c (ffffffff81604d84)
Location: include/linux/fs.h:834
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
In mm/secretmem.c (ffffffff813e3406)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_setattr
```
```
In fs/open.c (0)
Location: include/linux/fs.h:789
Inline: True
```
```
In fs/ext4/extents.c (ffffffff814c9eda)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff814d13e3)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff814dc3ca)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff814ebea5)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff814ee0d9)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/fuse/dir.c (ffffffff8157c2d9)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81581f37)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff8158b721)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_break_layouts
```
```
In block/fops.c (ffffffff8166fff3)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
```
```
In block/ioctl.c (ffffffff81690a4b)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/blk-zoned.c (ffffffff816b8561)
Location: include/linux/fs.h:789
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
In mm/secretmem.c (ffffffff8146ad96)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_setattr
```
```
In fs/open.c (0)
Location: include/linux/fs.h:804
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8151c138)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
```
```
In fs/ext4/extents.c (ffffffff8156256c)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff81569f0b)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff8157537a)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff81585c02)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff81587fbb)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/fuse/dir.c (ffffffff81621ce9)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81627e18)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff81631f81)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_break_layouts
```
```
In block/fops.c (ffffffff8172b553)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
```
```
In block/ioctl.c (ffffffff8174f628)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/blk-zoned.c (ffffffff81778a31)
Location: include/linux/fs.h:804
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
In mm/secretmem.c (ffffffff8149fc26)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_setattr
```
```
In fs/open.c (0)
Location: include/linux/fs.h:819
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff81554373)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
```
```
In fs/ext4/extents.c (ffffffff8159a2b0)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff815a1d02)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff815acfab)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff815bc347)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff815be83f)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/fuse/dir.c (ffffffff8165a142)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff816601f4)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff8166a1c1)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_break_layouts
```
```
In block/fops.c (ffffffff817688b1)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
```
```
In block/ioctl.c (ffffffff8178b565)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/blk-zoned.c (ffffffff817b85ee)
Location: include/linux/fs.h:819
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
In mm/secretmem.c (ffffffff814cf376)
Location: include/linux/fs.h:852
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_setattr
```
```
In fs/open.c (0)
Location: include/linux/fs.h:852
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8158a52e)
Location: include/linux/fs.h:852
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
```
```
In fs/ext4/extents.c (ffffffff815d3100)
Location: include/linux/fs.h:852
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff815dabcc)
Location: include/linux/fs.h:852
Inline: True
```
```
In fs/ext4/inline.c (ffffffff815e5d5b)
Location: include/linux/fs.h:852
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff815f5127)
Location: include/linux/fs.h:852
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff815f75e8)
Location: include/linux/fs.h:852
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/fuse/dir.c (ffffffff81693dd4)
Location: include/linux/fs.h:852
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff8169a054)
Location: include/linux/fs.h:852
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff816a4501)
Location: include/linux/fs.h:852
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_break_layouts
```
```
In block/fops.c (ffffffff817aa72c)
Location: include/linux/fs.h:852
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
```
```
In block/ioctl.c (ffffffff817cdcc5)
Location: include/linux/fs.h:852
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/blk-zoned.c (ffffffff817fd0d9)
Location: include/linux/fs.h:852
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

# Function: <code>filemap_write_and_wait_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118ea30)
Location: mm/filemap.c:479
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:__generic_file_write_iter
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/dax.c:dax_do_io
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff8118ea30-ffffffff8118ea91: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a25e0)
Location: mm/filemap.c:559
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_fsync_common
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff811a25e0-ffffffff811a2668: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b2420)
Location: mm/filemap.c:524
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/read_write.c:vfs_clone_file_prep_inodes
  - fs/read_write.c:vfs_clone_file_prep_inodes
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_rw
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_fsync_common
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff811b2420-ffffffff811b24a8: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b9090)
Location: mm/filemap.c:555
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/read_write.c:vfs_clone_file_prep_inodes
  - fs/read_write.c:vfs_clone_file_prep_inodes
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_rw
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_fsync_common
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff811b9090-ffffffff811b9124: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cd9a0)
Location: mm/filemap.c:650
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/read_write.c:vfs_clone_file_prep_inodes
  - fs/read_write.c:vfs_clone_file_prep_inodes
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_rw
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff811cd9a0-ffffffff811cda27: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ef4d0)
Location: mm/filemap.c:650
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/read_write.c:vfs_clone_file_prep_inodes
  - fs/read_write.c:vfs_clone_file_prep_inodes
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_rw
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff811ef4d0-ffffffff811ef557: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81200cd0)
Location: mm/filemap.c:627
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_rw
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fuse/file.c:fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81200cd0-ffffffff81200d57: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812188f0)
Location: mm/filemap.c:666
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff812188f0-ffffffff8121897a: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81226180)
Location: mm/filemap.c:675
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81226180-ffffffff81226226: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81251220)
Location: mm/filemap.c:648
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/swapfile.c:__do_sys_swapon
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/ioctl.c:fiemap_prep
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_vma_close
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff81251220-ffffffff812512be: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125c8b0)
Location: mm/filemap.c:649
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/swapfile.c:__do_sys_swapon
  - fs/ioctl.c:fiemap_prep
  - fs/remap_range.c:generic_remap_file_range_prep
  - fs/remap_range.c:generic_remap_file_range_prep
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_vma_close
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff8125c8b0-ffffffff8125c94e: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81261690)
Location: mm/filemap.c:680
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/swapfile.c:__do_sys_swapon
  - fs/ioctl.c:fiemap_prep
  - fs/remap_range.c:generic_remap_file_range_prep
  - fs/remap_range.c:generic_remap_file_range_prep
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:bdev_disk_changed
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_vma_close
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff81261690-ffffffff8126170c: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81299990)
Location: mm/filemap.c:698
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/swapfile.c:__do_sys_swapon
  - fs/ioctl.c:fiemap_prep
  - fs/remap_range.c:generic_remap_file_range_prep
  - fs/remap_range.c:generic_remap_file_range_prep
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_vma_close
  - fs/fuse/file.c:fuse_cache_write_iter
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:freeze_bdev
  - block/bdev.c:set_blocksize
```
**Symbols:**

```
ffffffff81299990-ffffffff81299a60: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f56a0)
Location: mm/filemap.c:667
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/swapfile.c:__do_sys_swapon
  - fs/ioctl.c:fiemap_prep
  - fs/remap_range.c:generic_remap_file_range_prep
  - fs/remap_range.c:generic_remap_file_range_prep
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_cache_write_iter
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:freeze_bdev
  - block/bdev.c:sync_blockdev_range
  - block/bdev.c:set_blocksize
  - block/fops.c:blkdev_read_iter
```
**Symbols:**

```
ffffffff812f56a0-ffffffff812f5734: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff81360c0f)
Location: mm/filemap.c:665
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/swapfile.c:__do_sys_swapon
  - fs/ioctl.c:fiemap_prep
  - fs/remap_range.c:__generic_remap_file_range_prep
  - fs/remap_range.c:__generic_remap_file_range_prep
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_cache_write_iter
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:freeze_bdev
  - block/bdev.c:sync_blockdev_range
  - block/bdev.c:set_blocksize
  - block/fops.c:blkdev_read_iter
```
**Symbols:**

```
ffffffff8135f530-ffffffff8135f5da: filemap_write_and_wait_range.part.0 (STB_LOCAL)
ffffffff8135f840-ffffffff8135f902: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff813922d7)
Location: mm/filemap.c:672
Inline: True
Inline callers:
  - mm/filemap.c:kiocb_invalidate_pages
  - mm/filemap.c:kiocb_write_and_wait
Direct callers:
  - mm/filemap.c:kiocb_invalidate_pages
  - mm/filemap.c:kiocb_write_and_wait
  - mm/swapfile.c:__do_sys_swapon
  - fs/ioctl.c:fiemap_prep
  - fs/libfs.c:direct_write_fallback
  - fs/remap_range.c:__generic_remap_file_range_prep
  - fs/remap_range.c:__generic_remap_file_range_prep
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:freeze_bdev
  - block/bdev.c:sync_blockdev_range
  - block/bdev.c:set_blocksize
```
**Symbols:**

```
ffffffff81390690-ffffffff81390737: filemap_write_and_wait_range.part.0 (STB_LOCAL)
ffffffff81390820-ffffffff813908df: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff813ba367)
Location: mm/filemap.c:667
Inline: True
Inline callers:
  - mm/filemap.c:kiocb_invalidate_pages
  - mm/filemap.c:kiocb_write_and_wait
Direct callers:
  - mm/filemap.c:kiocb_invalidate_pages
  - mm/filemap.c:kiocb_write_and_wait
  - mm/swapfile.c:__do_sys_swapon
  - fs/ioctl.c:fiemap_prep
  - fs/libfs.c:direct_write_fallback
  - fs/remap_range.c:__generic_remap_file_range_prep
  - fs/remap_range.c:__generic_remap_file_range_prep
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_io
  - block/bdev.c:bdev_mark_dead
  - block/bdev.c:bdev_release
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:bdev_freeze
  - block/bdev.c:sync_blockdev_range
  - block/bdev.c:set_blocksize
```
**Symbols:**

```
ffffffff813ba0d0-ffffffff813ba177: filemap_write_and_wait_range.part.0 (STB_LOCAL)
ffffffff813ba4a0-ffffffff813ba55f: filemap_write_and_wait_range (STB_GLOBAL)
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
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b3428)
Location: mm/filemap.c:675
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffff8000102b3428-ffff8000102b34fc: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e0618)
Location: mm/filemap.c:675
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
c04e0618-c04e06bc: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000369f80)
Location: mm/filemap.c:675
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
c000000000369f80-c00000000036a06c: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d8b40)
Location: mm/filemap.c:675
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffe0001d8b40-ffffffe0001d8c16: filemap_write_and_wait_range (STB_GLOBAL)
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
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121e7d0)
Location: mm/filemap.c:675
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8121e7d0-ffffffff8121e876: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81211990)
Location: mm/filemap.c:675
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81211990-ffffffff81211a36: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121c570)
Location: mm/filemap.c:675
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8121c570-ffffffff8121c616: filemap_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122b600)
Location: mm/filemap.c:675
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8122b600-ffffffff8122b6a6: filemap_write_and_wait_range (STB_GLOBAL)
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

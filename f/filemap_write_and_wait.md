# Function: <code>filemap_write_and_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118e980)
Location: mm/filemap.c:444
Inline: True
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:fuse_vma_close
```
**Symbols:**

```
ffffffff8118e980-ffffffff8118e9ec: filemap_write_and_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a2510)
Location: mm/filemap.c:523
Inline: True
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/iomap.c:iomap_fiemap
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:fuse_vma_close
```
**Symbols:**

```
ffffffff811a2510-ffffffff811a2598: filemap_write_and_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b2350)
Location: mm/filemap.c:488
Inline: True
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/iomap.c:iomap_fiemap
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:fuse_vma_close
```
**Symbols:**

```
ffffffff811b2350-ffffffff811b23d8: filemap_write_and_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b8fd0)
Location: mm/filemap.c:516
Inline: True
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/iomap.c:iomap_fiemap
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:fuse_vma_close
```
**Symbols:**

```
ffffffff811b8fd0-ffffffff811b9047: filemap_write_and_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cd8d0)
Location: mm/filemap.c:612
Inline: True
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/iomap.c:iomap_fiemap
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:fuse_vma_close
```
**Symbols:**

```
ffffffff811cd8d0-ffffffff811cd951: filemap_write_and_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ef400)
Location: mm/filemap.c:612
Inline: True
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/iomap.c:iomap_bmap
  - fs/iomap.c:iomap_fiemap
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:fuse_vma_close
```
**Symbols:**

```
ffffffff811ef400-ffffffff811ef481: filemap_write_and_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81200c00)
Location: mm/filemap.c:589
Inline: True
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/iomap.c:iomap_bmap
  - fs/iomap.c:iomap_fiemap
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:fuse_vma_close
```
**Symbols:**

```
ffffffff81200c00-ffffffff81200c81: filemap_write_and_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81218820)
Location: mm/filemap.c:626
Inline: True
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:fuse_vma_close
```
**Symbols:**

```
ffffffff81218820-ffffffff812188a4: filemap_write_and_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812260a0)
Location: mm/filemap.c:635
Inline: True
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:fuse_vma_close
```
**Symbols:**

```
ffffffff812260a0-ffffffff81226140: filemap_write_and_wait (STB_GLOBAL)
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
In mm/swapfile.c (ffffffff812bf6c3)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/ioctl.c (ffffffff8132b24f)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - fs/ioctl.c:fiemap_prep
```
```
In fs/block_dev.c (ffffffff813607a3)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
```
```
In fs/verity/enable.c (ffffffff8139672d)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/iomap/fiemap.c (ffffffff813add55)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/ext4/inode.c (ffffffff813fffc8)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff814012d5)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/verity.c (ffffffff8143c21e)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ecryptfs/file.c (ffffffff8145f26e)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_flush
```
```
In fs/ecryptfs/main.c (ffffffff81461ebe)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
```
In fs/fuse/file.c (ffffffff81475aa5)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_vma_close
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
In mm/swapfile.c (ffffffff812cb280)
Location: include/linux/fs.h:2654
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/ioctl.c (ffffffff8133680f)
Location: include/linux/fs.h:2654
Inline: True
Inline callers:
  - fs/ioctl.c:fiemap_prep
```
```
In fs/block_dev.c (ffffffff8136dcd8)
Location: include/linux/fs.h:2654
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
```
```
In fs/verity/enable.c (ffffffff813a844d)
Location: include/linux/fs.h:2654
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/iomap/fiemap.c (ffffffff813bf3c5)
Location: include/linux/fs.h:2654
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/ext4/inode.c (ffffffff81412738)
Location: include/linux/fs.h:2654
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81413b95)
Location: include/linux/fs.h:2654
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/verity.c (ffffffff81458516)
Location: include/linux/fs.h:2654
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ecryptfs/file.c (ffffffff8147af0e)
Location: include/linux/fs.h:2654
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_flush
```
```
In fs/ecryptfs/main.c (ffffffff8147da2e)
Location: include/linux/fs.h:2654
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
```
In fs/fuse/file.c (ffffffff81490725)
Location: include/linux/fs.h:2654
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_vma_close
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
In mm/swapfile.c (ffffffff812d1e16)
Location: include/linux/fs.h:2890
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/ioctl.c (ffffffff8133cb4c)
Location: include/linux/fs.h:2890
Inline: True
Inline callers:
  - fs/ioctl.c:fiemap_prep
```
```
In fs/block_dev.c (ffffffff8137467e)
Location: include/linux/fs.h:2890
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:bdev_disk_changed
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
```
```
In fs/verity/enable.c (ffffffff813af4a6)
Location: include/linux/fs.h:2890
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/iomap/fiemap.c (ffffffff813c6505)
Location: include/linux/fs.h:2890
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/ext4/inode.c (ffffffff81418b98)
Location: include/linux/fs.h:2890
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81419e19)
Location: include/linux/fs.h:2890
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/verity.c (ffffffff8145deb8)
Location: include/linux/fs.h:2890
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ecryptfs/file.c (ffffffff8148094e)
Location: include/linux/fs.h:2890
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_flush
```
```
In fs/ecryptfs/main.c (ffffffff814835ee)
Location: include/linux/fs.h:2890
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
```
In fs/fuse/file.c (ffffffff81496155)
Location: include/linux/fs.h:2890
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_vma_close
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
In mm/swapfile.c (ffffffff813177ec)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/ioctl.c (ffffffff8138a84c)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/ioctl.c:fiemap_prep
```
```
In fs/verity/enable.c (ffffffff813ff056)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/iomap/fiemap.c (ffffffff814162b7)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/ext4/inode.c (ffffffff8146bdb7)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8146d009)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/verity.c (ffffffff814b33d7)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ecryptfs/file.c (ffffffff814d81ee)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_flush
```
```
In fs/ecryptfs/main.c (ffffffff814dad6e)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
```
In fs/fuse/file.c (ffffffff814edc15)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_vma_close
```
```
In block/bdev.c (ffffffff815c47b7)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:freeze_bdev
  - block/bdev.c:set_blocksize
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
In mm/swapfile.c (ffffffff813829d1)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/ioctl.c (ffffffff8140b9fd)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - fs/ioctl.c:fiemap_prep
```
```
In fs/verity/enable.c (ffffffff81472bf2)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/iomap/fiemap.c (ffffffff8148db77)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/ext4/inode.c (ffffffff814ebe52)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff814ec79f)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/verity.c (ffffffff8153bfbf)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ecryptfs/file.c (ffffffff815658de)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_flush
```
```
In fs/ecryptfs/main.c (ffffffff815686fa)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
```
In block/bdev.c (ffffffff8166ede7)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:freeze_bdev
  - block/bdev.c:set_blocksize
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
In mm/swapfile.c (ffffffff813fc735)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/ioctl.c (ffffffff814963cd)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - fs/ioctl.c:fiemap_prep
```
```
In fs/verity/enable.c (ffffffff81504949)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/iomap/fiemap.c (ffffffff81521357)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/ext4/inode.c (ffffffff81585bab)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8158651c)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/verity.c (ffffffff815da66f)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ecryptfs/file.c (ffffffff81608b5e)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_flush
```
```
In fs/ecryptfs/main.c (ffffffff8160c01a)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
```
In block/bdev.c (ffffffff8172a0ba)
Location: include/linux/pagemap.h:58
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:freeze_bdev
  - block/bdev.c:set_blocksize
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
In mm/swapfile.c (ffffffff8142fa3f)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/ioctl.c (ffffffff814cb2cd)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - fs/ioctl.c:fiemap_prep
```
```
In fs/iomap/fiemap.c (ffffffff81559397)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/ext4/inode.c (ffffffff815bc2a9)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
```
```
In fs/ext4/ioctl.c (ffffffff815bcc5c)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/verity.c (ffffffff81612442)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ecryptfs/file.c (ffffffff816409c1)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_flush
```
```
In fs/ecryptfs/main.c (ffffffff81643f0a)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
```
In block/bdev.c (ffffffff81766458)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:freeze_bdev
  - block/bdev.c:set_blocksize
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
In mm/swapfile.c (ffffffff814695cd)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/ioctl.c (ffffffff814fdb7d)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - fs/ioctl.c:fiemap_prep
```
```
In fs/iomap/fiemap.c (ffffffff8158fb27)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/ext4/inode.c (ffffffff815f5089)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
```
```
In fs/ext4/ioctl.c (ffffffff815f5a3a)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/verity.c (ffffffff8164b112)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ecryptfs/file.c (ffffffff81679f71)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_flush
```
```
In fs/ecryptfs/main.c (ffffffff8167d49a)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
```
In block/bdev.c (ffffffff817a83ec)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - block/bdev.c:bdev_mark_dead
  - block/bdev.c:bdev_release
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:bdev_freeze
  - block/bdev.c:set_blocksize
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
int filemap_write_and_wait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b32e8)
Location: mm/filemap.c:635
Inline: True
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:fuse_vma_close
```
**Symbols:**

```
ffff8000102b32e8-ffff8000102b33a8: filemap_write_and_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e0500)
Location: mm/filemap.c:635
Inline: True
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:fuse_vma_close
```
**Symbols:**

```
c04e0500-c04e05a4: filemap_write_and_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000369e40)
Location: mm/filemap.c:635
Inline: True
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:fuse_vma_close
```
**Symbols:**

```
c000000000369e40-c000000000369f2c: filemap_write_and_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d89fe)
Location: mm/filemap.c:635
Inline: True
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:fuse_vma_close
```
**Symbols:**

```
ffffffe0001d89fe-ffffffe0001d8ad2: filemap_write_and_wait (STB_GLOBAL)
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
int filemap_write_and_wait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121e6f0)
Location: mm/filemap.c:635
Inline: True
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:fuse_vma_close
```
**Symbols:**

```
ffffffff8121e6f0-ffffffff8121e790: filemap_write_and_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812118b0)
Location: mm/filemap.c:635
Inline: True
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:fuse_vma_close
```
**Symbols:**

```
ffffffff812118b0-ffffffff81211950: filemap_write_and_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121c490)
Location: mm/filemap.c:635
Inline: True
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:fuse_vma_close
```
**Symbols:**

```
ffffffff8121c490-ffffffff8121c530: filemap_write_and_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int filemap_write_and_wait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122b520)
Location: mm/filemap.c:635
Inline: True
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - fs/fuse/file.c:fuse_vma_close
```
**Symbols:**

```
ffffffff8122b520-ffffffff8122b5c0: filemap_write_and_wait (STB_GLOBAL)
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

# Function: <code>truncate_inode_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8119f4e0)
Location: mm/truncate.c:388
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
Direct callers:
  - fs/block_dev.c:kill_bdev
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/indirect.c:ext4_ind_direct_IO
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
**Symbols:**

```
ffffffff8119f4e0-ffffffff8119f4f7: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811b52c6)
Location: mm/truncate.c:399
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
Direct callers:
  - fs/block_dev.c:kill_bdev
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff811b5210-ffffffff811b5227: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811c58d6)
Location: mm/truncate.c:428
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
Direct callers:
  - fs/block_dev.c:kill_bdev
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff811c5820-ffffffff811c5837: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811cdbe6)
Location: mm/truncate.c:427
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
Direct callers:
  - fs/block_dev.c:kill_bdev
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff811cdb30-ffffffff811cdb47: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811e2f96)
Location: mm/truncate.c:480
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
Direct callers:
  - fs/block_dev.c:kill_bdev
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff811e2ee0-ffffffff811e2ef7: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812045f6)
Location: mm/truncate.c:476
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
Direct callers:
  - fs/block_dev.c:kill_bdev
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81204540-ffffffff81204557: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81216fb6)
Location: mm/truncate.c:473
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/block_dev.c:kill_bdev
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81216f00-ffffffff81216f17: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81226917)
Location: mm/truncate.c:474
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/block_dev.c:kill_bdev
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81226860-ffffffff81226877: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81234787)
Location: mm/truncate.c:474
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/block_dev.c:kill_bdev
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff812346d0-ffffffff812346e7: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81261d47)
Location: mm/truncate.c:474
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81261c90-ffffffff81261ca7: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8126c047)
Location: mm/truncate.c:474
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8126bf90-ffffffff8126bfa7: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81270f37)
Location: mm/truncate.c:422
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81270e90-ffffffff81270ea7: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812adf07)
Location: mm/truncate.c:423
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
```
**Symbols:**

```
ffffffff812ade50-ffffffff812ade67: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81308af6)
Location: mm/truncate.c:450
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
```
**Symbols:**

```
ffffffff81308a30-ffffffff81308a51: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81372906)
Location: mm/truncate.c:446
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
```
**Symbols:**

```
ffffffff81372820-ffffffff81372841: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813a4a66)
Location: mm/truncate.c:447
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
```
**Symbols:**

```
ffffffff813a4990-ffffffff813a49b1: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813ce5c6)
Location: mm/truncate.c:437
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
```
**Symbols:**

```
ffffffff813ce4f0-ffffffff813ce511: truncate_inode_pages (STB_GLOBAL)
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
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffff8000102c4db4)
Location: mm/truncate.c:474
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/block_dev.c:kill_bdev
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffff8000102c4c38-ffff8000102c4c70: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c04ef61c)
Location: mm/truncate.c:474
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/block_dev.c:kill_bdev
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
c04ef504-c04ef534: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c00000000037f510)
Location: mm/truncate.c:474
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/block_dev.c:kill_bdev
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
c00000000037f3c0-c00000000037f3d8: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffe0001e54b2)
Location: mm/truncate.c:474
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/block_dev.c:kill_bdev
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffe0001e53ac-ffffffe0001e53e0: truncate_inode_pages (STB_GLOBAL)
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
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122cdd7)
Location: mm/truncate.c:474
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/block_dev.c:kill_bdev
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8122cd20-ffffffff8122cd37: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8121fea7)
Location: mm/truncate.c:474
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/block_dev.c:kill_bdev
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8121fe00-ffffffff8121fe17: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122ab77)
Location: mm/truncate.c:474
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/block_dev.c:kill_bdev
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8122aac0-ffffffff8122aad7: truncate_inode_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages(struct address_space *mapping, loff_t lstart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81239f77)
Location: mm/truncate.c:474
Inline: True
Inline callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
Direct callers:
  - fs/block_dev.c:kill_bdev
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81239ed0-ffffffff81239ee7: truncate_inode_pages (STB_GLOBAL)
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

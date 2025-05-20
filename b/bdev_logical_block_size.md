# Function: <code>bdev_logical_block_size</code>

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
In fs/buffer.c (ffffffff81243c1b)
Location: include/linux/blkdev.h:1200
Inline: True
```
```
In fs/block_dev.c (ffffffff8124742f)
Location: include/linux/blkdev.h:1200
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:sb_min_blocksize
```
```
In fs/direct-io.c (ffffffff8124a15d)
Location: include/linux/blkdev.h:1200
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/ext4/super.c (ffffffff81322a00)
Location: include/linux/blkdev.h:1200
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In block/blk-core.c (ffffffff813b9e3e)
Location: include/linux/blkdev.h:1200
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-lib.c (ffffffff813c2996)
Location: include/linux/blkdev.h:1200
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
```
In block/ioctl.c (ffffffff813c94d4)
Location: include/linux/blkdev.h:1200
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partitions/msdos.c (ffffffff813d2925)
Location: include/linux/blkdev.h:1200
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff813d3989)
Location: include/linux/blkdev.h:1200
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
```
In block/compat_ioctl.c (ffffffff813e652f)
Location: include/linux/blkdev.h:1200
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/block/loop.c (ffffffff8156e0e2)
Location: include/linux/blkdev.h:1200
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/bitmap.c (ffffffff8169bb6b)
Location: include/linux/blkdev.h:1200
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_sb_page
  - drivers/md/bitmap.c:write_page
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
In fs/buffer.c (ffffffff8126c9cc)
Location: include/linux/blkdev.h:1229
Inline: True
```
```
In fs/block_dev.c (ffffffff81270633)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff81272c49)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff812868e9)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - fs/dax.c:__dax_zero_page_range
```
```
In fs/ext4/super.c (ffffffff812ed709)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In block/blk-core.c (ffffffff813fdc1f)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-lib.c (ffffffff8140650b)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
```
In block/ioctl.c (ffffffff8140d842)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partitions/atari.c (ffffffff81413b82)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8141844c)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff8141a15a)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff8142c7bb)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/block/loop.c (ffffffff815c39d2)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/bitmap.c (ffffffff816fea04)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
  - drivers/md/bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff8127fca6)
Location: include/linux/blkdev.h:1394
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81283f93)
Location: include/linux/blkdev.h:1394
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff8128674b)
Location: include/linux/blkdev.h:1394
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8129a879)
Location: include/linux/blkdev.h:1394
Inline: True
Inline callers:
  - fs/dax.c:__dax_zero_page_range
```
```
In fs/iomap.c (ffffffff812b0c52)
Location: include/linux/blkdev.h:1394
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
```
```
In fs/ext4/super.c (ffffffff81302fd8)
Location: include/linux/blkdev.h:1394
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In block/blk-core.c (ffffffff8141755e)
Location: include/linux/blkdev.h:1394
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-lib.c (ffffffff814209f6)
Location: include/linux/blkdev.h:1394
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814286d2)
Location: include/linux/blkdev.h:1394
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff8142f0b2)
Location: include/linux/blkdev.h:1394
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8143397c)
Location: include/linux/blkdev.h:1394
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff8143568a)
Location: include/linux/blkdev.h:1394
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff814465bb)
Location: include/linux/blkdev.h:1394
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/block/loop.c (ffffffff815f20b2)
Location: include/linux/blkdev.h:1394
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/bitmap.c (ffffffff8173065f)
Location: include/linux/blkdev.h:1394
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
  - drivers/md/bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff8128d256)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81291642)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff81293dcf)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff812a944d)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - fs/dax.c:__dax_zero_page_range
```
```
In fs/iomap.c (ffffffff812be058)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
```
```
In fs/ext4/super.c (ffffffff813389e3)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In block/blk-core.c (ffffffff814253bd)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-lib.c (ffffffff8142e966)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff81436a22)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff8143c2f2)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8144077f)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814421df)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff81454b48)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/block/loop.c (ffffffff816062c2)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/bitmap.c (ffffffff8174850c)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
  - drivers/md/bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff812afd96)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff812b4392)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff812b6d2f)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff812cca1d)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - fs/dax.c:__dax_zero_page_range
```
```
In fs/iomap.c (ffffffff812e1957)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
```
```
In fs/ext4/super.c (ffffffff8135cfc2)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In block/blk-lib.c (ffffffff81459e69)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814627b5)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff814683cb)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8146ce13)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff8146eb4f)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff814807de)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/block/loop.c (ffffffff8166e6c2)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffffffff817ba79c)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff812d7fe5)
Location: include/linux/blkdev.h:1487
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff812db9b8)
Location: include/linux/blkdev.h:1487
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff812df71f)
Location: include/linux/blkdev.h:1487
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff812f7125)
Location: include/linux/blkdev.h:1487
Inline: True
```
```
In fs/iomap.c (ffffffff8130e067)
Location: include/linux/blkdev.h:1487
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
```
```
In fs/ext4/super.c (ffffffff813865a9)
Location: include/linux/blkdev.h:1487
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In block/blk-lib.c (ffffffff8148d5bc)
Location: include/linux/blkdev.h:1487
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff8149627d)
Location: include/linux/blkdev.h:1487
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff8149c25b)
Location: include/linux/blkdev.h:1487
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff814a0cf6)
Location: include/linux/blkdev.h:1487
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814a2b1c)
Location: include/linux/blkdev.h:1487
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:find_valid_gpt
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff814b5317)
Location: include/linux/blkdev.h:1487
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/block/loop.c (ffffffff816aa1a2)
Location: include/linux/blkdev.h:1487
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffffffff81802752)
Location: include/linux/blkdev.h:1487
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff812ed055)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff812f10a8)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffff812f422f)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8130c1d5)
Location: include/linux/blkdev.h:1266
Inline: True
```
```
In fs/iomap.c (ffffffff813238cb)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff8139f0a9)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In block/blk-lib.c (ffffffff814a6e4c)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814b05c4)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff814b657b)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff814bb0b6)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814bccfe)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff814c8bd4)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/block/loop.c (ffffffff816cad92)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffffffff8182ea3b)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff8130e806)
Location: include/linux/blkdev.h:1280
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81312fac)
Location: include/linux/blkdev.h:1280
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffff81316948)
Location: include/linux/blkdev.h:1280
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff81333720)
Location: include/linux/blkdev.h:1280
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8134d7fb)
Location: include/linux/blkdev.h:1280
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff813c90be)
Location: include/linux/blkdev.h:1280
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-lib.c (ffffffff814d4d6c)
Location: include/linux/blkdev.h:1280
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814de4c7)
Location: include/linux/blkdev.h:1280
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff814e4abb)
Location: include/linux/blkdev.h:1280
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff814e971c)
Location: include/linux/blkdev.h:1280
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814eb38a)
Location: include/linux/blkdev.h:1280
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff814f781b)
Location: include/linux/blkdev.h:1280
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/block/loop.c (ffffffff81706362)
Location: include/linux/blkdev.h:1280
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffffffff81870f24)
Location: include/linux/blkdev.h:1280
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff81321826)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81325ed7)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffff813297c8)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff813472e0)
Location: include/linux/blkdev.h:1307
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff81365abb)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff813e246e)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-lib.c (ffffffff814ee05c)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814f7913)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff814fde7b)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff81502ae6)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff81504752)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff815154c1)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/block/loop.c (ffffffff8172cb13)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffffffff818a2d0d)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff8135be25)
Location: include/linux/blkdev.h:1341
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
```
```
In fs/block_dev.c (ffffffff8135f277)
Location: include/linux/blkdev.h:1341
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffff813635b1)
Location: include/linux/blkdev.h:1341
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813acf05)
Location: include/linux/blkdev.h:1341
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff8142e52a)
Location: include/linux/blkdev.h:1341
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-lib.c (ffffffff8154d9d2)
Location: include/linux/blkdev.h:1341
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff815588e1)
Location: include/linux/blkdev.h:1341
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/partitions/atari.c (ffffffff8155e5c9)
Location: include/linux/blkdev.h:1341
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (0)
Location: include/linux/blkdev.h:1341
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/efi.c (ffffffff815651a1)
Location: include/linux/blkdev.h:1341
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:alloc_read_gpt_header
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In drivers/block/loop.c (ffffffff817e9d0e)
Location: include/linux/blkdev.h:1341
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffffffff81972838)
Location: include/linux/blkdev.h:1341
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff8136a3c5)
Location: include/linux/blkdev.h:1442
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
```
```
In fs/block_dev.c (ffffffff8136e3ee)
Location: include/linux/blkdev.h:1442
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff81370861)
Location: include/linux/blkdev.h:1442
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813be5f5)
Location: include/linux/blkdev.h:1442
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff81447207)
Location: include/linux/blkdev.h:1442
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-lib.c (ffffffff81569b4f)
Location: include/linux/blkdev.h:1442
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff81574ee5)
Location: include/linux/blkdev.h:1442
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/partitions/atari.c (ffffffff8157a209)
Location: include/linux/blkdev.h:1442
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (0)
Location: include/linux/blkdev.h:1442
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/efi.c (ffffffff8158029e)
Location: include/linux/blkdev.h:1442
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:alloc_read_gpt_header
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In drivers/block/loop.c (ffffffff817fe761)
Location: include/linux/blkdev.h:1442
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffffffff81977754)
Location: include/linux/blkdev.h:1442
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff81371026)
Location: include/linux/blkdev.h:1427
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81374cfb)
Location: include/linux/blkdev.h:1427
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff81377130)
Location: include/linux/blkdev.h:1427
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813c5be5)
Location: include/linux/blkdev.h:1427
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff8144ca07)
Location: include/linux/blkdev.h:1427
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-lib.c (ffffffff81571aa7)
Location: include/linux/blkdev.h:1427
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff8157cf75)
Location: include/linux/blkdev.h:1427
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/partitions/atari.c (ffffffff81581f39)
Location: include/linux/blkdev.h:1427
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (0)
Location: include/linux/blkdev.h:1427
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/efi.c (ffffffff81587e17)
Location: include/linux/blkdev.h:1427
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In drivers/block/loop.c (ffffffff817e3392)
Location: include/linux/blkdev.h:1427
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffffffff8195b6ae)
Location: include/linux/blkdev.h:1427
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff813c09f6)
Location: include/linux/blkdev.h:1402
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff813c3a96)
Location: include/linux/blkdev.h:1402
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff81415578)
Location: include/linux/blkdev.h:1402
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/super.c (ffffffff814a0a97)
Location: include/linux/blkdev.h:1402
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/bdev.c (ffffffff815c40c6)
Location: include/linux/blkdev.h:1402
Inline: True
Inline callers:
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
```
```
In block/fops.c (ffffffff815c54fa)
Location: include/linux/blkdev.h:1402
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/blk-lib.c (ffffffff815d61b7)
Location: include/linux/blkdev.h:1402
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff815e2575)
Location: include/linux/blkdev.h:1402
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In drivers/block/loop.c (ffffffff8186e35c)
Location: include/linux/blkdev.h:1402
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffffffff81a00e9e)
Location: include/linux/blkdev.h:1402
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff814459d8)
Location: include/linux/blkdev.h:1224
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff8144a951)
Location: include/linux/blkdev.h:1224
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8148ccd8)
Location: include/linux/blkdev.h:1224
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/super.c (ffffffff81527559)
Location: include/linux/blkdev.h:1224
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/bdev.c (ffffffff8166f13b)
Location: include/linux/blkdev.h:1224
Inline: True
Inline callers:
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
```
```
In block/fops.c (ffffffff8166ff6b)
Location: include/linux/blkdev.h:1224
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/blk-lib.c (ffffffff816821d4)
Location: include/linux/blkdev.h:1224
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff816911c2)
Location: include/linux/blkdev.h:1224
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In drivers/block/loop.c (ffffffff819b7b85)
Location: include/linux/blkdev.h:1224
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffffffff81b67bb9)
Location: include/linux/blkdev.h:1224
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff814d4a58)
Location: include/linux/blkdev.h:1172
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff814d904c)
Location: include/linux/blkdev.h:1172
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff81520263)
Location: include/linux/blkdev.h:1172
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/inode.c (ffffffff81580883)
Location: include/linux/blkdev.h:1172
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_getattr
```
```
In fs/ext4/super.c (ffffffff815c5639)
Location: include/linux/blkdev.h:1172
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/bdev.c (ffffffff8172b0e5)
Location: include/linux/blkdev.h:1172
Inline: True
Inline callers:
  - block/bdev.c:bdev_statx_dioalign
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
```
```
In block/fops.c (ffffffff8172b4cb)
Location: include/linux/blkdev.h:1172
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
```
```
In block/bio.c (ffffffff8172f590)
Location: include/linux/blkdev.h:1172
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_iter_get_pages
```
```
In block/blk-lib.c (ffffffff8173f854)
Location: include/linux/blkdev.h:1172
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff8174fde5)
Location: include/linux/blkdev.h:1172
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In drivers/block/loop.c (ffffffff81b2cec5)
Location: include/linux/blkdev.h:1172
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffffffff81d03569)
Location: include/linux/blkdev.h:1172
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff8150c505)
Location: include/linux/blkdev.h:1153
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
```
```
In fs/direct-io.c (ffffffff81511eea)
Location: include/linux/blkdev.h:1153
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff815582d0)
Location: include/linux/blkdev.h:1153
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/inode.c (ffffffff815b7e40)
Location: include/linux/blkdev.h:1153
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_getattr
```
```
In fs/ext4/super.c (ffffffff815fd25d)
Location: include/linux/blkdev.h:1153
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/bdev.c (ffffffff81767352)
Location: include/linux/blkdev.h:1153
Inline: True
Inline callers:
  - block/bdev.c:bdev_statx_dioalign
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
```
```
In block/fops.c (ffffffff81768824)
Location: include/linux/blkdev.h:1153
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
```
```
In block/bio.c (ffffffff8176b82d)
Location: include/linux/blkdev.h:1153
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_iter_get_pages
```
```
In block/blk-lib.c (ffffffff8177bd91)
Location: include/linux/blkdev.h:1153
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff8178c008)
Location: include/linux/blkdev.h:1153
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In drivers/block/loop.c (ffffffff81b7d0f3)
Location: include/linux/blkdev.h:1153
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffffffff81d6d345)
Location: include/linux/blkdev.h:1153
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:__write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff81541145)
Location: include/linux/blkdev.h:1138
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
```
```
In fs/direct-io.c (ffffffff815463b1)
Location: include/linux/blkdev.h:1138
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8158e900)
Location: include/linux/blkdev.h:1138
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/inode.c (ffffffff815f0bd4)
Location: include/linux/blkdev.h:1138
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_getattr
```
```
In fs/ext4/super.c (ffffffff81635d9c)
Location: include/linux/blkdev.h:1138
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_journal_blkdev
```
```
In block/bdev.c (ffffffff817a9022)
Location: include/linux/blkdev.h:1138
Inline: True
Inline callers:
  - block/bdev.c:bdev_statx_dioalign
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
```
```
In block/fops.c (ffffffff817aa6c7)
Location: include/linux/blkdev.h:1138
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_iomap_begin
```
```
In block/bio.c (ffffffff817adcf2)
Location: include/linux/blkdev.h:1138
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_iter_get_pages
```
```
In block/blk-lib.c (ffffffff817be181)
Location: include/linux/blkdev.h:1138
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff817ce7a8)
Location: include/linux/blkdev.h:1138
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In drivers/block/loop.c (ffffffff81bd107e)
Location: include/linux/blkdev.h:1138
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffffffff81e24566)
Location: include/linux/blkdev.h:1138
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:__write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (ffff8000103da1b8)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffff8000103e00f4)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffff8000103e4c38)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffff80001040785c)
Location: include/linux/blkdev.h:1307
Inline: True
```
```
In fs/iomap/direct-io.c (ffff80001042c978)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffff8000104bb850)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-lib.c (ffff8000105ecc44)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffff8000105f8910)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffff8000105ffa30)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffff800010604900)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffff800010606808)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffff80001061c430)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/block/loop.c (ffff800010922990)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffff800010af8804)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (c05b36dc)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
```
```
In fs/block_dev.c (c05b8f50)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (c05bcaf4)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (c05f555c)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (c067efb4)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-lib.c (c0799178)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (c07a3bec)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (c07aace0)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (c07afb68)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (c07b1808)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:last_lba
```
```
In drivers/block/loop.c (c0a06274)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (c0bd8928)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (c0000000004df1a0)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (c0000000004e5c78)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (c0000000004eaef8)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (c000000000513140)
Location: include/linux/blkdev.h:1307
Inline: True
```
```
In fs/iomap/direct-io.c (c00000000053e018)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (c0000000005f174c)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-lib.c (c000000000782614)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (c000000000790ce4)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (c000000000799e00)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (c0000000007a0690)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (c0000000007a2f30)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:find_valid_gpt
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (c0000000007bada8)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/block/loop.c (c0000000009c82ac)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (c000000000be4818)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffe000292fcc)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffe000296ec4)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffe00029a7f0)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffe0002b2480)
Location: include/linux/blkdev.h:1307
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffe0002c9d56)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffe000337b84)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-lib.c (ffffffe00042c6da)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffe0004354ea)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffe00043afd4)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffe00043f8b0)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffe000441730)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In drivers/block/loop.c (ffffffe0005a168a)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffffffe0006e9808)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff81319e06)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8131e4b7)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffff81321da8)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8133f8c0)
Location: include/linux/blkdev.h:1307
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8135e09b)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff813daa4e)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-lib.c (ffffffff814e663c)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814efef3)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff814f645b)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff814fb0c6)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814fcd32)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff8150daa1)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/block/loop.c (ffffffff816f28f3)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffffffff81848b8d)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff8130a9a6)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8130f057)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffff81312948)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff81330580)
Location: include/linux/blkdev.h:1307
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8134ed3b)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff813cb4ce)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-lib.c (ffffffff814d6bac)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814e0433)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff814e696b)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff814eb5d6)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814ed242)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff814fded1)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/block/loop.c (ffffffff816cc9f3)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffffffff818101ed)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff813178d6)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8131bf87)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffff8131f878)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8133d390)
Location: include/linux/blkdev.h:1307
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8135bb6b)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff813d7eee)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-lib.c (ffffffff814e26cc)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814ebf83)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff814f24eb)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff814f7156)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814f8dc2)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff81509b31)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/block/loop.c (ffffffff8171ffd3)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffffffff818981bd)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
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
In fs/buffer.c (ffffffff813294d1)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8132e097)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffff81331598)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff81350f80)
Location: include/linux/blkdev.h:1307
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8136f2bb)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff813ed18e)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-lib.c (ffffffff814fb54c)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff81504f93)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff8150b54b)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff815101b6)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff81511e22)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff815231a1)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/block/loop.c (ffffffff8173b393)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md-bitmap.c (ffffffff818b43d8)
Location: include/linux/blkdev.h:1307
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
</details>
</li>
</ul>

## Differences

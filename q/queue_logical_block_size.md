# Function: <code>queue_logical_block_size</code>

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
In fs/buffer.c (ffffffff81243c2d)
Location: include/linux/blkdev.h:1190
Inline: True
```
```
In fs/block_dev.c (ffffffff8124743f)
Location: include/linux/blkdev.h:1190
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:sb_min_blocksize
```
```
In fs/direct-io.c (ffffffff8124a16b)
Location: include/linux/blkdev.h:1190
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/ext4/super.c (ffffffff81322a11)
Location: include/linux/blkdev.h:1190
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In block/blk-core.c (ffffffff813b9e4c)
Location: include/linux/blkdev.h:1190
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffffffff813bc736)
Location: include/linux/blkdev.h:1190
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (ffffffff813c0600)
Location: include/linux/blkdev.h:1190
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-lib.c (ffffffff813c29a9)
Location: include/linux/blkdev.h:1190
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
```
In block/ioctl.c (ffffffff813c94e2)
Location: include/linux/blkdev.h:1190
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partitions/msdos.c (ffffffff813d292c)
Location: include/linux/blkdev.h:1190
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff813d3990)
Location: include/linux/blkdev.h:1190
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
In block/compat_ioctl.c (ffffffff813e6536)
Location: include/linux/blkdev.h:1190
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-integrity.c (ffffffff813e7b44)
Location: include/linux/blkdev.h:1190
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In drivers/block/loop.c (ffffffff8156e0f0)
Location: include/linux/blkdev.h:1190
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/block/virtio_blk.c (ffffffff81572092)
Location: include/linux/blkdev.h:1190
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_config_changed_work
  - drivers/block/virtio_blk.c:virtblk_config_changed_work
  - drivers/block/virtio_blk.c:virtblk_config_changed_work
  - drivers/block/virtio_blk.c:virtblk_probe
```
```
In drivers/md/md.c (ffffffff81691aed)
Location: include/linux/blkdev.h:1190
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/bitmap.c (ffffffff8169bb79)
Location: include/linux/blkdev.h:1190
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_sb_page
  - drivers/md/bitmap.c:write_page
```
```
In drivers/md/dm-io.c (ffffffff816aaee3)
Location: include/linux/blkdev.h:1190
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In fs/buffer.c (ffffffff8126c9de)
Location: include/linux/blkdev.h:1219
Inline: True
```
```
In fs/block_dev.c (ffffffff81270644)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff81272c57)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff81286903)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - fs/dax.c:__dax_zero_page_range
```
```
In fs/ext4/super.c (ffffffff812ed718)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In block/blk-core.c (ffffffff813fdc31)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffffffff81400416)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (ffffffff8140458e)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-lib.c (ffffffff8140651d)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
```
In block/ioctl.c (ffffffff8140d850)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partitions/atari.c (ffffffff81413b89)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8141845d)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff8141a168)
Location: include/linux/blkdev.h:1219
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
In block/compat_ioctl.c (ffffffff8142c7c2)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-integrity.c (ffffffff8142ddd4)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In drivers/block/loop.c (ffffffff815c39e0)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/block/virtio_blk.c (ffffffff815c80f5)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_config_changed_work
  - drivers/block/virtio_blk.c:virtblk_config_changed_work
  - drivers/block/virtio_blk.c:virtblk_config_changed_work
```
```
In drivers/md/md.c (ffffffff816f2862)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/bitmap.c (ffffffff816fea1e)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
  - drivers/md/bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (ffffffff8170b392)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In fs/buffer.c (ffffffff8127fcb5)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81283f93)
Location: include/linux/blkdev.h:1384
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
In fs/direct-io.c (ffffffff81286759)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8129a893)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - fs/dax.c:__dax_zero_page_range
```
```
In fs/iomap.c (ffffffff812b0c64)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
```
```
In fs/ext4/super.c (ffffffff81302fe7)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In block/blk-core.c (ffffffff81417570)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffffffff81419e06)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (ffffffff8141dced)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-lib.c (ffffffff81420a17)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814286e0)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff8142f0b9)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8143398d)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff81435698)
Location: include/linux/blkdev.h:1384
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
In block/compat_ioctl.c (ffffffff814465c2)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-integrity.c (ffffffff81447b94)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In drivers/block/loop.c (ffffffff815f20c0)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff81723f81)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/bitmap.c (ffffffff8173067a)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
  - drivers/md/bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (ffffffff8173d31f)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In fs/buffer.c (ffffffff8128d25e)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81291649)
Location: include/linux/blkdev.h:1422
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
In fs/direct-io.c (ffffffff81293de3)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff812a944d)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - fs/dax.c:__dax_zero_page_range
```
```
In fs/iomap.c (ffffffff812be06a)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
```
```
In fs/ext4/super.c (ffffffff813389f1)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In block/blk-core.c (ffffffff814253cf)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffffffff81427d46)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (ffffffff8142c2f4)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-lib.c (ffffffff8142e987)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff81436a29)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff8143c2f9)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8144077f)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814421e6)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff81454b4f)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-integrity.c (ffffffff814560cc)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In drivers/block/loop.c (ffffffff816062d0)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff8173c38b)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/bitmap.c (ffffffff81748526)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
  - drivers/md/bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (ffffffff81756fe7)
Location: include/linux/blkdev.h:1422
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In fs/buffer.c (ffffffff812afd9e)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff812b4399)
Location: include/linux/blkdev.h:1437
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
In fs/direct-io.c (ffffffff812b6d43)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff812cca1d)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - fs/dax.c:__dax_zero_page_range
```
```
In fs/iomap.c (ffffffff812e1969)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
```
```
In fs/ext4/super.c (ffffffff8135cfd3)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In block/blk-core.c (ffffffff814504a0)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffffffff81452e06)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (ffffffff81457507)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-lib.c (ffffffff81459e69)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814627bc)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff814683d9)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8146ce13)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff8146eb56)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff814807e5)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-integrity.c (ffffffff81481d2c)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In drivers/block/loop.c (ffffffff8166e6d0)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff817adf3b)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff817ba7b6)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (ffffffff817c91f7)
Location: include/linux/blkdev.h:1437
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In fs/buffer.c (ffffffff812d7ff8)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff812db9bf)
Location: include/linux/blkdev.h:1477
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
In fs/direct-io.c (ffffffff812df733)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff812f7133)
Location: include/linux/blkdev.h:1477
Inline: True
```
```
In fs/iomap.c (ffffffff8130e079)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
```
```
In fs/ext4/super.c (ffffffff813865a9)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In block/blk-core.c (ffffffff81483787)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffffffff81486255)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (ffffffff8148a471)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-lib.c (ffffffff8148d5bc)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff81496290)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff8149c269)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff814a0d0d)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814a2b30)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:find_valid_gpt
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff814b531e)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-integrity.c (ffffffff814b697c)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In drivers/block/loop.c (ffffffff816aa1b0)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff817f3d64)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff81802752)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (ffffffff81811f9b)
Location: include/linux/blkdev.h:1477
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In fs/buffer.c (ffffffff812ed068)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff812f10af)
Location: include/linux/blkdev.h:1256
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
In fs/direct-io.c (ffffffff812f4243)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8130c1e3)
Location: include/linux/blkdev.h:1256
Inline: True
```
```
In fs/iomap.c (ffffffff813238dd)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff8139f0a9)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In block/blk-core.c (ffffffff8149ef47)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffffffff814a0465)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (ffffffff814a3fd7)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-lib.c (ffffffff814a6e4c)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814b05d7)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff814b6589)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff814bb0cd)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814bcd12)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff814c8bdb)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-integrity.c (ffffffff814ca18c)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff814cafce)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_complete
  - block/t10-pi.c:t10_pi_prepare
```
```
In drivers/block/loop.c (ffffffff816cada0)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff8181fc94)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff8182ea3b)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (ffffffff8183df07)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In fs/buffer.c (ffffffff8130e814)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81312fb3)
Location: include/linux/blkdev.h:1270
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
In fs/direct-io.c (ffffffff8131695c)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8133372e)
Location: include/linux/blkdev.h:1270
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8134d80d)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff813c90be)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-core.c (ffffffff814cd028)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffffffff814ce9d5)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (ffffffff814d2644)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffffffff814d4d6c)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814de4db)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff814e4ac9)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff814e9735)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814eb39e)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff814f7822)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-integrity.c (ffffffff814f8a5c)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff814f98f0)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_complete
  - block/t10-pi.c:t10_pi_prepare
```
```
In drivers/block/loop.c (ffffffff81706370)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff81862237)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff81870f24)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (ffffffff81880be7)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In fs/buffer.c (ffffffff81321834)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81325ede)
Location: include/linux/blkdev.h:1297
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
In fs/direct-io.c (ffffffff813297dc)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff813472ee)
Location: include/linux/blkdev.h:1297
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff81365acd)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff813e246e)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-core.c (ffffffff814e625e)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffffffff814e7d45)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (ffffffff814eb9c9)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffffffff814ee05c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814f7927)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff814fde89)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff81502aff)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff81504766)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff815154c8)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-integrity.c (ffffffff8151690c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff81517687)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/block/loop.c (ffffffff8172cb27)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff81893e67)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff818a2d19)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (ffffffff818b2aa7)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In fs/buffer.c (ffffffff8135be4c)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
```
```
In fs/block_dev.c (ffffffff8135f27e)
Location: include/linux/blkdev.h:1331
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
In fs/direct-io.c (ffffffff813635c5)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813acf3e)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff8142e52a)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-core.c (ffffffff8154554e)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffffffff81546c25)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (ffffffff8154bfb4)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/blk-lib.c (ffffffff8154d9d2)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff815588e8)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/partitions/atari.c (ffffffff8155e5e7)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8156339c)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/efi.c (ffffffff815651b5)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:alloc_read_gpt_header
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/blk-integrity.c (ffffffff81577130)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff81577e47)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/block/loop.c (ffffffff817e9d1c)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff8196650c)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff81972838)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (ffffffff81983041)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In fs/buffer.c (ffffffff8136a3e9)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
```
```
In fs/block_dev.c (ffffffff8136e3f2)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff8137086c)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813be62b)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff81447207)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-core.c (ffffffff81561bab)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffffffff81562915)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (ffffffff8156830e)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/blk-lib.c (ffffffff81569b4f)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff81574ee9)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/partitions/atari.c (ffffffff8157a224)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8157e4d9)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/efi.c (ffffffff815802af)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:alloc_read_gpt_header
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/blk-integrity.c (ffffffff81593dca)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff81594ac5)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/block/loop.c (ffffffff817fe76c)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff8196cf59)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff81977754)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (ffffffff8198715e)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In fs/buffer.c (ffffffff81371031)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81374cff)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff8137713b)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813c5c1b)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff8144ca07)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-core.c (ffffffff8156a312)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffffffff8156afc9)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-settings.c (ffffffff8156d4ae)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_set_zoned
```
```
In block/blk-merge.c (ffffffff815700d6)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/blk-lib.c (ffffffff81571aa7)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff8157cf79)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/partitions/atari.c (ffffffff81581f54)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff81586069)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/efi.c (ffffffff81587e27)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/blk-integrity.c (ffffffff8159abaa)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff8159b898)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/block/loop.c (ffffffff817e339d)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff8194fa3a)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff8195b6ae)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (ffffffff8196b830)
Location: include/linux/blkdev.h:1417
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In fs/buffer.c (ffffffff813c0a01)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff813c3aa1)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff81415587)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/super.c (ffffffff814a0a97)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/bdev.c (ffffffff815c40d1)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
```
```
In block/fops.c (ffffffff815c54fa)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/blk-core.c (ffffffff815cd9f0)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffffffff815cf239)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-settings.c (ffffffff815d1b0c)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_set_zoned
```
```
In block/blk-merge.c (ffffffff815d477f)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/blk-lib.c (ffffffff815d61b7)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff815e2579)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/partitions/atari.c (ffffffff815e72ad)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff815eba92)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/efi.c (ffffffff815edac1)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/blk-integrity.c (ffffffff81602dea)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff8160382c)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/block/loop.c (ffffffff8186e367)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff819f4eba)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff81a00e9e)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (ffffffff81a13cf0)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In fs/buffer.c (ffffffff814459df)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff8144a958)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8148cce3)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/super.c (ffffffff81527559)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/bdev.c (ffffffff8166f142)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
```
```
In block/fops.c (ffffffff8166ff6b)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/blk-sysfs.c (ffffffff8167a7e9)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-settings.c (ffffffff8167d5af)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_set_zoned
```
```
In block/blk-merge.c (ffffffff816805b6)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/blk-lib.c (ffffffff816823b7)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff816911c9)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/partitions/atari.c (ffffffff81696667)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8169ba5d)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/efi.c (ffffffff8169e068)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In block/blk-integrity.c (ffffffff816b5d2a)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff816b6a2c)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/block/loop.c (ffffffff819b7b8c)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff81b5eac8)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff81b67bc0)
Location: include/linux/blkdev.h:1214
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
In fs/buffer.c (ffffffff814d4a5f)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff814d9053)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff81520263)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/inode.c (ffffffff8158088a)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_getattr
```
```
In fs/ext4/super.c (ffffffff815c5639)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/bdev.c (ffffffff8172b0ec)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - block/bdev.c:bdev_statx_dioalign
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
```
```
In block/fops.c (ffffffff8172b4cb)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
```
```
In block/bio.c (ffffffff8172f59b)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_iter_get_pages
```
```
In block/blk-sysfs.c (ffffffff81736d79)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-settings.c (ffffffff8173a0c3)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - block/blk-settings.c:disk_set_zoned
```
```
In block/blk-lib.c (ffffffff8173fa4d)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff8174fdec)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/partitions/atari.c (ffffffff81755857)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff8175ab4d)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/efi.c (ffffffff8175caa8)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In block/blk-integrity.c (ffffffff817757ea)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff817769ec)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/block/loop.c (ffffffff81b2cecc)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff81cf89b6)
Location: include/linux/blkdev.h:1162
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff81d03570)
Location: include/linux/blkdev.h:1162
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
In fs/buffer.c (ffffffff8150c525)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
```
```
In fs/direct-io.c (ffffffff81511eee)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff815582d0)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/inode.c (ffffffff815b7e44)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_getattr
```
```
In fs/ext4/super.c (ffffffff815fd25d)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/bdev.c (ffffffff81767356)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - block/bdev.c:bdev_statx_dioalign
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
```
```
In block/fops.c (ffffffff81768824)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
```
```
In block/bio.c (ffffffff8176b836)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_iter_get_pages
```
```
In block/blk-sysfs.c (ffffffff81773539)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-settings.c (ffffffff817767b1)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - block/blk-settings.c:disk_set_zoned
```
```
In block/blk-lib.c (ffffffff8177bf7a)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff8178c00d)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/partitions/atari.c (ffffffff817922e7)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff81798a0d)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/efi.c (ffffffff8179b343)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In block/blk-integrity.c (ffffffff817b573a)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff817b65bc)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/block/loop.c (ffffffff81b7d0f7)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/block/virtio_blk.c (ffffffff81b80ddb)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_update_capacity
  - drivers/block/virtio_blk.c:virtblk_update_capacity
  - drivers/block/virtio_blk.c:virtblk_update_capacity
```
```
In drivers/md/md.c (ffffffff81d605f5)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff81d6d345)
Location: include/linux/blkdev.h:1143
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
In fs/buffer.c (ffffffff81541168)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
```
```
In fs/direct-io.c (ffffffff815463b5)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8158e900)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/inode.c (ffffffff815f0bd8)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_getattr
```
```
In fs/ext4/super.c (ffffffff81635d9c)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_journal_blkdev
```
```
In block/bdev.c (ffffffff817a9026)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - block/bdev.c:bdev_statx_dioalign
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
```
```
In block/fops.c (ffffffff817aa6c7)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_iomap_begin
```
```
In block/bio.c (ffffffff817adcf6)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_iter_get_pages
```
```
In block/blk-sysfs.c (ffffffff817b5819)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-settings.c (ffffffff817b89d1)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - block/blk-settings.c:disk_set_zoned
```
```
In block/blk-lib.c (ffffffff817be36a)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff817ce7ad)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkpg_do_ioctl
```
```
In block/partitions/atari.c (ffffffff817d5bf7)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff817dc43d)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/efi.c (ffffffff817deda3)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In block/blk-integrity.c (ffffffff817fa14a)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff817fafcc)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/block/loop.c (ffffffff81bd1082)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/block/virtio_blk.c (ffffffff81bd4c49)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_update_capacity
  - drivers/block/virtio_blk.c:virtblk_update_capacity
  - drivers/block/virtio_blk.c:virtblk_update_capacity
```
```
In drivers/md/md.c (ffffffff81e18355)
Location: include/linux/blkdev.h:1128
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff81e24566)
Location: include/linux/blkdev.h:1128
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
In fs/buffer.c (ffff8000103da1c4)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffff8000103e00fc)
Location: include/linux/blkdev.h:1297
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
In fs/direct-io.c (ffff8000103e4c44)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffff800010407864)
Location: include/linux/blkdev.h:1297
Inline: True
```
```
In fs/iomap/direct-io.c (ffff80001042c978)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffff8000104bb854)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-core.c (ffff8000105e381c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffff8000105e59fc)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (ffff8000105ea3e0)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffff8000105ecc44)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffff8000105f891c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffff8000105ffa38)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffff80001060490c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffff800010606808)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffff80001061c434)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-integrity.c (ffff80001061dd48)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffff80001061eb6c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/block/loop.c (ffff80001092299c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffff800010ae8a84)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffff800010af8804)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (ffff800010b0a22c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In fs/buffer.c (c05b36f0)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
```
```
In fs/block_dev.c (c05b8f54)
Location: include/linux/blkdev.h:1297
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
In fs/direct-io.c (c05bcafc)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (c05f556c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (c067efb8)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-core.c (c0790b30)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (c07928f8)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (c0796a6c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:blk_bio_discard_split
```
```
In block/blk-lib.c (c0799178)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (c07a3bf4)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (c07aace8)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (c07afb74)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (c07b1814)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:last_lba
```
```
In block/blk-integrity.c (c07c58c8)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (c07c6530)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/block/loop.c (c0a0627c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (c0bc8d28)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (c0bd8928)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (c0be86c8)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In fs/buffer.c (c0000000004df1ac)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (c0000000004e5c80)
Location: include/linux/blkdev.h:1297
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
In fs/direct-io.c (c0000000004eaf04)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (c000000000513144)
Location: include/linux/blkdev.h:1297
Inline: True
```
```
In fs/iomap/direct-io.c (c00000000053e024)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (c0000000005f174c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-core.c (c000000000777248)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (c000000000779b8c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (c00000000077f3e0)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (c000000000782614)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (c000000000790cec)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (c000000000799e08)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (c0000000007a069c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (c0000000007a2f38)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:find_valid_gpt
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (c0000000007badac)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-integrity.c (c0000000007bcdf0)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (c0000000007be08c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/block/loop.c (c0000000009c82b8)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (c000000000bd1b70)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (c000000000be4824)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (c000000000bfbc68)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In fs/buffer.c (ffffffe000292fd0)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffe000296ec8)
Location: include/linux/blkdev.h:1297
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
In fs/direct-io.c (ffffffe00029a7f8)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffe0002b2484)
Location: include/linux/blkdev.h:1297
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffe0002c9d62)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffe000337b8a)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-core.c (ffffffe00042529e)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffffffe000426d28)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (ffffffe00042a794)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffffffe00042c6da)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffe0004354ee)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffe00043afda)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffe00043f8b4)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffe000441736)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/blk-integrity.c (ffffffe000450972)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffe000451b3e)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/block/loop.c (ffffffe0005a168c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffe0006dc63a)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffe0006e980a)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (ffffffe0006f8254)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In fs/buffer.c (ffffffff81319e14)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8131e4be)
Location: include/linux/blkdev.h:1297
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
In fs/direct-io.c (ffffffff81321dbc)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8133f8ce)
Location: include/linux/blkdev.h:1297
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8135e0ad)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff813daa4e)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-core.c (ffffffff814de83e)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffffffff814e0325)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (ffffffff814e3fa9)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffffffff814e663c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814eff07)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff814f6469)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff814fb0df)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814fcd46)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff8150daa8)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-integrity.c (ffffffff8150eeec)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff8150fc67)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/block/loop.c (ffffffff816f2907)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/nvme/host/core.c (ffffffff8174332a)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_update_disk_info
  - drivers/nvme/host/core.c:nvme_setup_cmd
```
```
In drivers/md/md.c (ffffffff81839ce7)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff81848b99)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (ffffffff81858927)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In fs/buffer.c (ffffffff8130a9b4)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8130f05e)
Location: include/linux/blkdev.h:1297
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
In fs/direct-io.c (ffffffff8131295c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8133058e)
Location: include/linux/blkdev.h:1297
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8134ed4d)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff813cb4ce)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-core.c (ffffffff814cf1de)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffffffff814d0cc5)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (ffffffff814d4889)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffffffff814d6bac)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814e0447)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff814e6979)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff814eb5ef)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814ed256)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff814fded8)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-integrity.c (ffffffff814ff31c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff814fff87)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/block/loop.c (ffffffff816cca07)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/nvme/host/core.c (ffffffff81724fba)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_update_disk_info
  - drivers/nvme/host/core.c:nvme_setup_cmd
```
```
In drivers/md/md.c (ffffffff81801357)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff818101f9)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (ffffffff8181ff37)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In fs/buffer.c (ffffffff813178e4)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8131bf8e)
Location: include/linux/blkdev.h:1297
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
In fs/direct-io.c (ffffffff8131f88c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8133d39e)
Location: include/linux/blkdev.h:1297
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8135bb7d)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff813d7eee)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-core.c (ffffffff814da8ce)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffffffff814dc3b5)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (ffffffff814e0039)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffffffff814e26cc)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff814ebf97)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff814f24f9)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff814f716f)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff814f8dd6)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff81509b38)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-integrity.c (ffffffff8150af7c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff8150bcf7)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/block/loop.c (ffffffff8171ffe7)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff81889317)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff818981c9)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (ffffffff818a7f57)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In fs/buffer.c (ffffffff813294df)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8132e09e)
Location: include/linux/blkdev.h:1297
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
In fs/direct-io.c (ffffffff813315ac)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff81350f8e)
Location: include/linux/blkdev.h:1297
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8136f2cd)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/ext4/super.c (ffffffff813ed18e)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In block/blk-core.c (ffffffff814f35ce)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-sysfs.c (ffffffff814f5225)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_logical_block_size_show
```
```
In block/blk-merge.c (ffffffff814f8e99)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffffffff814fb54c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff81504fa7)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/partitions/atari.c (ffffffff8150b559)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/msdos.c (ffffffff815101cf)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/efi.c (ffffffff81511e36)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/efi.c:read_lba
```
```
In block/compat_ioctl.c (ffffffff815231a8)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-integrity.c (ffffffff8152461c)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff81525397)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/block/loop.c (ffffffff8173b3a7)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/md/md.c (ffffffff818a6a47)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff818b43e4)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:read_sb_page
```
```
In drivers/md/dm-io.c (ffffffff818c4197)
Location: include/linux/blkdev.h:1297
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
</ul>

## Differences

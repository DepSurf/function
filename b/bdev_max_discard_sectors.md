# Function: <code>bdev_max_discard_sectors</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813826e3)
Location: include/linux/blkdev.h:1274
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/ext4/ioctl.c (ffffffff814ee4bf)
Location: include/linux/blkdev.h:1274
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8152de05)
Location: include/linux/blkdev.h:1274
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/jbd2/journal.c (ffffffff8154b113)
Location: include/linux/blkdev.h:1274
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_erase
```
```
In fs/fat/file.c (ffffffff8155ea9c)
Location: include/linux/blkdev.h:1274
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff81561178)
Location: include/linux/blkdev.h:1274
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-core.c (ffffffff81679651)
Location: include/linux/blkdev.h:1274
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-lib.c (ffffffff81681bb5)
Location: include/linux/blkdev.h:1274
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff81690c61)
Location: include/linux/blkdev.h:1274
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/block/loop.c (ffffffff819b5f6b)
Location: include/linux/blkdev.h:1274
Inline: True
```
```
In drivers/md/dm.c (ffffffff81b7304c)
Location: include/linux/blkdev.h:1274
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-table.c (ffffffff81b74825)
Location: include/linux/blkdev.h:1274
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_discard_capable
```
```
In drivers/md/dm-io.c (ffffffff81b7c7a1)
Location: include/linux/blkdev.h:1274
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In mm/swapfile.c (ffffffff813fc655)
Location: include/linux/blkdev.h:1222
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/ext4/ioctl.c (ffffffff815883bf)
Location: include/linux/blkdev.h:1222
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff815cbfc9)
Location: include/linux/blkdev.h:1222
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/jbd2/journal.c (ffffffff815ead68)
Location: include/linux/blkdev.h:1222
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_erase
```
```
In fs/fat/file.c (ffffffff81600c9c)
Location: include/linux/blkdev.h:1222
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff816036fa)
Location: include/linux/blkdev.h:1222
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-core.c (ffffffff817359e8)
Location: include/linux/blkdev.h:1222
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-lib.c (ffffffff8173f1e6)
Location: include/linux/blkdev.h:1222
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff8174f849)
Location: include/linux/blkdev.h:1222
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/block/loop.c (ffffffff81b2b0fb)
Location: include/linux/blkdev.h:1222
Inline: True
```
```
In drivers/md/dm.c (ffffffff81d0efd0)
Location: include/linux/blkdev.h:1222
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-table.c (ffffffff81d11755)
Location: include/linux/blkdev.h:1222
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_discard_capable
```
```
In drivers/md/dm-io.c (ffffffff81d1a634)
Location: include/linux/blkdev.h:1222
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In mm/swapfile.c (ffffffff8142f95e)
Location: include/linux/blkdev.h:1203
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/ext4/ioctl.c (ffffffff815bf1d6)
Location: include/linux/blkdev.h:1203
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff816038eb)
Location: include/linux/blkdev.h:1203
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/jbd2/journal.c (ffffffff816227e8)
Location: include/linux/blkdev.h:1203
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_erase
```
```
In fs/fat/file.c (ffffffff81638b8f)
Location: include/linux/blkdev.h:1203
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff8163b61a)
Location: include/linux/blkdev.h:1203
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-core.c (ffffffff81771e83)
Location: include/linux/blkdev.h:1203
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-lib.c (ffffffff8177b753)
Location: include/linux/blkdev.h:1203
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff8178b4c4)
Location: include/linux/blkdev.h:1203
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/block/loop.c (ffffffff81b7b3e8)
Location: include/linux/blkdev.h:1203
Inline: True
```
```
In drivers/md/dm.c (ffffffff81d781e1)
Location: include/linux/blkdev.h:1203
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-table.c (ffffffff81d7abb5)
Location: include/linux/blkdev.h:1203
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_discard_capable
```
```
In drivers/md/dm-io.c (ffffffff81d83791)
Location: include/linux/blkdev.h:1203
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In mm/swapfile.c (ffffffff814694f4)
Location: include/linux/blkdev.h:1188
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/ext4/ioctl.c (ffffffff815f7f7c)
Location: include/linux/blkdev.h:1188
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8163c6f8)
Location: include/linux/blkdev.h:1188
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/jbd2/journal.c (ffffffff8165b848)
Location: include/linux/blkdev.h:1188
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_erase
```
```
In fs/fat/file.c (ffffffff8167207f)
Location: include/linux/blkdev.h:1188
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff81674b79)
Location: include/linux/blkdev.h:1188
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In block/blk-core.c (ffffffff817b454d)
Location: include/linux/blkdev.h:1188
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-lib.c (ffffffff817bdb43)
Location: include/linux/blkdev.h:1188
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff817cdc24)
Location: include/linux/blkdev.h:1188
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/block/loop.c (ffffffff81bcf1d8)
Location: include/linux/blkdev.h:1188
Inline: True
```
```
In drivers/md/dm.c (ffffffff81e2f41a)
Location: include/linux/blkdev.h:1188
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-table.c (ffffffff81e31cc5)
Location: include/linux/blkdev.h:1188
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_discard_capable
```
```
In drivers/md/dm-io.c (ffffffff81e3ae71)
Location: include/linux/blkdev.h:1188
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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

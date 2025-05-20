# Function: <code>sync_blockdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812473e0)
Location: fs/block_dev.c:186
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:__blkdev_put
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff812473e0-ffffffff81247400: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8127106a)
Location: fs/block_dev.c:204
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8126fca0-ffffffff8126fcc0: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812849d7)
Location: fs/block_dev.c:459
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81282ea0-ffffffff81282ec0: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff81291daf)
Location: fs/block_dev.c:467
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81291b90-ffffffff81291ba8: sync_blockdev.part.27 (STB_LOCAL)
ffffffff81291bb0-ffffffff81291bc8: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff812b4b2f)
Location: fs/block_dev.c:455
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff812b4910-ffffffff812b4928: sync_blockdev.part.32 (STB_LOCAL)
ffffffff812b4930-ffffffff812b4948: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dccc0)
Location: fs/block_dev.c:456
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff812db1d0-ffffffff812db1f0: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f2120)
Location: fs/block_dev.c:493
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff812f0720-ffffffff812f0740: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81313b60)
Location: fs/block_dev.c:498
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff813120a0-ffffffff813120c0: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81326a70)
Location: fs/block_dev.c:498
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81325000-ffffffff81325020: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81360656)
Location: fs/block_dev.c:497
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - block/partitions/core.c:blk_drop_partitions
  - block/partitions/core.c:bdev_del_partition
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8135fef0-ffffffff8135ff1c: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136dbc6)
Location: fs/block_dev.c:529
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - block/partitions/core.c:blk_drop_partitions
  - block/partitions/core.c:bdev_del_partition
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8136d760-ffffffff8136d78c: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813744fb)
Location: fs/block_dev.c:533
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:bdev_disk_changed
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81374150-ffffffff8137417c: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c4623)
Location: block/bdev.c:200
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:freeze_bdev
  - block/bdev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff815c3ee0-ffffffff815c3f0c: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166ed32)
Location: block/bdev.c:195
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:freeze_bdev
  - block/bdev.c:freeze_bdev
  - block/bdev.c:set_blocksize
  - block/bdev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8166eac0-ffffffff8166eb00: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8172a002)
Location: block/bdev.c:194
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:freeze_bdev
  - block/bdev.c:freeze_bdev
  - block/bdev.c:set_blocksize
  - block/bdev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81729da0-ffffffff81729de0: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8176635f)
Location: block/bdev.c:194
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:freeze_bdev
  - block/bdev.c:freeze_bdev
  - block/bdev.c:set_blocksize
  - block/bdev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - block/partitions/core.c:bdev_disk_changed
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81766110-ffffffff81766150: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817a83e7)
Location: block/bdev.c:197
Inline: True
Inline callers:
  - block/bdev.c:bdev_mark_dead
  - block/bdev.c:bdev_mark_dead
  - block/bdev.c:bdev_release
  - block/bdev.c:bdev_release
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:bdev_freeze
  - block/bdev.c:bdev_freeze
  - block/bdev.c:set_blocksize
  - block/bdev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:fs_bdev_freeze
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - block/ioctl.c:blkdev_common_ioctl
  - block/partitions/core.c:bdev_disk_changed
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff817a7c60-ffffffff817a7ca0: sync_blockdev (STB_GLOBAL)
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
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e1890)
Location: fs/block_dev.c:498
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffff8000103df598-ffff8000103df5dc: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b8ae8)
Location: fs/block_dev.c:498
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
c05b78bc-c05b78e8: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e5638)
Location: fs/block_dev.c:498
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
c0000000004e43a0-c0000000004e43f8: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000297dd6)
Location: fs/block_dev.c:498
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffe0002963f4-ffffffe00029642e: sync_blockdev (STB_GLOBAL)
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
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131f050)
Location: fs/block_dev.c:498
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8131d5e0-ffffffff8131d600: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130fbf0)
Location: fs/block_dev.c:498
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8130e180-ffffffff8130e1a0: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131cb20)
Location: fs/block_dev.c:498
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8131b0b0-ffffffff8131b0d0: sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sync_blockdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132dd23)
Location: fs/block_dev.c:498
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/super.c:kill_block_super
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8132cd50-ffffffff8132cd70: sync_blockdev (STB_GLOBAL)
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

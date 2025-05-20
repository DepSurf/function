# Function: <code>invalidate_bdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81247380)
Location: fs/block_dev.c:87
Inline: False
Direct callers:
  - fs/super.c:do_remount_sb
  - fs/block_dev.c:__invalidate_device
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81247380-ffffffff812473d3: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8126fc40)
Location: fs/block_dev.c:100
Inline: False
Direct callers:
  - fs/super.c:do_remount_sb
  - fs/block_dev.c:__invalidate_device
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8126fc40-ffffffff8126fc93: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81282e40)
Location: fs/block_dev.c:102
Inline: False
Direct callers:
  - fs/super.c:do_remount_sb
  - fs/block_dev.c:__invalidate_device
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81282e40-ffffffff81282e93: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812907b0)
Location: fs/block_dev.c:103
Inline: False
Direct callers:
  - fs/super.c:do_remount_sb
  - fs/block_dev.c:__invalidate_device
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff812907b0-ffffffff81290802: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b3470)
Location: fs/block_dev.c:91
Inline: False
Direct callers:
  - fs/super.c:do_remount_sb
  - fs/block_dev.c:__invalidate_device
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff812b3470-ffffffff812b34c2: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812db170)
Location: fs/block_dev.c:91
Inline: False
Direct callers:
  - fs/super.c:do_remount_sb
  - fs/block_dev.c:__invalidate_device
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff812db170-ffffffff812db1c2: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f06c0)
Location: fs/block_dev.c:91
Inline: False
Direct callers:
  - fs/super.c:do_remount_sb
  - fs/block_dev.c:__invalidate_device
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff812f06c0-ffffffff812f0712: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81312040)
Location: fs/block_dev.c:91
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:__invalidate_device
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81312040-ffffffff81312096: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81324fa0)
Location: fs/block_dev.c:91
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:__invalidate_device
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81324fa0-ffffffff81324ff6: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8135eb30)
Location: fs/block_dev.c:90
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
  - fs/block_dev.c:check_disk_size_change
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_common_ioctl
  - block/partitions/core.c:blk_drop_partitions
  - block/partitions/core.c:bdev_del_partition
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl_reset
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8135eb30-ffffffff8135eb88: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136c2f0)
Location: fs/block_dev.c:90
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:__invalidate_device
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_common_ioctl
  - block/partitions/core.c:blk_drop_partitions
  - block/partitions/core.c:bdev_del_partition
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl_reset
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8136c2f0-ffffffff8136c348: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81372c30)
Location: fs/block_dev.c:90
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:bdev_disk_changed
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_common_ioctl
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81372c30-ffffffff81372c88: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c3b80)
Location: block/bdev.c:81
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/bdev.c:__invalidate_device
  - block/ioctl.c:blkdev_common_ioctl
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff815c3b80-ffffffff815c3bdb: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166ea65)
Location: block/bdev.c:81
Inline: True
Inline callers:
  - block/bdev.c:__invalidate_device
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_common_ioctl
  - block/genhd.c:invalidate_disk
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8166e4c0-ffffffff8166e51b: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81729d35)
Location: block/bdev.c:80
Inline: True
Inline callers:
  - block/bdev.c:__invalidate_device
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_common_ioctl
  - block/genhd.c:invalidate_disk
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff817296d0-ffffffff8172972b: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817660a5)
Location: block/bdev.c:80
Inline: True
Inline callers:
  - block/bdev.c:__invalidate_device
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_common_ioctl
  - block/genhd.c:invalidate_disk
  - block/partitions/core.c:bdev_disk_changed
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81765a40-ffffffff81765a98: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817a83bd)
Location: block/bdev.c:83
Inline: True
Inline callers:
  - block/bdev.c:bdev_mark_dead
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_common_ioctl
  - block/genhd.c:invalidate_disk
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_del_partition
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff817a7640-ffffffff817a7698: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103df530)
Location: fs/block_dev.c:91
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:__invalidate_device
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffff8000103df530-ffff8000103df598: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b7858)
Location: fs/block_dev.c:91
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:__invalidate_device
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
c05b7858-c05b78bc: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e42f0)
Location: fs/block_dev.c:91
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:__invalidate_device
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
c0000000004e42f0-c0000000004e4398: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000296396)
Location: fs/block_dev.c:91
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:__invalidate_device
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffe000296396-ffffffe0002963f4: invalidate_bdev (STB_GLOBAL)
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
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131d580)
Location: fs/block_dev.c:91
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:__invalidate_device
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8131d580-ffffffff8131d5d6: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130e120)
Location: fs/block_dev.c:91
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:__invalidate_device
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8130e120-ffffffff8130e176: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131b050)
Location: fs/block_dev.c:91
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:__invalidate_device
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8131b050-ffffffff8131b0a6: invalidate_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132ccf0)
Location: fs/block_dev.c:91
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:__invalidate_device
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkpg_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8132ccf0-ffffffff8132cd46: invalidate_bdev (STB_GLOBAL)
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

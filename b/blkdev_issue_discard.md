# Function: <code>blkdev_issue_discard</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff813c2640)
Location: block/blk-lib.c:40
Inline: False
Direct callers:
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/fat/fatent.c:fat_free_clusters
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff813c2640-ffffffff813c2890: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814065c0)
Location: block/blk-lib.c:112
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/fat/fatent.c:fat_free_clusters
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff814065c0-ffffffff81406689: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81420730)
Location: block/blk-lib.c:117
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/fat/fatent.c:fat_free_clusters
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff81420730-ffffffff814207f9: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8142e6c0)
Location: block/blk-lib.c:112
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/fat/fatent.c:fat_free_clusters
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff8142e6c0-ffffffff8142e78a: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814599e0)
Location: block/blk-lib.c:113
Inline: False
Direct callers:
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/fat/fatent.c:fat_free_clusters
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff814599e0-ffffffff81459aaa: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8148d050)
Location: block/blk-lib.c:132
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/fat/fatent.c:fat_free_clusters
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff8148d050-ffffffff8148d111: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814a6750)
Location: block/blk-lib.c:97
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff814a6750-ffffffff814a6811: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814d4660)
Location: block/blk-lib.c:97
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff814d4660-ffffffff814d4722: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814ed970)
Location: block/blk-lib.c:97
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff814ed970-ffffffff814eda32: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8154d6a0)
Location: block/blk-lib.c:97
Inline: False
Direct callers:
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:discard_swap
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_free_clusters
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff8154d6a0-ffffffff8154d756: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81569f80)
Location: block/blk-lib.c:131
Inline: False
Direct callers:
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:discard_swap
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_free_clusters
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff81569f80-ffffffff8156a036: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81571ef0)
Location: block/blk-lib.c:131
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_free_clusters
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff81571ef0-ffffffff81571fb3: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff815d6600)
Location: block/blk-lib.c:132
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_free_clusters
  - block/fops.c:blkdev_fallocate
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff815d6600-ffffffff815d66c3: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81681d00)
Location: block/blk-lib.c:99
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_free_clusters
  - block/fops.c:blkdev_fallocate
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff81681d00-ffffffff81681de4: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8173f330)
Location: block/blk-lib.c:97
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_free_clusters
  - block/fops.c:blkdev_fallocate
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff8173f330-ffffffff8173f414: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8177b890)
Location: block/blk-lib.c:97
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_free_clusters
  - block/fops.c:blkdev_fallocate
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff8177b890-ffffffff8177b96d: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff817bdc80)
Location: block/blk-lib.c:97
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_free_clusters
  - block/fops.c:blkdev_fallocate
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff817bdc80-ffffffff817bdd5d: blkdev_issue_discard (STB_GLOBAL)
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
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffff8000105ec568)
Location: block/blk-lib.c:97
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffff8000105ec568-ffff8000105ec62c: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (c0798a08)
Location: block/blk-lib.c:97
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
c0798a08-c0798adc: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (c000000000781c70)
Location: block/blk-lib.c:97
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
c000000000781c70-c000000000781d70: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffe00042c140)
Location: block/blk-lib.c:97
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffe00042c140-ffffffe00042c1da: blkdev_issue_discard (STB_GLOBAL)
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
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814e5f50)
Location: block/blk-lib.c:97
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff814e5f50-ffffffff814e6012: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814d64c0)
Location: block/blk-lib.c:97
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff814d64c0-ffffffff814d6582: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814e1fe0)
Location: block/blk-lib.c:97
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff814e1fe0-ffffffff814e20a2: blkdev_issue_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814fae90)
Location: block/blk-lib.c:97
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff814fae90-ffffffff814faf52: blkdev_issue_discard (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int flags</code>
</li>
</ul>
</details>
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

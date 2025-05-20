# Function: <code>blkdev_issue_zeroout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, bool discard);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff813c2a30)
Location: block/blk-lib.c:285
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/extents.c:ext4_ext_zeroout
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff813c2a30-ffffffff813c2c7c: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, bool discard);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81406690)
Location: block/blk-lib.c:252
Inline: False
Direct callers:
  - fs/dax.c:__dax_zero_page_range
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81406690-ffffffff81406877: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, bool discard);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81420bb0)
Location: block/blk-lib.c:354
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/dax.c:__dax_zero_page_range
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81420bb0-ffffffff81420cee: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8142eb70)
Location: block/blk-lib.c:359
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_fallocate
  - fs/dax.c:__dax_zero_page_range
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff8142eb70-ffffffff8142ec2f: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81459e00)
Location: block/blk-lib.c:365
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_fallocate
  - fs/dax.c:__dax_zero_page_range
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81459e00-ffffffff8145a00c: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8148d560)
Location: block/blk-lib.c:393
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff8148d560-ffffffff8148d77e: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814a6df0)
Location: block/blk-lib.c:358
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814a6df0-ffffffff814a700e: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814d4d10)
Location: block/blk-lib.c:358
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_fallocate
  - fs/dax.c:__dax_zero_page_range
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814d4d10-ffffffff814d4f2b: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814ee000)
Location: block/blk-lib.c:358
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_fallocate
  - fs/dax.c:__dax_zero_page_range
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814ee000-ffffffff814ee219: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8154d980)
Location: block/blk-lib.c:358
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/inode.c:ext4_issue_zeroout
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff8154d980-ffffffff8154db7b: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81569b00)
Location: block/blk-lib.c:392
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/inode.c:ext4_issue_zeroout
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff81569b00-ffffffff81569cf5: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81571a50)
Location: block/blk-lib.c:392
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/inode.c:ext4_issue_zeroout
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff81571a50-ffffffff81571c66: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff815d6160)
Location: block/blk-lib.c:393
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/inode.c:ext4_issue_zeroout
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_fallocate
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff815d6160-ffffffff815d6376: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81682160)
Location: block/blk-lib.c:254
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/inode.c:ext4_issue_zeroout
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_fallocate
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff81682160-ffffffff81682372: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8173f7e0)
Location: block/blk-lib.c:252
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/inode.c:ext4_issue_zeroout
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_fallocate
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff8173f7e0-ffffffff8173f9f2: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8177bd20)
Location: block/blk-lib.c:252
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/inode.c:ext4_issue_zeroout
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_fallocate
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff8177bd20-ffffffff8177bf2c: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff817be110)
Location: block/blk-lib.c:252
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/inode.c:ext4_issue_zeroout
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_fallocate
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff817be110-ffffffff817be31c: blkdev_issue_zeroout (STB_GLOBAL)
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
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffff8000105ecbe8)
Location: block/blk-lib.c:358
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_fallocate
  - fs/dax.c:__dax_zero_page_range
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffff8000105ecbe8-ffff8000105ecdb0: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (c0799114)
Location: block/blk-lib.c:358
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
c0799114-c0799320: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (c0000000007825a0)
Location: block/blk-lib.c:358
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_fallocate
  - fs/dax.c:__dax_zero_page_range
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
c0000000007825a0-c000000000782830: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffe00042c6a2)
Location: block/blk-lib.c:358
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/dax.c:__dax_zero_page_range
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffe00042c6a2-ffffffe00042c80a: blkdev_issue_zeroout (STB_GLOBAL)
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
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814e65e0)
Location: block/blk-lib.c:358
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_fallocate
  - fs/dax.c:__dax_zero_page_range
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814e65e0-ffffffff814e67f9: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814d6b50)
Location: block/blk-lib.c:358
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_fallocate
  - fs/dax.c:__dax_zero_page_range
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814d6b50-ffffffff814d6d69: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814e2670)
Location: block/blk-lib.c:358
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_fallocate
  - fs/dax.c:__dax_zero_page_range
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814e2670-ffffffff814e2889: blkdev_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814fb4f0)
Location: block/blk-lib.c:358
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_fallocate
  - fs/dax.c:__dax_zero_page_range
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814fb4f0-ffffffff814fb709: blkdev_issue_zeroout (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool discard</code>
</li>
</ul>
</details>
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

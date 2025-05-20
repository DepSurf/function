# Function: <code>get_start_sect</code>

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
In fs/block_dev.c (ffffffff812477f8)
Location: include/linux/genhd.h:454
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_read_page
  - fs/block_dev.c:bdev_write_page
```
```
In block/blk-settings.c (ffffffff813bea76)
Location: include/linux/genhd.h:454
Inline: True
```
```
In block/ioctl.c (ffffffff813c90de)
Location: include/linux/genhd.h:454
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff813e638a)
Location: include/linux/genhd.h:454
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
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
In fs/block_dev.c (ffffffff8127005e)
Location: include/linux/genhd.h:443
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffff814029d6)
Location: include/linux/genhd.h:443
Inline: True
```
```
In block/ioctl.c (ffffffff8140d33f)
Location: include/linux/genhd.h:443
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff8142c63d)
Location: include/linux/genhd.h:443
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
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
In fs/block_dev.c (ffffffff8128325e)
Location: include/linux/genhd.h:434
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffff8141c676)
Location: include/linux/genhd.h:434
Inline: True
```
```
In block/ioctl.c (ffffffff814285f1)
Location: include/linux/genhd.h:434
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff8144643d)
Location: include/linux/genhd.h:434
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff81448e6a)
Location: include/linux/genhd.h:434
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
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
In fs/block_dev.c (ffffffff81290a0e)
Location: include/linux/genhd.h:428
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffff8142a5d6)
Location: include/linux/genhd.h:428
Inline: True
```
```
In block/ioctl.c (ffffffff81436941)
Location: include/linux/genhd.h:428
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff814549ba)
Location: include/linux/genhd.h:428
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff814573d9)
Location: include/linux/genhd.h:428
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/dax/super.c (ffffffff8163cec9)
Location: include/linux/genhd.h:428
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
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
In fs/block_dev.c (ffffffff812b36de)
Location: include/linux/genhd.h:420
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffff81455816)
Location: include/linux/genhd.h:420
Inline: True
```
```
In block/ioctl.c (ffffffff814626d1)
Location: include/linux/genhd.h:420
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff8148064d)
Location: include/linux/genhd.h:420
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff814830d6)
Location: include/linux/genhd.h:420
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/dax/super.c (ffffffff816a5c20)
Location: include/linux/genhd.h:420
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
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
In fs/block_dev.c (ffffffff812db5b0)
Location: include/linux/genhd.h:428
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffff81488b85)
Location: include/linux/genhd.h:428
Inline: True
```
```
In block/ioctl.c (ffffffff8149617e)
Location: include/linux/genhd.h:428
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff814b51c0)
Location: include/linux/genhd.h:428
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff814b7cdf)
Location: include/linux/genhd.h:428
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/dax/super.c (ffffffff816e1845)
Location: include/linux/genhd.h:428
Inline: True
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
In fs/block_dev.c (ffffffff812f0b00)
Location: include/linux/genhd.h:451
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffff814a2aa5)
Location: include/linux/genhd.h:451
Inline: True
```
```
In block/ioctl.c (ffffffff814affb3)
Location: include/linux/genhd.h:451
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff814c8a7d)
Location: include/linux/genhd.h:451
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff814cb7ba)
Location: include/linux/genhd.h:451
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/dax/super.c (ffffffff81704c65)
Location: include/linux/genhd.h:451
Inline: True
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
In fs/block_dev.c (ffffffff8131246e)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffff814d0b85)
Location: include/linux/genhd.h:458
Inline: True
```
```
In block/ioctl.c (ffffffff814de977)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff814f773e)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff814fa117)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/dax/super.c (ffffffff8173ea75)
Location: include/linux/genhd.h:458
Inline: True
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
In fs/block_dev.c (ffffffff813253be)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffff814e9f05)
Location: include/linux/genhd.h:458
Inline: True
```
```
In block/ioctl.c (ffffffff814f7db6)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff815152d7)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff81518276)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/dax/super.c (ffffffff81762c55)
Location: include/linux/genhd.h:458
Inline: True
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
In fs/block_dev.c (ffffffff813618de)
Location: include/linux/genhd.h:327
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffff81548f92)
Location: include/linux/genhd.h:327
Inline: True
Inline callers:
  - block/blk-settings.c:disk_stack_limits
```
```
In block/ioctl.c (ffffffff81558984)
Location: include/linux/genhd.h:327
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
```
In drivers/dax/super.c (ffffffff8182362d)
Location: include/linux/genhd.h:327
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
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
In fs/block_dev.c (ffffffff8136e66e)
Location: include/linux/genhd.h:268
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffff81564c9c)
Location: include/linux/genhd.h:268
Inline: True
Inline callers:
  - block/blk-settings.c:disk_stack_limits
```
```
In block/ioctl.c (ffffffff81574f89)
Location: include/linux/genhd.h:268
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
```
In drivers/dax/super.c (ffffffff81832349)
Location: include/linux/genhd.h:268
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/md/dm-table.c (ffffffff81980856)
Location: include/linux/genhd.h:268
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_set_device_limits
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
In fs/block_dev.c (ffffffff81374f7e)
Location: include/linux/genhd.h:240
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffff8156d2ec)
Location: include/linux/genhd.h:240
Inline: True
Inline callers:
  - block/blk-settings.c:disk_stack_limits
```
```
In block/ioctl.c (ffffffff8157d019)
Location: include/linux/genhd.h:240
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
```
In drivers/dax/super.c (ffffffff81815139)
Location: include/linux/genhd.h:240
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/md/dm-table.c (ffffffff81964a66)
Location: include/linux/genhd.h:240
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_set_device_limits
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
In block/bdev.c (ffffffff815c495e)
Location: include/linux/genhd.h:234
Inline: True
Inline callers:
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffff815d1915)
Location: include/linux/genhd.h:234
Inline: True
Inline callers:
  - block/blk-settings.c:disk_stack_limits
```
```
In block/ioctl.c (ffffffff815e2619)
Location: include/linux/genhd.h:234
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
```
In drivers/dax/super.c (ffffffff8189f959)
Location: include/linux/genhd.h:234
Inline: True
Inline callers:
  - drivers/dax/super.c:generic_fsdax_supported
```
```
In drivers/md/dm-table.c (ffffffff81a0ca06)
Location: include/linux/genhd.h:234
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_set_device_limits
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
In block/bdev.c (ffffffff8166f3a0)
Location: include/linux/blkdev.h:787
Inline: True
Inline callers:
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffff8167d435)
Location: include/linux/blkdev.h:787
Inline: True
Inline callers:
  - block/blk-settings.c:disk_stack_limits
```
```
In block/ioctl.c (ffffffff81691264)
Location: include/linux/blkdev.h:787
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
```
In drivers/dax/super.c (ffffffff819e940c)
Location: include/linux/blkdev.h:787
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
```
In drivers/md/dm-table.c (ffffffff81b75283)
Location: include/linux/blkdev.h:787
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_set_device_limits
```
```
In drivers/md/dm-linear.c (ffffffff81b77ffd)
Location: include/linux/blkdev.h:787
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_dax_recovery_write
  - drivers/md/dm-linear.c:linear_dax_zero_page_range
  - drivers/md/dm-linear.c:linear_dax_direct_access
```
```
In drivers/md/dm-stripe.c (ffffffff81b789dc)
Location: include/linux/blkdev.h:787
Inline: True
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
In block/bdev.c (ffffffff8172a720)
Location: include/linux/blkdev.h:775
Inline: True
Inline callers:
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffff81739f05)
Location: include/linux/blkdev.h:775
Inline: True
Inline callers:
  - block/blk-settings.c:disk_stack_limits
```
```
In block/ioctl.c (ffffffff8174fe8d)
Location: include/linux/blkdev.h:775
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
```
In drivers/dax/super.c (ffffffff81b65c4f)
Location: include/linux/blkdev.h:775
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
```
In drivers/md/dm-table.c (ffffffff81d123a5)
Location: include/linux/blkdev.h:775
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_set_device_limits
```
```
In drivers/md/dm-linear.c (ffffffff81d155ad)
Location: include/linux/blkdev.h:775
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_dax_recovery_write
  - drivers/md/dm-linear.c:linear_dax_zero_page_range
  - drivers/md/dm-linear.c:linear_dax_direct_access
```
```
In drivers/md/dm-stripe.c (ffffffff81d1602c)
Location: include/linux/blkdev.h:775
Inline: True
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
In block/blk-settings.c (ffffffff817765e5)
Location: include/linux/blkdev.h:759
Inline: True
Inline callers:
  - block/blk-settings.c:disk_stack_limits
```
```
In block/ioctl.c (ffffffff8178c0ab)
Location: include/linux/blkdev.h:759
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
```
In drivers/dax/super.c (ffffffff81bb926f)
Location: include/linux/blkdev.h:759
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
```
In drivers/md/dm-table.c (ffffffff81d7b762)
Location: include/linux/blkdev.h:759
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_set_device_limits
```
```
In drivers/md/dm-linear.c (ffffffff81d7e6fd)
Location: include/linux/blkdev.h:759
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_dax_recovery_write
  - drivers/md/dm-linear.c:linear_dax_zero_page_range
  - drivers/md/dm-linear.c:linear_dax_direct_access
```
```
In drivers/md/dm-stripe.c (ffffffff81d7f284)
Location: include/linux/blkdev.h:759
Inline: True
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
In block/blk-settings.c (ffffffff817b8915)
Location: include/linux/blkdev.h:737
Inline: True
Inline callers:
  - block/blk-settings.c:disk_stack_limits
```
```
In block/ioctl.c (ffffffff817ce84b)
Location: include/linux/blkdev.h:737
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
```
In drivers/dax/super.c (ffffffff81c0d8cc)
Location: include/linux/blkdev.h:737
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
```
In drivers/md/dm-table.c (ffffffff81e326e2)
Location: include/linux/blkdev.h:737
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_set_device_limits
```
```
In drivers/md/dm-linear.c (ffffffff81e35d1d)
Location: include/linux/blkdev.h:737
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_dax_recovery_write
  - drivers/md/dm-linear.c:linear_dax_zero_page_range
  - drivers/md/dm-linear.c:linear_dax_direct_access
```
```
In drivers/md/dm-stripe.c (ffffffff81e368a4)
Location: include/linux/blkdev.h:737
Inline: True
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
In fs/block_dev.c (ffff8000103df9f4)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (ffff8000105e821c)
Location: include/linux/genhd.h:458
Inline: True
```
```
In block/ioctl.c (ffff8000105f8460)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffff80001061c0f4)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffff80001061f944)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/dax/super.c (ffff800010962918)
Location: include/linux/genhd.h:458
Inline: True
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
In fs/block_dev.c (c05b7cc0)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (c0794e08)
Location: include/linux/genhd.h:458
Inline: True
```
```
In block/ioctl.c (c07a3888)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/blk-zoned.c (c07c74f4)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/dax/super.c (c0a39818)
Location: include/linux/genhd.h:458
Inline: True
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
In fs/block_dev.c (c0000000004e49d4)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (c00000000077ce00)
Location: include/linux/genhd.h:458
Inline: True
```
```
In block/ioctl.c (c000000000790b28)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (c0000000007baa98)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (c0000000007bf120)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/dax/super.c (c000000000a189a8)
Location: include/linux/genhd.h:458
Inline: True
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
In fs/block_dev.c (ffffffe0002967a0)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffe000428ee2)
Location: include/linux/genhd.h:458
Inline: True
```
```
In block/ioctl.c (ffffffe00043538a)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffe000452312)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/dax/super.c (ffffffe0005cff14)
Location: include/linux/genhd.h:458
Inline: True
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
In fs/block_dev.c (ffffffff8131d99e)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffff814e24e5)
Location: include/linux/genhd.h:458
Inline: True
```
```
In block/ioctl.c (ffffffff814f0396)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff8150d8b7)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff81510856)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/dax/super.c (ffffffff81717345)
Location: include/linux/genhd.h:458
Inline: True
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
In fs/block_dev.c (ffffffff8130e53e)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffff814d2e75)
Location: include/linux/genhd.h:458
Inline: True
```
```
In block/ioctl.c (ffffffff814e08d6)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff814fdce7)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff81500b76)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/dax/super.c (ffffffff816ef875)
Location: include/linux/genhd.h:458
Inline: True
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
In fs/block_dev.c (ffffffff8131b46e)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffff814de575)
Location: include/linux/genhd.h:458
Inline: True
```
```
In block/ioctl.c (ffffffff814ec426)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff81509947)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff8150c8e6)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/dax/super.c (ffffffff81756115)
Location: include/linux/genhd.h:458
Inline: True
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
In fs/block_dev.c (ffffffff8132d10e)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In block/blk-settings.c (ffffffff814f73d5)
Location: include/linux/genhd.h:458
Inline: True
```
```
In block/ioctl.c (ffffffff81505436)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (ffffffff81522fb7)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffffffff81525fc1)
Location: include/linux/genhd.h:458
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/dax/super.c (ffffffff81771585)
Location: include/linux/genhd.h:458
Inline: True
```
</details>
</li>
</ul>

## Differences

# Function: <code>blkdev_get_by_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81249340)
Location: fs/block_dev.c:1473
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - fs/ext4/super.c:ext4_load_journal
  - drivers/md/md.c:lock_rdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81249340-ffffffff81249389: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81271f10)
Location: fs/block_dev.c:1545
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - fs/ext4/super.c:ext4_fill_super
  - drivers/md/md.c:lock_rdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81271f10-ffffffff81271f59: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812854b0)
Location: fs/block_dev.c:1791
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - fs/ext4/super.c:ext4_fill_super
  - drivers/md/md.c:lock_rdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff812854b0-ffffffff812854f9: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81292b10)
Location: fs/block_dev.c:1718
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - fs/ext4/super.c:ext4_fill_super
  - drivers/md/md.c:lock_rdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81292b10-ffffffff81292b59: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b5940)
Location: fs/block_dev.c:1709
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - fs/ext4/super.c:ext4_load_journal
  - drivers/md/md.c:lock_rdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff812b5940-ffffffff812b5989: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dd7b0)
Location: fs/block_dev.c:1733
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - fs/ext4/super.c:ext4_load_journal
  - drivers/md/md.c:lock_rdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff812dd7b0-ffffffff812dd7f9: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f2d90)
Location: fs/block_dev.c:1766
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - fs/ext4/super.c:ext4_load_journal
  - drivers/md/md.c:lock_rdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff812f2d90-ffffffff812f2dd9: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813147f0)
Location: fs/block_dev.c:1806
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff813147f0-ffffffff8131483b: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81327be0)
Location: fs/block_dev.c:1804
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81327be0-ffffffff81327c2b: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81361610)
Location: fs/block_dev.c:1825
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:md_import_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81361610-ffffffff8136165b: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136e9b0)
Location: fs/block_dev.c:1422
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_swap_check
  - mm/swapfile.c:__do_sys_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_bszset
  - block/genhd.c:register_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8136e9b0-ffffffff8136eb41: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81375270)
Location: fs/block_dev.c:1425
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_bszset
  - block/genhd.c:register_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81375270-ffffffff813754b6: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bdev.c (ffffffff815c4ffa)
Location: block/bdev.c:789
Inline: True
Inline callers:
  - block/bdev.c:blkdev_get_by_path
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/bdev.c:blkdev_get_by_path
  - block/fops.c:blkdev_open
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_bszset
  - block/genhd.c:device_add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff815c4c30-ffffffff815c4f40: blkdev_get_by_dev.part.0 (STB_LOCAL)
ffffffff81cd7eb7-ffffffff81cd7ecb: blkdev_get_by_dev.part.0.cold (STB_LOCAL)
ffffffff815c4f40-ffffffff815c4f99: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bdev.c (ffffffff8166fa5a)
Location: block/bdev.c:787
Inline: True
Inline callers:
  - block/bdev.c:blkdev_get_by_path
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/bdev.c:blkdev_get_by_path
  - block/fops.c:blkdev_open
  - block/ioctl.c:blkdev_bszset
  - block/genhd.c:disk_scan_partitions
  - drivers/md/md.c:md_import_device
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8166f650-ffffffff8166f979: blkdev_get_by_dev.part.0 (STB_LOCAL)
ffffffff81e8b24a-ffffffff81e8b25f: blkdev_get_by_dev.part.0.cold (STB_LOCAL)
ffffffff8166f980-ffffffff8166f9ec: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bdev.c (ffffffff8172ae5a)
Location: block/bdev.c:786
Inline: True
Inline callers:
  - block/bdev.c:blkdev_get_by_path
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/bdev.c:blkdev_get_by_path
  - block/fops.c:blkdev_open
  - block/ioctl.c:blkdev_bszset
  - block/genhd.c:disk_scan_partitions
  - drivers/md/md.c:md_import_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8172aa30-ffffffff8172ad5f: blkdev_get_by_dev.part.0 (STB_LOCAL)
ffffffff82075a81-ffffffff82075a96: blkdev_get_by_dev.part.0.cold (STB_LOCAL)
ffffffff8172ad70-ffffffff8172addc: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, blk_mode_t mode, void *holder, const struct blk_holder_ops *hops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bdev.c (ffffffff817670d1)
Location: block/bdev.c:769
Inline: True
Inline callers:
  - block/bdev.c:blkdev_get_by_path
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - fs/ext4/super.c:ext4_get_dev_journal
  - block/bdev.c:blkdev_get_by_path
  - block/fops.c:blkdev_open
  - block/ioctl.c:blkdev_bszset
  - block/genhd.c:disk_scan_partitions
  - drivers/md/md.c:md_import_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81766c70-ffffffff81766fbd: blkdev_get_by_dev.part.0 (STB_LOCAL)
ffffffff820f5894-ffffffff820f58a9: blkdev_get_by_dev.part.0.cold (STB_LOCAL)
ffffffff81766fd0-ffffffff81767048: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e2b20)
Location: fs/block_dev.c:1804
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffff8000103e2b20-ffff8000103e2b98: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05bad34)
Location: fs/block_dev.c:1804
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
c05bad34-c05bad7c: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e8970)
Location: fs/block_dev.c:1804
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
  - drivers/md/md.c:lock_rdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
c0000000004e8970-c0000000004e8a34: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000298fb6)
Location: fs/block_dev.c:1804
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffe000298fb6-ffffffe000299024: blkdev_get_by_dev (STB_GLOBAL)
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
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813201c0)
Location: fs/block_dev.c:1804
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff813201c0-ffffffff8132020b: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81310d60)
Location: fs/block_dev.c:1804
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81310d60-ffffffff81310dab: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131dc90)
Location: fs/block_dev.c:1804
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8131dc90-ffffffff8131dcdb: blkdev_get_by_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct block_device *blkdev_get_by_dev(dev_t dev, fmode_t mode, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132f990)
Location: fs/block_dev.c:1804
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8132f990-ffffffff8132f9db: blkdev_get_by_dev (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct blk_holder_ops *hops</code>
</li>
<li>
<b>Param type changed. </b>
<code>fmode_t mode</code> ➡️ <code>blk_mode_t mode</code>
</li>
</ul>
</details>
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

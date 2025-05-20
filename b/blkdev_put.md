# Function: <code>blkdev_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81248cc0)
Location: fs/block_dev.c:1577
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapon
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:dm_put_table_device
```
**Symbols:**

```
ffffffff81248cc0-ffffffff81248dcd: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81271290)
Location: fs/block_dev.c:1649
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:device_add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81271290-ffffffff8127139d: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81285000)
Location: fs/block_dev.c:1895
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:device_add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81285000-ffffffff8128510d: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81292370)
Location: fs/block_dev.c:1817
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:device_add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81292370-ffffffff8129243a: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b5180)
Location: fs/block_dev.c:1810
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:device_add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff812b5180-ffffffff812b524a: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dd340)
Location: fs/block_dev.c:1831
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff812dd340-ffffffff812dd40a: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f2920)
Location: fs/block_dev.c:1864
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff812f2920-ffffffff812f29ea: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81314240)
Location: fs/block_dev.c:1904
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81314240-ffffffff8131431d: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81326bf0)
Location: fs/block_dev.c:1888
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81326bf0-ffffffff81326ccd: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81360fe0)
Location: fs/block_dev.c:1919
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:get_swap_writer
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_bszset
  - block/genhd.c:register_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81360fe0-ffffffff813610bd: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136df50)
Location: fs/block_dev.c:1596
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_swap_check
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_bszset
  - block/genhd.c:register_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8136df50-ffffffff8136e087: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81374910)
Location: fs/block_dev.c:1593
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_bszset
  - block/genhd.c:register_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81374910-ffffffff81374a47: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bdev.c (0)
Location: block/bdev.c:897
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bdev.c:blkdev_get_by_path
  - block/fops.c:blkdev_close
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_bszset
  - block/genhd.c:device_add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81cd7ea2-ffffffff81cd7eb7: blkdev_put.cold (STB_LOCAL)
ffffffff815c4600-ffffffff815c480b: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bdev.c (0)
Location: block/bdev.c:898
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bdev.c:blkdev_get_by_path
  - block/fops.c:blkdev_close
  - block/ioctl.c:blkdev_bszset
  - block/genhd.c:disk_scan_partitions
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81e8b224-ffffffff81e8b239: blkdev_put.cold (STB_LOCAL)
ffffffff8166ed10-ffffffff8166eeef: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bdev.c (0)
Location: block/bdev.c:897
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bdev.c:blkdev_get_by_path
  - block/fops.c:blkdev_close
  - block/ioctl.c:blkdev_bszset
  - block/genhd.c:disk_scan_partitions
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff82075a6c-ffffffff82075a81: blkdev_put.cold (STB_LOCAL)
ffffffff81729fe0-ffffffff8172a1c2: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void blkdev_put(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bdev.c (0)
Location: block/bdev.c:887
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bdev.c:blkdev_get_by_path
  - block/fops.c:blkdev_release
  - block/ioctl.c:blkdev_bszset
  - block/genhd.c:disk_scan_partitions
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff820f5864-ffffffff820f5879: blkdev_put.cold (STB_LOCAL)
ffffffff81766340-ffffffff81766517: blkdev_put (STB_GLOBAL)
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
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e1aa8)
Location: fs/block_dev.c:1888
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffff8000103e1aa8-ffff8000103e1bd8: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b8cf8)
Location: fs/block_dev.c:1888
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
c05b8cf8-c05b8e54: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e58f0)
Location: fs/block_dev.c:1888
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
c0000000004e58f0-c0000000004e5b18: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000297fb4)
Location: fs/block_dev.c:1888
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffe000297fb4-ffffffe0002980be: blkdev_put (STB_GLOBAL)
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
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131f1d0)
Location: fs/block_dev.c:1888
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8131f1d0-ffffffff8131f2ad: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130fd70)
Location: fs/block_dev.c:1888
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8130fd70-ffffffff8130fe4d: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131cca0)
Location: fs/block_dev.c:1888
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8131cca0-ffffffff8131cd7d: blkdev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blkdev_put(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132deb0)
Location: fs/block_dev.c:1888
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/super.c:kill_block_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/ioctl.c:blkdev_ioctl
  - block/genhd.c:__device_add_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8132deb0-ffffffff8132dfb5: blkdev_put (STB_GLOBAL)
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
<code>void *holder</code>
</li>
<li>
<b>Param removed. </b>
<code>fmode_t mode</code>
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

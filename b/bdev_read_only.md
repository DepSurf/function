# Function: <code>bdev_read_only</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff813c9920)
Location: block/genhd.c:1369
Inline: False
Direct callers:
  - fs/super.c:do_remount_sb
  - fs/block_dev.c:blkdev_write_iter
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - block/ioctl.c:blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
ffffffff813c9920-ffffffff813c9941: bdev_read_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8140dba0)
Location: block/genhd.c:1398
Inline: False
Direct callers:
  - fs/super.c:do_remount_sb
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__save_error_info
  - block/ioctl.c:blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
ffffffff8140dba0-ffffffff8140dbbe: bdev_read_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81428f30)
Location: block/genhd.c:1398
Inline: False
Direct callers:
  - fs/super.c:do_remount_sb
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__save_error_info
  - block/ioctl.c:blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
**Symbols:**

```
ffffffff81428f30-ffffffff81428f4e: bdev_read_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81437270)
Location: block/genhd.c:1421
Inline: False
Direct callers:
  - fs/super.c:do_remount_sb
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__save_error_info
  - block/ioctl.c:blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff81437270-ffffffff8143728c: bdev_read_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81463030)
Location: block/genhd.c:1505
Inline: False
Direct callers:
  - fs/super.c:do_remount_sb
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__save_error_info
  - block/ioctl.c:blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff81463030-ffffffff8146304c: bdev_read_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81496970)
Location: block/genhd.c:1540
Inline: False
Direct callers:
  - fs/super.c:do_remount_sb
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__save_error_info
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/ioctl.c:blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff81496970-ffffffff8149698e: bdev_read_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b0890)
Location: block/genhd.c:1565
Inline: False
Direct callers:
  - fs/super.c:do_remount_sb
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__save_error_info
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/ioctl.c:blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff814b0890-ffffffff814b08ae: bdev_read_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814deca0)
Location: block/genhd.c:1586
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__save_error_info
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/ioctl.c:blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff814deca0-ffffffff814decbe: bdev_read_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f80e0)
Location: block/genhd.c:1595
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__save_error_info
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/ioctl.c:blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff814f80e0-ffffffff814f80fe: bdev_read_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81558bf0)
Location: block/genhd.c:1808
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:blkdev_write_iter
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/ext4/super.c:__save_error_info
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/ioctl.c:blkdev_common_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff81558bf0-ffffffff81558c0e: bdev_read_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81575180)
Location: block/genhd.c:1658
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:blkdev_write_iter
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/super.c:ext4_handle_error
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/ioctl.c:blkdev_common_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff81575180-ffffffff81575198: bdev_read_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8157e250)
Location: block/genhd.c:1366
Inline: True
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:blkdev_write_iter
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/super.c:ext4_handle_error
  - block/blk-core.c:submit_bio_checks
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/ioctl.c:blkdev_common_ioctl
  - block/partitions/core.c:part_ro_show
  - block/blk-zoned.c:blkdev_zone_mgmt
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff8157e250-ffffffff8157e283: bdev_read_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff815e3805)
Location: block/genhd.c:1413
Inline: True
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - block/bdev.c:blkdev_get_by_path
  - block/fops.c:blkdev_write_iter
  - block/blk-core.c:submit_bio_checks
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/ioctl.c:blkdev_common_ioctl
  - block/partitions/core.c:part_ro_show
  - block/blk-zoned.c:blkdev_zone_mgmt
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff81cd8890-ffffffff81cd88b9: bdev_read_only.cold (STB_LOCAL)
ffffffff815e37d0-ffffffff815e382c: bdev_read_only (STB_GLOBAL)
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
In fs/super.c (ffffffff813f6839)
Location: include/linux/blkdev.h:776
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/ext4/super.c (ffffffff815291a8)
Location: include/linux/blkdev.h:776
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/ext4/orphan.c (ffffffff8153a5ce)
Location: include/linux/blkdev.h:776
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
```
```
In block/bdev.c (ffffffff8166fa8c)
Location: include/linux/blkdev.h:776
Inline: True
Inline callers:
  - block/bdev.c:blkdev_get_by_path
```
```
In block/fops.c (ffffffff81670293)
Location: include/linux/blkdev.h:776
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_iter
```
```
In block/blk-core.c (ffffffff816796a3)
Location: include/linux/blkdev.h:776
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-lib.c (ffffffff81682402)
Location: include/linux/blkdev.h:776
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff816908ed)
Location: include/linux/blkdev.h:776
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/partitions/core.c (ffffffff81695395)
Location: include/linux/blkdev.h:776
Inline: True
Inline callers:
  - block/partitions/core.c:part_ro_show
```
```
In block/blk-zoned.c (ffffffff816b7e26)
Location: include/linux/blkdev.h:776
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
```
In drivers/md/md.c (ffffffff81b5c3e2)
Location: include/linux/blkdev.h:776
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_read_only
  - drivers/md/md.c:rdev_read_only
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
In fs/super.c (ffffffff8147f959)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/ext4/super.c (ffffffff815c72d8)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/ext4/orphan.c (ffffffff815d8b5e)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
```
```
In block/bdev.c (ffffffff8172ae8c)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/bdev.c:blkdev_get_by_path
```
```
In block/fops.c (ffffffff8172b9b3)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_iter
```
```
In block/blk-core.c (ffffffff81735b5c)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-lib.c (ffffffff8173fa9d)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff8174f4d1)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/partitions/core.c (ffffffff81754475)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/partitions/core.c:part_ro_show
```
```
In block/blk-zoned.c (ffffffff81778422)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
```
In drivers/md/md.c (ffffffff81cf6872)
Location: include/linux/blkdev.h:764
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_read_only
  - drivers/md/md.c:rdev_read_only
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
In fs/super.c (ffffffff814b4715)
Location: include/linux/blkdev.h:748
Inline: True
Inline callers:
  - fs/super.c:reconfigure_super
```
```
In fs/ext4/super.c (ffffffff815ff03a)
Location: include/linux/blkdev.h:748
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/ext4/orphan.c (ffffffff816106fe)
Location: include/linux/blkdev.h:748
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
```
```
In block/bdev.c (ffffffff81767103)
Location: include/linux/blkdev.h:748
Inline: True
Inline callers:
  - block/bdev.c:blkdev_get_by_path
```
```
In block/fops.c (ffffffff81767a59)
Location: include/linux/blkdev.h:748
Inline: True
Inline callers:
  - block/fops.c:blkdev_mmap
  - block/fops.c:blkdev_write_iter
```
```
In block/blk-core.c (ffffffff81772082)
Location: include/linux/blkdev.h:748
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-lib.c (ffffffff8177bfca)
Location: include/linux/blkdev.h:748
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff8178bbc9)
Location: include/linux/blkdev.h:748
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/partitions/core.c (ffffffff81790585)
Location: include/linux/blkdev.h:748
Inline: True
Inline callers:
  - block/partitions/core.c:part_ro_show
```
```
In block/blk-zoned.c (ffffffff817b7cdb)
Location: include/linux/blkdev.h:748
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
```
In drivers/md/md.c (ffffffff81d5e312)
Location: include/linux/blkdev.h:748
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_read_only
  - drivers/md/md.c:rdev_read_only
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
In fs/super.c (ffffffff814e41b3)
Location: include/linux/blkdev.h:725
Inline: True
Inline callers:
  - fs/super.c:setup_bdev_super
  - fs/super.c:reconfigure_super
```
```
In fs/ext4/super.c (ffffffff81637c80)
Location: include/linux/blkdev.h:725
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/ext4/orphan.c (ffffffff816494be)
Location: include/linux/blkdev.h:725
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
```
```
In block/bdev.c (ffffffff817a8dd9)
Location: include/linux/blkdev.h:725
Inline: True
Inline callers:
  - block/bdev.c:bdev_open_by_path
```
```
In block/fops.c (ffffffff817a96b9)
Location: include/linux/blkdev.h:725
Inline: True
Inline callers:
  - block/fops.c:blkdev_mmap
  - block/fops.c:blkdev_write_iter
```
```
In block/blk-core.c (ffffffff817b4301)
Location: include/linux/blkdev.h:725
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-lib.c (ffffffff817be3ba)
Location: include/linux/blkdev.h:725
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/ioctl.c (ffffffff817ce34d)
Location: include/linux/blkdev.h:725
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/partitions/core.c (ffffffff817d3e25)
Location: include/linux/blkdev.h:725
Inline: True
Inline callers:
  - block/partitions/core.c:part_ro_show
```
```
In block/blk-zoned.c (ffffffff817fcbed)
Location: include/linux/blkdev.h:725
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
```
In drivers/md/md.c (ffffffff81e15172)
Location: include/linux/blkdev.h:725
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_read_only
  - drivers/md/md.c:rdev_read_only
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
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105f92f0)
Location: block/genhd.c:1595
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__save_error_info
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/ioctl.c:blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffff8000105f92f0-ffff8000105f9330: bdev_read_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a453c)
Location: block/genhd.c:1595
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__save_error_info
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/ioctl.c:blkdev_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
c07a453c-c07a4560: bdev_read_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c000000000791920)
Location: block/genhd.c:1595
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__save_error_info
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/ioctl.c:blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
c000000000791920-c000000000791948: bdev_read_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe000435ae0)
Location: block/genhd.c:1595
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__save_error_info
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/ioctl.c:blkdev_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffe000435ae0-ffffffe000435b14: bdev_read_only (STB_GLOBAL)
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
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f06c0)
Location: block/genhd.c:1595
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__save_error_info
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/ioctl.c:blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff814f06c0-ffffffff814f06de: bdev_read_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e0c00)
Location: block/genhd.c:1595
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__save_error_info
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/ioctl.c:blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff814e0c00-ffffffff814e0c1e: bdev_read_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814ec750)
Location: block/genhd.c:1595
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__save_error_info
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/ioctl.c:blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff814ec750-ffffffff814ec76e: bdev_read_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bdev_read_only(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81505720)
Location: block/genhd.c:1595
Inline: False
Direct callers:
  - fs/super.c:reconfigure_super
  - fs/block_dev.c:blkdev_get_by_path
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__save_error_info
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/ioctl.c:blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff81505720-ffffffff8150573e: bdev_read_only (STB_GLOBAL)
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

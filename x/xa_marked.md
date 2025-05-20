# Function: <code>xa_marked</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8120f141)
Location: include/linux/xarray.h:357
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/memfd.c (ffffffff812a8f89)
Location: include/linux/xarray.h:357
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/fs-writeback.c (ffffffff812e127d)
Location: include/linux/xarray.h:357
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff8136f382)
Location: include/linux/xarray.h:357
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
```
In lib/xarray.c (ffffffff81a16d6f)
Location: include/linux/xarray.h:357
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
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
In mm/page-writeback.c (ffffffff8121ec60)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/memfd.c (ffffffff812c5447)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff812ff9e5)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff813988d4)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
```
In lib/xarray.c (ffffffff81a868ff)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff81225fdc)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff8122c700)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/memfd.c (ffffffff812d6e1b)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff81314904)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff813b1364)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
```
In lib/xarray.c (ffffffff81abdbc6)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff81251116)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff8125a01c)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/memfd.c (ffffffff8130bf87)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8134ba5a)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff813fcfc0)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
```
In lib/xarray.c (ffffffff815fb286)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_expand
  - lib/xarray.c:xas_expand
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
In mm/filemap.c (ffffffff8125c7a6)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff81265778)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/memfd.c (ffffffff81317e47)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8135897a)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff8140f72d)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
```
In lib/xarray.c (ffffffff8161fdf4)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_expand
  - lib/xarray.c:xas_expand
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
In mm/filemap.c (ffffffff8125dbd8)
Location: include/linux/xarray.h:416
Inline: True
Inline callers:
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff8126a27a)
Location: include/linux/xarray.h:416
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/memfd.c (ffffffff8131e037)
Location: include/linux/xarray.h:416
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8135f37a)
Location: include/linux/xarray.h:416
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff81415aad)
Location: include/linux/xarray.h:416
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
```
In lib/xarray.c (ffffffff81603574)
Location: include/linux/xarray.h:416
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff81299e95)
Location: include/linux/xarray.h:416
Inline: True
Inline callers:
  - mm/filemap.c:filemap_range_needs_writeback
```
```
In mm/page-writeback.c (ffffffff812a6f0d)
Location: include/linux/xarray.h:416
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/memfd.c (ffffffff8136b417)
Location: include/linux/xarray.h:416
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff813adf8a)
Location: include/linux/xarray.h:416
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/ext4/inode.c (ffffffff81468fc9)
Location: include/linux/xarray.h:416
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
```
In lib/xarray.c (ffffffff81671f3e)
Location: include/linux/xarray.h:416
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff812f5861)
Location: include/linux/xarray.h:417
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/page-writeback.c (ffffffff812ff0e8)
Location: include/linux/xarray.h:417
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
```
```
In mm/memfd.c (ffffffff813e94a6)
Location: include/linux/xarray.h:417
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff81435109)
Location: include/linux/xarray.h:417
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/iomap/direct-io.c (ffffffff8148d72e)
Location: include/linux/xarray.h:417
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff814e8d9b)
Location: include/linux/xarray.h:417
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
```
In block/fops.c (ffffffff81670e52)
Location: include/linux/xarray.h:417
Inline: True
Inline callers:
  - block/fops.c:blkdev_read_iter
```
```
In lib/xarray.c (ffffffff8178c65a)
Location: include/linux/xarray.h:417
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff8135f71b)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/page-writeback.c (ffffffff8136980f)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
```
```
In mm/memfd.c (ffffffff81471486)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff814c3149)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/iomap/direct-io.c (ffffffff815209ab)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff815828ab)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_do_writepages
```
```
In block/fops.c (ffffffff8172c582)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - block/fops.c:blkdev_read_iter
```
```
In lib/xarray.c (ffffffff82049cfa)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff81392153)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - mm/filemap.c:kiocb_write_and_wait
```
```
In mm/page-writeback.c (ffffffff8139b9ac)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
```
```
In mm/memfd.c (ffffffff814a59b0)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff814f8529)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/ext4/inode.c (ffffffff815b94a1)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_do_writepages
```
```
In lib/xarray.c (ffffffff820c7e53)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff813ba1e3)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - mm/filemap.c:kiocb_write_and_wait
```
```
In mm/page-writeback.c (ffffffff813c43fb)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
```
```
In mm/memfd.c (ffffffff814d6960)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8152cca9)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/ext4/inode.c (ffffffff815f2221)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_do_writepages
```
```
In lib/xarray.c (ffffffff821a27d3)
Location: include/linux/xarray.h:418
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffff8000102b31cc)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffff8000102bc084)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/memfd.c (ffff80001037bdb0)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffff8000103ca754)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffff800010485cc8)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
```
In lib/xarray.c (ffff800010d99038)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
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
In mm/filemap.c (c04e0428)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (c04e7034)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/memfd.c (c0566b74)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (c05a6d2c)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (c0647a10)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
```
In lib/xarray.c (c0e95a50)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
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
In mm/filemap.c (c000000000369d3c)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (c000000000373960)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/memfd.c (c000000000471290)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (c0000000004cc118)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (c0000000005ab750)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
```
In lib/xarray.c (c000000000ede984)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffe0001d8948)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffe0001de242)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/memfd.c (ffffffe000252594)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffe000288918)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffe00030de44)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
```
In lib/xarray.c (ffffffe0008c209c)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff8121e62c)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff81224d50)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/memfd.c (ffffffff812cf3fb)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8130cee4)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff813a9944)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
```
In lib/xarray.c (ffffffff81a5ca16)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff812117ec)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff81217eea)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/memfd.c (ffffffff812c007f)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff812fdb04)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff8139a3d4)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
```
In lib/xarray.c (ffffffff81a19af6)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff8121c3cc)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff81222af0)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/memfd.c (ffffffff812cd20b)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8130acd4)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff813a71a4)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
```
In lib/xarray.c (ffffffff81ac8e06)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff8122b45c)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff81231cd0)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/memfd.c (ffffffff812ddf98)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8131c40e)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff813bb9b4)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
```
In lib/xarray.c (ffffffff81ad52e6)
Location: include/linux/xarray.h:414
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
</details>
</li>
</ul>

## Differences

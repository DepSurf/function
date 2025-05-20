# Function: <code>mapping_tagged</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mapping_tagged(struct address_space *mapping, int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81198940)
Location: mm/page-writeback.c:2798
Inline: False
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff81198940-ffffffff81198954: mapping_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int mapping_tagged(struct address_space *mapping, int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811add6a)
Location: mm/page-writeback.c:2858
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff811ad9a0-ffffffff811ad9b4: mapping_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int mapping_tagged(struct address_space *mapping, int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811be392)
Location: mm/page-writeback.c:2825
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff811bdf00-ffffffff811bdf14: mapping_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mapping_tagged(struct address_space *mapping, int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c7781)
Location: mm/page-writeback.c:2834
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff811c60b0-ffffffff811c60c4: mapping_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mapping_tagged(struct address_space *mapping, int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811dc5c2)
Location: mm/page-writeback.c:2817
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff811daec0-ffffffff811daed4: mapping_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int mapping_tagged(struct address_space *mapping, int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811fe8f7)
Location: mm/page-writeback.c:2814
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff811fbf70-ffffffff811fbf84: mapping_tagged (STB_GLOBAL)
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
In mm/page-writeback.c (ffffffff8120f141)
Location: include/linux/fs.h:500
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In fs/fs-writeback.c (ffffffff812e127d)
Location: include/linux/fs.h:500
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff8136f382)
Location: include/linux/fs.h:500
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
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
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In fs/fs-writeback.c (ffffffff812ff9e5)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff813988d4)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
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
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff8122c700)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In fs/fs-writeback.c (ffffffff81314904)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff813b1364)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
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
Location: include/linux/fs.h:522
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff8125a01c)
Location: include/linux/fs.h:522
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In fs/fs-writeback.c (ffffffff8134ba5a)
Location: include/linux/fs.h:522
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff813fcfc0)
Location: include/linux/fs.h:522
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
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
Location: include/linux/fs.h:486
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff81265778)
Location: include/linux/fs.h:486
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In fs/fs-writeback.c (ffffffff8135897a)
Location: include/linux/fs.h:486
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff8140f72d)
Location: include/linux/fs.h:486
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
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
Location: include/linux/fs.h:487
Inline: True
Inline callers:
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff8126a27a)
Location: include/linux/fs.h:487
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In fs/fs-writeback.c (ffffffff8135f37a)
Location: include/linux/fs.h:487
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff81415aad)
Location: include/linux/fs.h:487
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
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
Location: include/linux/fs.h:494
Inline: True
Inline callers:
  - mm/filemap.c:filemap_range_needs_writeback
```
```
In mm/page-writeback.c (ffffffff812a6f0d)
Location: include/linux/fs.h:494
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In fs/fs-writeback.c (ffffffff813adf8a)
Location: include/linux/fs.h:494
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
Location: include/linux/fs.h:494
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
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
Location: include/linux/fs.h:444
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/page-writeback.c (ffffffff812ff0e8)
Location: include/linux/fs.h:444
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
```
```
In fs/fs-writeback.c (ffffffff81435109)
Location: include/linux/fs.h:444
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
Location: include/linux/fs.h:444
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff814e8d9b)
Location: include/linux/fs.h:444
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
```
```
In block/fops.c (ffffffff81670e52)
Location: include/linux/fs.h:444
Inline: True
Inline callers:
  - block/fops.c:blkdev_read_iter
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
Location: include/linux/fs.h:459
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/page-writeback.c (ffffffff8136980f)
Location: include/linux/fs.h:459
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
```
```
In fs/fs-writeback.c (ffffffff814c3149)
Location: include/linux/fs.h:459
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
Location: include/linux/fs.h:459
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff815828ab)
Location: include/linux/fs.h:459
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_do_writepages
```
```
In block/fops.c (ffffffff8172c582)
Location: include/linux/fs.h:459
Inline: True
Inline callers:
  - block/fops.c:blkdev_read_iter
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
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - mm/filemap.c:kiocb_write_and_wait
```
```
In mm/page-writeback.c (ffffffff8139b9ac)
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
```
```
In fs/fs-writeback.c (ffffffff814f8529)
Location: include/linux/fs.h:474
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
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_do_writepages
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
Location: include/linux/fs.h:507
Inline: True
Inline callers:
  - mm/filemap.c:kiocb_write_and_wait
```
```
In mm/page-writeback.c (ffffffff813c43fb)
Location: include/linux/fs.h:507
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
```
```
In fs/fs-writeback.c (ffffffff8152cca9)
Location: include/linux/fs.h:507
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
Location: include/linux/fs.h:507
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_do_writepages
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
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffff8000102bc084)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In fs/fs-writeback.c (ffff8000103ca754)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffff800010485cc8)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
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
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (c04e7034)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In fs/fs-writeback.c (c05a6d2c)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (c0647a10)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
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
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (c000000000373960)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In fs/fs-writeback.c (c0000000004cc118)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (c0000000005ab750)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
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
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffe0001de242)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In fs/fs-writeback.c (ffffffe000288918)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffe00030de44)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
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
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff81224d50)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In fs/fs-writeback.c (ffffffff8130cee4)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff813a9944)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
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
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff81217eea)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In fs/fs-writeback.c (ffffffff812fdb04)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff8139a3d4)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
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
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff81222af0)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In fs/fs-writeback.c (ffffffff8130acd4)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff813a71a4)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
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
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff81231cd0)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In fs/fs-writeback.c (ffffffff8131c40e)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
```
```
In fs/ext4/inode.c (ffffffff813bb9b4)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_writepages
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
</ul>

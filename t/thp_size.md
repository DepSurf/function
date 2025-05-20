# Function: <code>thp_size</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8126b0bd)
Location: include/linux/huge_mm.h:477
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/page_vma_mapped.c (ffffffff812adb1f)
Location: include/linux/huge_mm.h:477
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812af8ed)
Location: include/linux/huge_mm.h:477
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/page_io.c (ffffffff812c32dc)
Location: include/linux/huge_mm.h:477
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In mm/memory-failure.c (ffffffff8130c863)
Location: include/linux/huge_mm.h:477
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/iomap/buffered-io.c (ffffffff813bc08f)
Location: include/linux/huge_mm.h:477
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
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
In mm/filemap.c (ffffffff81263300)
Location: include/linux/huge_mm.h:494
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
```
```
In mm/truncate.c (ffffffff812701cf)
Location: include/linux/huge_mm.h:494
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/page_io.c (ffffffff812caadb)
Location: include/linux/huge_mm.h:494
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff813c356c)
Location: include/linux/huge_mm.h:494
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
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
In mm/filemap.c (ffffffff8129fa3d)
Location: include/linux/huge_mm.h:493
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
```
```
In mm/truncate.c (ffffffff812ad45f)
Location: include/linux/huge_mm.h:493
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/page_io.c (ffffffff8130faeb)
Location: include/linux/huge_mm.h:493
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff8141245a)
Location: include/linux/huge_mm.h:493
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8137a501)
Location: include/linux/mm.h:964
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff813f7fa5)
Location: include/linux/mm.h:1094
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:swap_writepage_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8142b1df)
Location: include/linux/mm.h:1280
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_bdev_sync
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:swap_writepage_fs
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences

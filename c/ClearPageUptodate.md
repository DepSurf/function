# Function: <code>ClearPageUptodate</code>

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
In mm/filemap.c (ffffffff8118d8e1)
Location: include/linux/page-flags.h:376
Inline: True
```
```
In mm/page_io.c (ffffffff811d1f8e)
Location: include/linux/page-flags.h:376
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff8120193d)
Location: include/linux/page-flags.h:376
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inode.c (ffffffff8129611d)
Location: include/linux/page-flags.h:376
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff812e2d8f)
Location: include/linux/page-flags.h:376
Inline: True
Inline callers:
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff812f38c8)
Location: include/linux/page-flags.h:376
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81303e16)
Location: include/linux/page-flags.h:376
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In drivers/md/md.c (ffffffff81691fdb)
Location: include/linux/page-flags.h:376
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffffffff811a0512)
Location: include/linux/page-flags.h:453
Inline: True
```
```
In mm/page_io.c (ffffffff811efae2)
Location: include/linux/page-flags.h:453
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff812267fc)
Location: include/linux/page-flags.h:453
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inode.c (ffffffff812c36f5)
Location: include/linux/page-flags.h:453
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff81312c9f)
Location: include/linux/page-flags.h:453
Inline: True
Inline callers:
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff81327d93)
Location: include/linux/page-flags.h:453
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff813382be)
Location: include/linux/page-flags.h:453
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In drivers/md/md.c (ffffffff816f5f8f)
Location: include/linux/page-flags.h:453
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffffffff811af6ea)
Location: include/linux/page-flags.h:469
Inline: True
```
```
In mm/page_io.c (ffffffff81200482)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff81238dcc)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inode.c (ffffffff812d8d91)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff81328c4f)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff8133dad0)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e08e)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In drivers/md/md.c (ffffffff817277bb)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffffffff811b659c)
Location: include/linux/page-flags.h:472
Inline: True
```
```
In mm/page_io.c (ffffffff8120b0dd)
Location: include/linux/page-flags.h:472
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff812450ec)
Location: include/linux/page-flags.h:472
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inode.c (ffffffff812fd030)
Location: include/linux/page-flags.h:472
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff8131e710)
Location: include/linux/page-flags.h:472
Inline: True
Inline callers:
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff813518cc)
Location: include/linux/page-flags.h:472
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81362cd7)
Location: include/linux/page-flags.h:472
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In drivers/md/md.c (ffffffff8174007c)
Location: include/linux/page-flags.h:472
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffffffff811ca91c)
Location: include/linux/page-flags.h:473
Inline: True
```
```
In mm/page_io.c (ffffffff8122460d)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff8126500c)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inode.c (ffffffff813218ff)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff81342d50)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff813763dc)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81387937)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In drivers/md/md.c (ffffffff817b272b)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffffffff811eb96c)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In mm/page_io.c (ffffffff81246b1e)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff8128932c)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inode.c (ffffffff8134f954)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff81370bda)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff813a4cec)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813b6c95)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In drivers/md/md.c (ffffffff817f5c9b)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffffffff811fc4ec)
Location: include/linux/page-flags.h:497
Inline: True
```
```
In mm/page_io.c (ffffffff8125af57)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff8129e27c)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/iomap.c (ffffffff8132358b)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - fs/iomap.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (ffffffff81367b34)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff8138906c)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff813bdaec)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813d01e5)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In drivers/md/md.c (ffffffff81821c1b)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffffffff81213c0c)
Location: include/linux/page-flags.h:530
Inline: True
```
```
In mm/page_io.c (ffffffff81275f62)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff812b944c)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/iomap/buffered-io.c (ffffffff8134b67b)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (ffffffff81390e2d)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff813b321d)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff813e83cc)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813faddb)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In drivers/md/md.c (ffffffff8186478b)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffffffff812213e4)
Location: include/linux/page-flags.h:530
Inline: True
```
```
In mm/page_io.c (ffffffff81285a3d)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff812cb33c)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/iomap/buffered-io.c (ffffffff8136393b)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (ffffffff813a97ed)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff813cc297)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff8140246c)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81414cab)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In drivers/md/md.c (ffffffff818964cb)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffffffff8124f420)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In mm/page_io.c (ffffffff812b7e09)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff8130165c)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/iomap/buffered-io.c (ffffffff813ab93a)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (ffffffff813f635f)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff81418348)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff81450bbc)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81462f46)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In drivers/md/md.c (ffffffff81963e3c)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffffffff81259dc0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In mm/page_io.c (ffffffff812c34b9)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff8130d71c)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/iomap/buffered-io.c (ffffffff813bc3c9)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_read_page_end_io
```
```
In fs/ext4/inode.c (ffffffff81408cbf)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff8142bea8)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff8146d0cc)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81bee442)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In drivers/md/md.c (ffffffff8196a72c)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffffffff8125e000)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In mm/page_io.c (ffffffff812ca239)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff81313a63)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/iomap/buffered-io.c (ffffffff813c38a7)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (ffffffff8140ebc1)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff81432b68)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff814727bc)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81be04a2)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/file.c (ffffffff81496fc2)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
```
```
In drivers/md/md.c (ffffffff8194e53c)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffffffff8129a720)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In mm/page_io.c (ffffffff8130f259)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff8135ed53)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/iomap/buffered-io.c (ffffffff81413ede)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (ffffffff81461e6e)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff81486338)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff814c903c)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81cd0c03)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/file.c (ffffffff814ee8a2)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
```
```
In drivers/md/md.c (ffffffff819f393c)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffffffff812f1f44)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In mm/page_io.c (ffffffff8137902e)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff813d9459)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/readpage.c (ffffffff81509c3a)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff8155544a)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81e83e66)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/file.c (ffffffff8157f6d9)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
```
```
In drivers/md/md.c (ffffffff81b5d5cb)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/page_io.c (ffffffff813f69ce)
Location: include/linux/page-flags.h:758
Inline: True
Inline callers:
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff8145f729)
Location: include/linux/page-flags.h:758
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/readpage.c (ffffffff815a489a)
Location: include/linux/page-flags.h:758
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ecryptfs/mmap.c (ffffffff8160cc5e)
Location: include/linux/page-flags.h:758
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/file.c (ffffffff816253b2)
Location: include/linux/page-flags.h:758
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
```
```
In drivers/md/md.c (ffffffff81cf751f)
Location: include/linux/page-flags.h:758
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/page_io.c (ffffffff8142985e)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:__end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff81495939)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ecryptfs/mmap.c (ffffffff81644ac3)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/file.c (ffffffff8165d728)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
```
```
In drivers/md/md.c (ffffffff81d5ee1b)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In fs/ecryptfs/mmap.c (ffffffff8167dff0)
Location: include/linux/page-flags.h:773
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/file.c (ffffffff81697475)
Location: include/linux/page-flags.h:773
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
```
```
In drivers/md/md.c (ffffffff81e1608b)
Location: include/linux/page-flags.h:773
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffff8000102b08ac)
Location: include/linux/page-flags.h:530
Inline: True
```
```
In mm/page_io.c (ffff800010320164)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffff80001036e7b4)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/iomap/buffered-io.c (ffff80001042b0e0)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (ffff80001047f058)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffff8000104a46b4)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/hugetlbfs/inode.c (ffff8000104e1b4c)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffff8000104f5d24)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In drivers/md/md.c (ffff800010ae9a78)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (c04db620)
Location: include/linux/page-flags.h:530
Inline: True
```
```
In mm/page_io.c (c05389cc)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/iomap/buffered-io.c (c05f2e44)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (c063ef88)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (c06662a4)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ecryptfs/mmap.c (c06b34bc)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In drivers/md/md.c (c0bccd70)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (c000000000363284)
Location: include/linux/page-flags.h:530
Inline: True
```
```
In mm/page_io.c (c0000000003f502c)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (c00000000045fc54)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/iomap/buffered-io.c (c00000000053aae0)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (c0000000005a1910)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (c0000000005d16b0)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/hugetlbfs/inode.c (c00000000061d244)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (c000000000636a50)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In drivers/md/md.c (c000000000bd72b0)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffffffe0001d4be6)
Location: include/linux/page-flags.h:530
Inline: True
```
```
In mm/page_io.c (ffffffe000221858)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/iomap/buffered-io.c (ffffffe0002c7e08)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (ffffffe000307042)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffe000325848)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffe000354aa2)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffe000364b60)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In drivers/md/md.c (ffffffe0006de19e)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffffffff81219a34)
Location: include/linux/page-flags.h:530
Inline: True
```
```
In mm/page_io.c (ffffffff8127e08d)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff812c391c)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/iomap/buffered-io.c (ffffffff8135bf1b)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (ffffffff813a1dcd)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff813c4877)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff813faa4c)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8140d28b)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In drivers/md/md.c (ffffffff8183c34b)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffffffff8120cc44)
Location: include/linux/page-flags.h:530
Inline: True
```
```
In mm/page_io.c (ffffffff8126febd)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff812b495c)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/iomap/buffered-io.c (ffffffff8134cbbb)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (ffffffff8139285d)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff813b52f7)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff813eb4cc)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813fdd0b)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In drivers/md/md.c (ffffffff818039ab)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffffffff812177d4)
Location: include/linux/page-flags.h:530
Inline: True
```
```
In mm/page_io.c (ffffffff8127be2d)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff812c172c)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/iomap/buffered-io.c (ffffffff813599eb)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (ffffffff8139f62d)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff813c1d07)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff813f7dcc)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a60b)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In drivers/md/md.c (ffffffff8188b97b)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
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
In mm/filemap.c (ffffffff81226884)
Location: include/linux/page-flags.h:530
Inline: True
```
```
In mm/page_io.c (ffffffff8128ba0d)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/memory-failure.c (ffffffff812d21ec)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/iomap/buffered-io.c (ffffffff8136d0db)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (ffffffff813b3ccd)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff813d6e87)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff8140db1c)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81420305)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In drivers/md/md.c (ffffffff818aabeb)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
```
</details>
</li>
</ul>

## Differences

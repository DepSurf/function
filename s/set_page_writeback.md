# Function: <code>set_page_writeback</code>

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
In mm/page_io.c (ffffffff811d2321)
Location: include/linux/page-flags.h:386
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffffffff81246ab0)
Location: include/linux/page-flags.h:386
Inline: True
```
```
In fs/block_dev.c (ffffffff812478c1)
Location: include/linux/page-flags.h:386
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (ffffffff8124dd2c)
Location: include/linux/page-flags.h:386
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff8129fe5e)
Location: include/linux/page-flags.h:386
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffffffff81319a46)
Location: include/linux/page-flags.h:386
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/page_io.c (ffffffff811eff38)
Location: include/linux/page-flags.h:463
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffffffff8126d208)
Location: include/linux/page-flags.h:463
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (ffffffff81270054)
Location: include/linux/page-flags.h:463
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (ffffffff812764af)
Location: include/linux/page-flags.h:463
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff812ce75e)
Location: include/linux/page-flags.h:463
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffffffff8134eba8)
Location: include/linux/page-flags.h:463
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/page_io.c (ffffffff8120087b)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffffffff8128045f)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (ffffffff81283254)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (ffffffff8128a189)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff812e453e)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffffffff813644b8)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/page_io.c (ffffffff8120b4d4)
Location: include/linux/page-flags.h:482
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffffffff8128ddc2)
Location: include/linux/page-flags.h:482
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (ffffffff81290a04)
Location: include/linux/page-flags.h:482
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (ffffffff81296edd)
Location: include/linux/page-flags.h:482
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff8131e21e)
Location: include/linux/page-flags.h:482
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffffffff81378cc8)
Location: include/linux/page-flags.h:482
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/page_io.c (ffffffff81224994)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffffffff812b09c3)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (ffffffff812b36d4)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (ffffffff812b9ffe)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff8134283e)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffffffff8139db68)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/page_io.c (ffffffff8124705a)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffffffff812d87ed)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (ffffffff812db5a6)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (ffffffff812e2c05)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff813706be)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffffffff813ccf38)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/page_io.c (ffffffff8125b49f)
Location: include/linux/page-flags.h:507
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffffffff812edcbd)
Location: include/linux/page-flags.h:507
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (ffffffff812f0af6)
Location: include/linux/page-flags.h:507
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (ffffffff812f7867)
Location: include/linux/page-flags.h:507
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff81388b4e)
Location: include/linux/page-flags.h:507
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffffffff813e62c0)
Location: include/linux/page-flags.h:507
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/page_io.c (ffffffff812765ea)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffffffff8130f452)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (ffffffff81312464)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (ffffffff81317eb4)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff813b2c3c)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffffffff8141221d)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/page_io.c (ffffffff812860da)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffffffff813223b2)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (ffffffff813253b4)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (ffffffff8132ad2a)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff813cbc9c)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffffffff8142bf61)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/page_io.c (ffffffff812b83d6)
Location: include/linux/page-flags.h:556
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffffffff8135c61c)
Location: include/linux/page-flags.h:556
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (ffffffff813618d4)
Location: include/linux/page-flags.h:556
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (ffffffff81364946)
Location: include/linux/page-flags.h:556
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff813ab82c)
Location: include/linux/page-flags.h:556
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
```
In fs/ext4/page-io.c (ffffffff81417dfc)
Location: include/linux/page-flags.h:556
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffffffff8147bcbf)
Location: include/linux/page-flags.h:556
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/page_io.c (ffffffff812c3aa3)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffffffff8136aaa3)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (ffffffff8136e664)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (ffffffff81371913)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff813bc218)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
```
In fs/ext4/page-io.c (ffffffff8142b901)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffffffff81496b24)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/page_io.c (ffffffff812ca86d)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffffffff813701b7)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (ffffffff81374f74)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (ffffffff81378be3)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff813c36f6)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
```
In fs/ext4/page-io.c (ffffffff81432521)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffffffff8149bc1d)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/page_io.c (ffffffff8130f86d)
Location: include/linux/page-flags.h:580
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffffffff813bed33)
Location: include/linux/page-flags.h:580
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff813c55bd)
Location: include/linux/page-flags.h:580
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff81413d5e)
Location: include/linux/page-flags.h:580
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
```
In fs/ext4/page-io.c (ffffffff81485de1)
Location: include/linux/page-flags.h:580
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffffffff814f360f)
Location: include/linux/page-flags.h:580
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In block/bdev.c (ffffffff815c4954)
Location: include/linux/page-flags.h:580
Inline: True
Inline callers:
  - block/bdev.c:bdev_write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool set_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff81300e90)
Location: mm/folio-compat.c:76
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/bdev.c:bdev_write_page
```
**Symbols:**

```
ffffffff81300e90-ffffffff81300eef: set_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool set_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8136b720)
Location: mm/folio-compat.c:48
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_fs
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/bdev.c:bdev_write_page
```
**Symbols:**

```
ffffffff8136b720-ffffffff8136b77f: set_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool set_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8139d920)
Location: mm/folio-compat.c:49
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:swap_writepage_fs
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8139d920-ffffffff8139d990: set_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff813c7580)
Location: mm/folio-compat.c:49
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff813c7580-ffffffff813c75f3: set_page_writeback (STB_GLOBAL)
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
In mm/page_io.c (ffff800010320648)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffff8000103db19c)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (ffff8000103df9e8)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (ffff8000103e6320)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffff8000104a3e24)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffff80001050fe44)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/page_io.c (c05390d8)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (c05b4624)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (c05b7cb4)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (c05be07c)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (c0665cd8)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (c06cb660)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/page_io.c (c0000000003f5820)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (c0000000004e0520)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (c0000000004e49c0)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (c0000000004ec714)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (c0000000005d1250)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (c000000000657648)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/page_io.c (ffffffe000221d50)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffffffe000293b54)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (ffffffe000296794)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (ffffffe00029b698)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffe00032537c)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffffffe00037a69e)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/page_io.c (ffffffff8127e72a)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffffffff8131a992)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (ffffffff8131d994)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (ffffffff8132330a)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff813c427c)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffffffff81424541)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/page_io.c (ffffffff8127055a)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffffffff8130b532)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (ffffffff8130e534)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (ffffffff81313eaa)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff813b4cfc)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffffffff81414fc1)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/page_io.c (ffffffff8127c4ca)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffffffff81318462)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (ffffffff8131b464)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (ffffffff81320dda)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff813c170c)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffffffff814206e1)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/page_io.c (ffffffff8128c09a)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
```
```
In fs/buffer.c (ffffffff8132a082)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (ffffffff8132d104)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
```
```
In fs/mpage.c (ffffffff81332afa)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (ffffffff813d686c)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/file.c (ffffffff814374a7)
Location: include/linux/page-flags.h:540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
</ul>

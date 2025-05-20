# Function: <code>mapping_gfp_constraint</code>

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
In mm/filemap.c (0)
Location: include/linux/pagemap.h:73
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/pagemap.h:73
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/pagemap.h:73
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/pagemap.h:73
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/pagemap.h:73
Inline: True
```
```
In fs/mpage.c (ffffffff8124e6dc)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:mpage_readpage
```
```
In fs/ext4/inode.c (0)
Location: include/linux/pagemap.h:73
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/pagemap.h:73
Inline: True
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
In mm/filemap.c (ffffffff811a3277)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_read_iter
```
```
In fs/namei.c (ffffffff8123db25)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/splice.c (ffffffff81266ced)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - fs/splice.c:__generic_file_splice_read
```
```
In fs/buffer.c (ffffffff8126ca74)
Location: include/linux/pagemap.h:73
Inline: True
```
```
In fs/mpage.c (ffffffff81277014)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff812c6392)
Location: include/linux/pagemap.h:73
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff811b306d)
Location: include/linux/pagemap.h:84
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_read_iter
```
```
In fs/namei.c (0)
Location: include/linux/pagemap.h:84
Inline: True
```
```
In fs/buffer.c (ffffffff8127fd58)
Location: include/linux/pagemap.h:84
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
```
In fs/mpage.c (ffffffff8128ad07)
Location: include/linux/pagemap.h:84
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff812dbbf2)
Location: include/linux/pagemap.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff811b9e62)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_read_iter
```
```
In fs/namei.c (0)
Location: include/linux/pagemap.h:103
Inline: True
```
```
In fs/buffer.c (ffffffff8128d2ef)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
```
In fs/mpage.c (ffffffff81297b04)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff81300481)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff811cf1f4)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_read_iter
```
```
In fs/namei.c (ffffffff8127edd5)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffffffff812afe33)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
```
In fs/mpage.c (ffffffff812badc4)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff81324ca1)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff811ee825)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In fs/namei.c (ffffffff812a5765)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffffffff812d8077)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
```
In fs/mpage.c (ffffffff812e3958)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff81352f01)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff8120003e)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In fs/namei.c (ffffffff812ba8d5)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffffffff812ed0e7)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
```
In fs/mpage.c (ffffffff812f7ffd)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap.c (ffffffff81324719)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/iomap.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff8136b02e)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff81217091)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In fs/namei.c (ffffffff812d74d5)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffffffff8130e8a0)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
```
In fs/mpage.c (ffffffff8131863f)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8134b939)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff81394543)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff812249a1)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In fs/namei.c (ffffffff812e9035)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffffffff813218bc)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
```
In fs/mpage.c (ffffffff8132b49d)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff81363c09)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff813acec3)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff8125265d)
Location: include/linux/pagemap.h:107
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In fs/namei.c (ffffffff813216f5)
Location: include/linux/pagemap.h:107
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffffffff8135bc83)
Location: include/linux/pagemap.h:107
Inline: True
Inline callers:
  - fs/buffer.c:grow_dev_page
```
```
In fs/mpage.c (ffffffff81365136)
Location: include/linux/pagemap.h:107
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff813ab00d)
Location: include/linux/pagemap.h:107
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff813f9132)
Location: include/linux/pagemap.h:107
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff8125bed8)
Location: include/linux/pagemap.h:109
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read_get_pages
```
```
In fs/namei.c (ffffffff8132cc95)
Location: include/linux/pagemap.h:109
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffffffff8136a223)
Location: include/linux/pagemap.h:109
Inline: True
Inline callers:
  - fs/buffer.c:grow_dev_page
```
```
In fs/mpage.c (ffffffff8137209c)
Location: include/linux/pagemap.h:109
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff813bcdec)
Location: include/linux/pagemap.h:109
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff8140b7e5)
Location: include/linux/pagemap.h:109
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff812620e9)
Location: include/linux/pagemap.h:114
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_pages
```
```
In fs/namei.c (ffffffff81332855)
Location: include/linux/pagemap.h:114
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffffffff81370e43)
Location: include/linux/pagemap.h:114
Inline: True
Inline callers:
  - fs/buffer.c:grow_dev_page
```
```
In fs/mpage.c (ffffffff813781a8)
Location: include/linux/pagemap.h:114
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff813c3f34)
Location: include/linux/pagemap.h:114
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff81411995)
Location: include/linux/pagemap.h:114
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff8129e6d7)
Location: include/linux/pagemap.h:114
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_pages
```
```
In fs/namei.c (ffffffff8137ffe5)
Location: include/linux/pagemap.h:114
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffffffff813bfda7)
Location: include/linux/pagemap.h:114
Inline: True
Inline callers:
  - fs/buffer.c:grow_dev_page
```
```
In fs/mpage.c (ffffffff813c4957)
Location: include/linux/pagemap.h:114
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff814133c3)
Location: include/linux/pagemap.h:114
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/inode.c (ffffffff81464845)
Location: include/linux/pagemap.h:114
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff812f2df3)
Location: include/linux/pagemap.h:278
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_pages
```
```
In fs/namei.c (ffffffff81400092)
Location: include/linux/pagemap.h:278
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffffffff814456b7)
Location: include/linux/pagemap.h:278
Inline: True
Inline callers:
  - fs/buffer.c:grow_dev_page
```
```
In fs/mpage.c (ffffffff8144b2ca)
Location: include/linux/pagemap.h:278
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8148bfaa)
Location: include/linux/pagemap.h:278
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/inode.c (ffffffff814e3e5d)
Location: include/linux/pagemap.h:278
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff8135d1a4)
Location: include/linux/pagemap.h:278
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_pages
```
```
In fs/namei.c (ffffffff8148a0e2)
Location: include/linux/pagemap.h:278
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffffffff814d4727)
Location: include/linux/pagemap.h:278
Inline: True
Inline callers:
  - fs/buffer.c:grow_dev_page
```
```
In fs/mpage.c (ffffffff814d9a0a)
Location: include/linux/pagemap.h:278
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8151e773)
Location: include/linux/pagemap.h:278
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/inode.c (ffffffff8157d38d)
Location: include/linux/pagemap.h:278
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff8138f1f7)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_pages
```
```
In fs/namei.c (ffffffff814befbf)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffffffff8150c5b2)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
```
```
In fs/mpage.c (ffffffff8150d971)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff815568e3)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/inode.c (ffffffff815b473d)
Location: include/linux/pagemap.h:282
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff813b88a7)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_pages
```
```
In fs/namei.c (ffffffff814f165f)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffffffff81541515)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/buffer.c:__bread_gfp
```
```
In fs/mpage.c (ffffffff81542658)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8158cda5)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/balloc.c (ffffffff815c8874)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff815ce1d9)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff815df044)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815e1e4a)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff815e57f9)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff815ec0a9)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff816074ea)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff8161755a)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff81639f13)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/ext4/xattr.c (ffffffff81641fd6)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/jbd2/recovery.c (ffffffff8165264d)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff8165ab21)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_load_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_get_buf
```
```
In fs/fat/dir.c (ffffffff8166d827)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8166f18a)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9bfc0)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
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
In mm/filemap.c (ffff8000102b1f44)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In fs/namei.c (ffff80001039239c)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffff8000103da244)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
```
In fs/mpage.c (ffff8000103e6a4c)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffff80001042bfb0)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffff800010481660)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In mm/filemap.c (c04decdc)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In fs/namei.c (c05799a4)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (c05b37b4)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
```
```
In fs/mpage.c (c05be2f8)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (c05f38ac)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (c0642808)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In mm/filemap.c (c000000000367da8)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In fs/namei.c (c00000000048adb0)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (c0000000004df268)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
```
In fs/mpage.c (c0000000004ece78)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (c00000000053b248)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (c0000000005a5d20)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In mm/filemap.c (ffffffe0001d780c)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In fs/namei.c (ffffffe0002615ec)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffffffe000293042)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
```
In fs/mpage.c (ffffffe00029bcb2)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffe0002c821c)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffe00030a2c2)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff8121cff1)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In fs/namei.c (ffffffff812e1615)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffffffff81319e9c)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
```
In fs/mpage.c (ffffffff81323a7d)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8135c1e9)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff813a54a3)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff812101c7)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In fs/namei.c (ffffffff812d2255)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffffffff8130aa3c)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
```
In fs/mpage.c (ffffffff8131461d)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8134ce89)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff81395f33)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff8121ad91)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In fs/namei.c (ffffffff812df425)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffffffff8131796c)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
```
In fs/mpage.c (ffffffff8132154d)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff81359cb9)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff813a2d03)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In mm/filemap.c (ffffffff81229ed0)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In fs/namei.c (ffffffff812f0815)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/buffer.c (ffffffff81329567)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
```
In fs/mpage.c (ffffffff813332a1)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8136d3c9)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff813b73e3)
Location: include/linux/pagemap.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
</details>
</li>
</ul>

## Differences

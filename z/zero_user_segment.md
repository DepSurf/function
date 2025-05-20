# Function: <code>zero_user_segment</code>

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
In mm/truncate.c (ffffffff8119f233)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811a9d78)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff81246dbb)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffff8124dc51)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/page-io.c (ffffffff812a0041)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/inline.c (ffffffff812e0532)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/readpage.c (ffffffff812e2ee0)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff813047c5)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff8131659a)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_write_end
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
In mm/truncate.c (ffffffff811b4e8b)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811c244c)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff8126d494)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffff812763b5)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/page-io.c (ffffffff812ce9d2)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/inline.c (ffffffff81310647)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/readpage.c (ffffffff81312db6)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff813388e6)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff8134db31)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_short_read
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
In mm/truncate.c (ffffffff811c54ad)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811d2509)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff812806e4)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffff8128a0f5)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/page-io.c (ffffffff812e47cd)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/inline.c (ffffffff81326477)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/readpage.c (ffffffff81328d66)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e686)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff8136343c)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_short_read
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
In mm/truncate.c (ffffffff811cd956)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811daec0)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff8128e03f)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffff81296c5f)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff812fa3fc)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (ffffffff8131e49c)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8131e821)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff813631e7)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff81377d8c)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_short_read
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
In mm/truncate.c (ffffffff811e2c46)
Location: include/linux/highmem.h:212
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811f0c54)
Location: include/linux/highmem.h:212
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff812b0c4f)
Location: include/linux/highmem.h:212
Inline: True
Inline callers:
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffff812b9eca)
Location: include/linux/highmem.h:212
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff8131ea2c)
Location: include/linux/highmem.h:212
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (ffffffff81342abc)
Location: include/linux/highmem.h:212
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813431ac)
Location: include/linux/highmem.h:212
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff81387eab)
Location: include/linux/highmem.h:212
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff8139cb59)
Location: include/linux/highmem.h:212
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_short_read
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
In mm/truncate.c (ffffffff812041fc)
Location: include/linux/highmem.h:212
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81212677)
Location: include/linux/highmem.h:212
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff812d8a7c)
Location: include/linux/highmem.h:212
Inline: True
Inline callers:
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffff812e2c7c)
Location: include/linux/highmem.h:212
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff8134ca81)
Location: include/linux/highmem.h:212
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (ffffffff81370a0c)
Location: include/linux/highmem.h:212
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81370f0f)
Location: include/linux/highmem.h:212
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff813b6a2d)
Location: include/linux/highmem.h:212
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff813cbf64)
Location: include/linux/highmem.h:212
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_short_read
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
In mm/truncate.c (ffffffff81216bbc)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81224136)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff812edf4c)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffff812f78de)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff81364bc1)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (ffffffff81388ea1)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813893b1)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff813cff7d)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff813e5024)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_short_read
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
In mm/truncate.c (ffffffff81226572)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81234746)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff8130f70c)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffff81317f29)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff8138e421)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (ffffffff813b2fa5)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813b3584)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff813fab6c)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff81410a9d)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_short_read
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
In mm/truncate.c (ffffffff812343de)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8124297f)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff8132268c)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffff8132ad9f)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff813a6e81)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (ffffffff813cc027)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813cc77a)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff81414a3c)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff8142a6ad)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/truncate.c (ffffffff812619ab)
Location: include/linux/highmem.h:305
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff812700ea)
Location: include/linux/highmem.h:305
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff8135ca63)
Location: include/linux/highmem.h:305
Inline: True
Inline callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffff8136480b)
Location: include/linux/highmem.h:305
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff813aca7f)
Location: include/linux/highmem.h:305
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
```
```
In fs/ext4/inline.c (ffffffff813f2f67)
Location: include/linux/highmem.h:305
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (ffffffff81418150)
Location: include/linux/highmem.h:305
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81418ae3)
Location: include/linux/highmem.h:305
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff81462cc2)
Location: include/linux/highmem.h:305
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff8147a7f5)
Location: include/linux/highmem.h:305
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/truncate.c (ffffffff8126be2e)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8127b4d7)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff8136ae68)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffff81371822)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff813bd52c)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
```
```
In fs/ext4/inline.c (ffffffff814056bb)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (ffffffff8142bb84)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8142c67a)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e7b3)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff81495505)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/truncate.c (ffffffff81270c8f)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8128068b)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff81370578)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffff81378af5)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff813c3aaa)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
```
```
In fs/ext4/inline.c (ffffffff8140b9f9)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (ffffffff8143284d)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81433349)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff81484345)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff8149a565)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/truncate.c (ffffffff812adc8d)
Location: include/linux/highmem.h:222
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff812bea3e)
Location: include/linux/highmem.h:222
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff813bf0f8)
Location: include/linux/highmem.h:222
Inline: True
Inline callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffff813c5498)
Location: include/linux/highmem.h:222
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff81413fe7)
Location: include/linux/highmem.h:222
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
```
```
In fs/ext4/inline.c (ffffffff8145e675)
Location: include/linux/highmem.h:222
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (ffffffff8148610d)
Location: include/linux/highmem.h:222
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81486bf5)
Location: include/linux/highmem.h:222
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff814db9c5)
Location: include/linux/highmem.h:222
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff814f1fd2)
Location: include/linux/highmem.h:222
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In fs/buffer.c (ffffffff81447907)
Location: include/linux/highmem.h:293
Inline: True
Inline callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffff8144c441)
Location: include/linux/highmem.h:293
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff814dcdd3)
Location: include/linux/highmem.h:293
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (ffffffff81509714)
Location: include/linux/highmem.h:293
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8150a534)
Location: include/linux/highmem.h:293
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff81569597)
Location: include/linux/highmem.h:293
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff8157f93e)
Location: include/linux/highmem.h:293
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In fs/buffer.c (ffffffff814d6457)
Location: include/linux/highmem.h:293
Inline: True
Inline callers:
  - fs/buffer.c:block_write_full_page
```
```
In fs/mpage.c (ffffffff814da86e)
Location: include/linux/highmem.h:293
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/inline.c (ffffffff81575de3)
Location: include/linux/highmem.h:293
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (ffffffff815a433d)
Location: include/linux/highmem.h:293
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff815a503a)
Location: include/linux/highmem.h:293
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff8160d177)
Location: include/linux/highmem.h:293
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff8162561e)
Location: include/linux/highmem.h:293
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In fs/ecryptfs/mmap.c (ffffffff81645037)
Location: include/linux/highmem.h:289
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff8165d9ab)
Location: include/linux/highmem.h:289
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In fs/ecryptfs/mmap.c (ffffffff8167e567)
Location: include/linux/highmem.h:289
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff816976e5)
Location: include/linux/highmem.h:289
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/truncate.c (ffff8000102c4a00)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffff8000102d4c74)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffff8000103db608)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffff8000103e6410)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffff80001047a664)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (ffff8000104a40a0)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffff8000104a4c04)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffff8000104f61ec)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffff80001050e6bc)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/truncate.c (c04ef2e8)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (c04fced8)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (c05b4b04)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (c05bdf1c)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (c063c0b4)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (c0666088)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (c06668a0)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (c06b3cc0)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (c06c9e38)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/truncate.c (c00000000037f1a0)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (c000000000394800)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (c0000000004e0910)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (c0000000004ec668)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (c00000000059d578)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (c0000000005d12a0)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (c0000000005d1da4)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (c0000000006370ac)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (c000000000655830)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/truncate.c (ffffffe0001e52aa)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffe0001f0a06)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffe000293d88)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffe00029b730)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffe000304f28)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (ffffffe000325574)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffe000325d08)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffe000365000)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffe00037927a)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/truncate.c (ffffffff8122ca2e)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8123afcf)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff8131ac6c)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffff8132337f)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff8139f461)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (ffffffff813c4607)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813c4d5a)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff8140d01c)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff81422c8d)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/truncate.c (ffffffff8121fb0e)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8122dfc9)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff8130b80c)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffff81313f1f)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff8138fef1)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (ffffffff813b5087)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813b57da)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff813fda9c)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff8141370d)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/truncate.c (ffffffff8122a7ce)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81238d6f)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff8131873c)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffff81320e4f)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff8139ccc1)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (ffffffff813c1a97)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813c21ea)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a39c)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff8141ee2d)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/truncate.c (ffffffff81239ba6)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff812483f4)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff8132a344)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/buffer.c:nobh_writepage
```
```
In fs/mpage.c (ffffffff81332b6f)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff813b11d1)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/page-io.c (ffffffff813d6bf7)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813d7374)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff8142008c)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff81435b8d)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
</details>
</li>
</ul>

## Differences

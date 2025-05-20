# Function: <code>SetPageError</code>

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
In mm/filemap.c (ffffffff8118d8e5)
Location: include/linux/page-flags.h:210
Inline: True
```
```
In mm/page_io.c (ffffffff811d1eb2)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_write
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/migrate.c (ffffffff811f1c24)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/memory-failure.c (ffffffff81202287)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff81243ffc)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:block_read_full_page
```
```
In fs/ext4/page-io.c (ffffffff8129f6f0)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/move_extent.c (ffffffff812d7273)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff812e2cd4)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - fs/ext4/readpage.c:completion_pages
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/fuse/file.c (ffffffff813167df)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffffffff811a0525)
Location: include/linux/page-flags.h:256
Inline: True
```
```
In mm/page_io.c (ffffffff811efade)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (ffffffff812105e8)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/memory-failure.c (ffffffff812267b7)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8126d94a)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/crypto.c (ffffffff81288bf3)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - fs/crypto/crypto.c:completion_pages
```
```
In fs/ext4/page-io.c (ffffffff812cdfdf)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/move_extent.c (ffffffff81306fa4)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff8131325e)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/squashfs/file.c (ffffffff81322722)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In fs/squashfs/symlink.c (ffffffff81324acb)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813251b3)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff8134b4b1)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffffffff811af6fd)
Location: include/linux/page-flags.h:266
Inline: True
```
```
In mm/page_io.c (ffffffff8120047e)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (ffffffff81222723)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/memory-failure.c (ffffffff81238d87)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff81280b78)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/crypto.c (ffffffff8129d833)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/crypto/crypto.c:completion_pages
```
```
In fs/ext4/page-io.c (ffffffff812e3dcf)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/move_extent.c (ffffffff8131cf57)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff81329202)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/squashfs/file.c (ffffffff813385b2)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In fs/squashfs/symlink.c (ffffffff8133a930)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8133b007)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff81360dc1)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffffffff811b65af)
Location: include/linux/page-flags.h:266
Inline: True
```
```
In mm/page_io.c (ffffffff8120b0d7)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (ffffffff8122e1c3)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/memory-failure.c (ffffffff81245199)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8128e44f)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (ffffffff812ae13d)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/crypto/bio.c:completion_pages
```
```
In fs/ext4/move_extent.c (ffffffff81315a2f)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff8131db1a)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff8131ec16)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/squashfs/file.c (ffffffff8134d537)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In fs/squashfs/symlink.c (ffffffff8134f598)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8134faaa)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff81375437)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffffffff811ca92f)
Location: include/linux/page-flags.h:267
Inline: True
```
```
In mm/page_io.c (ffffffff81224607)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (ffffffff81249299)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/memory-failure.c (ffffffff812650b9)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff812b1048)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (ffffffff812d1b3d)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - fs/crypto/bio.c:completion_pages
```
```
In fs/ext4/move_extent.c (ffffffff8133a255)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff8134212a)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff8134327f)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/squashfs/file.c (ffffffff81371be7)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In fs/squashfs/symlink.c (ffffffff81373c4c)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff81374194)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff8139a590)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffffffff811eb97f)
Location: include/linux/page-flags.h:274
Inline: True
```
```
In mm/page_io.c (ffffffff81246b18)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (ffffffff8126cd19)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/memory-failure.c (ffffffff812893d9)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff812d8ead)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (ffffffff812fc61a)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/ext4/move_extent.c (ffffffff813687bd)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff8136ffab)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff8137104e)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/squashfs/file.c (ffffffff813a01a4)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813a26db)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813a2bd1)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff813c979b)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffffffff811fc4ff)
Location: include/linux/page-flags.h:283
Inline: True
```
```
In mm/page_io.c (ffffffff8125af51)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (ffffffff8128151a)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/memory-failure.c (ffffffff8129e329)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff812ee37d)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (ffffffff81311e7a)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/iomap.c (ffffffff81325f49)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - fs/iomap.c:iomap_readpage
  - fs/iomap.c:iomap_read_end_io
```
```
In fs/ext4/move_extent.c (ffffffff81380c42)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff8138843b)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813894f0)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/squashfs/file.c (ffffffff813b8f24)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813bb4bb)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813bb9c6)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff813e244b)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffffffff81213c1f)
Location: include/linux/page-flags.h:314
Inline: True
```
```
In mm/page_io.c (ffffffff81275f5c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (ffffffff8129d7ab)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/memory-failure.c (ffffffff812b94f9)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8130fb78)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (ffffffff81339467)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8134b135)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/move_extent.c (ffffffff813a96b4)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b2511)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813b36c2)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/squashfs/file.c (ffffffff813e3d3c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813e5d72)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813e6233)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff8140e103)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffffffff812213f7)
Location: include/linux/page-flags.h:314
Inline: True
```
```
In mm/page_io.c (ffffffff81285a2c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (ffffffff812ad0ba)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/memory-failure.c (ffffffff812cb3f1)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff81322afe)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (ffffffff8134f2d9)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff81351838)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813633d5)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/move_extent.c (ffffffff813c25d4)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813cb419)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813cc911)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff813fdd70)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813ffdc2)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8140029a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff8142726d)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffffffff8124f45a)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
  - mm/filemap.c:page_endio
```
```
In mm/page_io.c (ffffffff812b7df4)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (ffffffff812e2bfa)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/memory-failure.c (ffffffff81301721)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8135c1e0)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (ffffffff81395808)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff813983cc)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813ab1d4)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/move_extent.c (ffffffff8140ecd0)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81417556)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81418acf)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff8144b7ce)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff8144d780)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8144dd01)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff81477bba)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffffffff81259dfa)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
  - mm/filemap.c:page_endio
```
```
In mm/page_io.c (ffffffff812c34a4)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (ffffffff812ee02a)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/memory-failure.c (ffffffff8130d7e1)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff813698ba)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (ffffffff813a6b28)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff813a9c4c)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813bc6eb)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/buffered-io.c:iomap_read_page_end_io
```
```
In fs/ext4/move_extent.c (ffffffff814221a0)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff8142b070)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff8142c666)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff81467eae)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81bed5b9)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8146a2be)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff8149246a)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffffffff8125e03a)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
  - mm/filemap.c:page_endio
```
```
In mm/page_io.c (ffffffff812ca225)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (ffffffff812f3b1a)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/memory-failure.c (ffffffff81313b31)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff813706ca)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (ffffffff813adbb8)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff813b1182)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813c2d45)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/move_extent.c (ffffffff81428864)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81431be0)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81433335)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff8146d4b1)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81bdf69b)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8146f947)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff81497468)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffffffff8129a75a)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
  - mm/filemap.c:page_endio
```
```
In mm/page_io.c (ffffffff8130f245)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (ffffffff8133e4ba)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/memory-failure.c (ffffffff8135ee21)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff813bf26b)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (ffffffff813fd538)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff81400de4)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff814123db)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/move_extent.c (ffffffff8147c5cd)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81485430)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81486ebd)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff814c3d49)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81ccf1ab)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff814c63b1)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff814eede8)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffffffff812f1edf)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
  - mm/filemap.c:page_endio
```
```
In mm/page_io.c (ffffffff81379015)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/memory-failure.c (ffffffff813d964f)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff81447609)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (ffffffff81470d49)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff81474ebd)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/ext4/move_extent.c (ffffffff814fedf9)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81508922)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff8150a51b)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff8154eab0)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81e82235)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff81551411)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff8157ea96)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/page_io.c (ffffffff813f69b5)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/memory-failure.c (ffffffff8145f93f)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff814d6237)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/ext4/move_extent.c (ffffffff81599653)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff815a3438)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff815a50ab)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff815ef52c)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff815f1b36)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff815f240a)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff8162472a)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/page_io.c (ffffffff81429845)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:__end_swap_bio_read
  - mm/page_io.c:__end_swap_bio_write
```
```
In mm/memory-failure.c (ffffffff81495b53)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/squashfs/file.c (ffffffff8162750c)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81629c26)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff8162a4f5)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff8165cb0a)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/memory-failure.c (ffffffff814c5323)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/squashfs/file.c (ffffffff8166066c)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81662e76)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff81663822)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff8169686a)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffff8000102b0918)
Location: include/linux/page-flags.h:314
Inline: True
```
```
In mm/page_io.c (ffff80001032014c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (ffff80001034f36c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/memory-failure.c (ffff80001036e8c8)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffff8000103dbafc)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (ffff800010410e84)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffff800010413968)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffff80001042ab50)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/move_extent.c (ffff80001049a020)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffff8000104a325c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffff8000104a4e50)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffff8000104dbe18)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffff8000104ddd74)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffff8000104de2c8)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffff80001050bc54)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (c04db638)
Location: include/linux/page-flags.h:314
Inline: True
```
```
In mm/page_io.c (c05389b4)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (c05512f4)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (c05b4e98)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (c05dd29c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (c05dfc14)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (c05f2b38)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/move_extent.c (c065b7e0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c06653fc)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (c0666998)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (c069d648)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (c069f9dc)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (c069feec)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (c06c6f30)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (c0000000003632a8)
Location: include/linux/page-flags.h:314
Inline: True
```
```
In mm/page_io.c (c0000000003f5008)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (c00000000043176c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/memory-failure.c (c00000000045fdf0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (c0000000004e0ec0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (c00000000051e620)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (c00000000052194c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (c00000000053a894)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/move_extent.c (c0000000005c431c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c0000000005d03c0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (c0000000005d1e50)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (c0000000006170c8)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (c00000000061998c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (c00000000061a030)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (c0000000006517e0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffffffe0001d4bf6)
Location: include/linux/page-flags.h:314
Inline: True
```
```
In mm/page_io.c (ffffffe000221844)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (ffffffe00023e3d4)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffe000294184)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (ffffffe0002b9074)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffe0002bb340)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffe0002c7d58)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/move_extent.c (ffffffe00031d778)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffe000324b6a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffe000325db4)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffe000350aa8)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffe0003527e4)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffe000352c9a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffe00037648a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffffffff81219a47)
Location: include/linux/page-flags.h:314
Inline: True
```
```
In mm/page_io.c (ffffffff8127e07c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (ffffffff812a569a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/memory-failure.c (ffffffff812c39d1)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8131b0de)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (ffffffff813478b9)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff81349e18)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8135b9b5)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/move_extent.c (ffffffff813babb4)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c39f9)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813c4ef1)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff813f6350)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813f83a2)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813f887a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff8141f84d)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffffffff8120cc57)
Location: include/linux/page-flags.h:314
Inline: True
```
```
In mm/page_io.c (ffffffff8126feac)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (ffffffff8129716a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/memory-failure.c (ffffffff812b4a11)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8130bc7e)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (ffffffff81338599)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff8133aaf8)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8134c655)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/move_extent.c (ffffffff813ab644)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b4489)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813b5971)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff813e6dd0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813e8e22)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813e92fa)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff814102cd)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffffffff812177e7)
Location: include/linux/page-flags.h:314
Inline: True
```
```
In mm/page_io.c (ffffffff8127be1c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (ffffffff812a34aa)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/memory-failure.c (ffffffff812c17e1)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff81318bae)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (ffffffff81345389)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff813478e8)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff81359485)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/move_extent.c (ffffffff813b8414)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c0e89)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813c2381)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff813f36d0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813f5722)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813f5bfa)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff8141b9ed)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
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
In mm/filemap.c (ffffffff81226897)
Location: include/linux/page-flags.h:314
Inline: True
```
```
In mm/page_io.c (ffffffff8128b9fc)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/migrate.c (ffffffff812b3cba)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/memory-failure.c (ffffffff812d22a1)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8132a7ce)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/bio.c (ffffffff81358669)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff8135abe8)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8136cb85)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/move_extent.c (ffffffff813cd124)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813d5fb9)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813d74fd)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff814092e0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff8140b370)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8140b84a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/file.c (ffffffff81432f5d)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
```
</details>
</li>
</ul>

## Differences

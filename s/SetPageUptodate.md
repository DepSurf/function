# Function: <code>SetPageUptodate</code>

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
In mm/filemap.c (ffffffff8118d912)
Location: include/linux/page-flags.h:365
Inline: True
```
```
In mm/shmem.c (ffffffff811a8671)
Location: include/linux/page-flags.h:365
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_symlink
```
```
In mm/page_io.c (ffffffff811d1f1d)
Location: include/linux/page-flags.h:365
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:swap_readpage
```
```
In mm/zswap.c (ffffffff811d88bb)
Location: include/linux/page-flags.h:365
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff811f1c3e)
Location: include/linux/page-flags.h:365
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/libfs.c (ffffffff81234b1f)
Location: include/linux/page-flags.h:365
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff81243267)
Location: include/linux/page-flags.h:365
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffffffff8124e1e2)
Location: include/linux/page-flags.h:365
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff8125cc7d)
Location: include/linux/page-flags.h:365
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_setup
```
```
In fs/ext4/inode.c (ffffffff8129e3de)
Location: include/linux/page-flags.h:365
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff812cf0ee)
Location: include/linux/page-flags.h:365
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff812d6e5c)
Location: include/linux/page-flags.h:365
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff812e0569)
Location: include/linux/page-flags.h:365
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In fs/ext4/readpage.c (ffffffff812e2d02)
Location: include/linux/page-flags.h:365
Inline: True
Inline callers:
  - fs/ext4/readpage.c:completion_pages
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff81303deb)
Location: include/linux/page-flags.h:365
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff81304b47)
Location: include/linux/page-flags.h:365
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8130eb8d)
Location: include/linux/page-flags.h:365
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_notify
```
```
In fs/fuse/file.c (ffffffff813167a2)
Location: include/linux/page-flags.h:365
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
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
In mm/filemap.c (ffffffff811a0552)
Location: include/linux/page-flags.h:441
Inline: True
```
```
In mm/shmem.c (ffffffff811c1cbb)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff811f01db)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff811f714c)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff8121062e)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff8121aead)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/libfs.c (ffffffff8125cffe)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8126c6d3)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8127693d)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff81284dba)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/crypto/crypto.c (ffffffff81288c20)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - fs/crypto/crypto.c:completion_pages
```
```
In fs/ext4/inode.c (ffffffff812cc8d7)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff812feaa4)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff81306b5b)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff81311116)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/readpage.c (ffffffff813133ad)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/squashfs/file.c (ffffffff813227fa)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/symlink.c (ffffffff81324a07)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff81324efa)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff81338881)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff81338c86)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81344259)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8134db21)
Location: include/linux/page-flags.h:441
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/filemap.c (ffffffff811af723)
Location: include/linux/page-flags.h:457
Inline: True
```
```
In mm/shmem.c (ffffffff811d1d86)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff81200b9f)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff81207af9)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff8122276e)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff8122cd02)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/libfs.c (ffffffff81270587)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8127f733)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8128a636)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff81298fc9)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/crypto/crypto.c (ffffffff8129d872)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - fs/crypto/crypto.c:completion_pages
```
```
In fs/ext4/inode.c (ffffffff812e27b4)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff81314b15)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff8131caff)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff81326ff6)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/readpage.c (ffffffff8132934b)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/squashfs/file.c (ffffffff81338687)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/symlink.c (ffffffff8133a875)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8133ad54)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e621)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff8134ea1d)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81359a65)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff813633d0)
Location: include/linux/page-flags.h:457
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/filemap.c (ffffffff811b65d9)
Location: include/linux/page-flags.h:460
Inline: True
```
```
In mm/shmem.c (ffffffff811da75d)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff8120b7f3)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff81212a92)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff8122e209)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff81239586)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/libfs.c (ffffffff8127dca0)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8128d796)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff812975d6)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff812a66b3)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/crypto/bio.c (ffffffff812ae17d)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - fs/crypto/bio.c:completion_pages
```
```
In fs/ext4/inline.c (ffffffff812faf45)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81306877)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff8130c2aa)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff8131590b)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff8131ef54)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/squashfs/file.c (ffffffff8134d5d2)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/symlink.c (ffffffff8134f4f3)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8134f985)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff81363105)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff81363519)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8136df8f)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff81377d86)
Location: include/linux/page-flags.h:460
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/filemap.c (ffffffff811ca959)
Location: include/linux/page-flags.h:461
Inline: True
```
```
In mm/shmem.c (ffffffff811f04c0)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff81224d19)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff8122d4dd)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff812492dd)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff81257cf5)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/libfs.c (ffffffff812a0755)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff812b031a)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff812ba85b)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff812c9be6)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/crypto/bio.c (ffffffff812d1b7d)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/crypto/bio.c:completion_pages
```
```
In fs/ext4/inline.c (ffffffff8131f635)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8132b447)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff81330e00)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff8133a13a)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813435ee)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/squashfs/file.c (ffffffff81371c82)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/symlink.c (ffffffff81373ba7)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8137402d)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff81387d95)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff813881fe)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81392b6c)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8139cb53)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/filemap.c (ffffffff811eb994)
Location: include/linux/page-flags.h:468
Inline: True
```
```
In mm/shmem.c (ffffffff81211c3b)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff812472b9)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff81250519)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff8126cd5d)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff8127bc30)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/libfs.c (ffffffff812c6cad)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff812d7be6)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff812e3256)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff812f2eef)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/crypto/bio.c (ffffffff812fc65c)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/ext4/inline.c (ffffffff8134d68e)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8135999c)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff8135f36c)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813686ad)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff81371369)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/squashfs/file.c (ffffffff813a0267)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813a2639)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813a2c9f)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff813b6ad1)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff813b704b)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff813c2ebb)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff813cbeea)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/filemap.c (ffffffff811fc515)
Location: include/linux/page-flags.h:485
Inline: True
```
```
In mm/shmem.c (ffffffff81225cc8)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff8125b70d)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff812649e9)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff8128155f)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff8128fd81)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/libfs.c (ffffffff812dbe7d)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff812ed6f6)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff812f7ec8)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff81307c12)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/crypto/bio.c (ffffffff81311ebd)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/iomap.c (ffffffff813234e0)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/iomap.c:iomap_set_range_uptodate
```
```
In fs/ext4/inline.c (ffffffff81365825)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81371ccc)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff8137780d)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff81380b31)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff81389825)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/squashfs/file.c (ffffffff813b8fe9)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813bb419)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813bba6c)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff813d0021)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff813d059b)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff813dc5f7)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/dir.c (ffffffff813dde02)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_readpage
```
```
In fs/fuse/file.c (ffffffff813e4faa)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/filemap.c (ffffffff81213c46)
Location: include/linux/page-flags.h:518
Inline: True
```
```
In mm/shmem.c (ffffffff81235319)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff81276882)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff8127ff65)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff8129d7f1)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff812aaf44)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/libfs.c (ffffffff812fa520)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8130ed7a)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff81318507)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff8132c3e5)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/crypto/bio.c (ffffffff81339441)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8134b580)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/inline.c (ffffffff8138ec00)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8139b25c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff813a0a47)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813a969c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff813b39fb)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/squashfs/file.c (ffffffff813e3df8)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813e5cc3)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813e62fa)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff813fac12)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff813fb1b3)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8140747f)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (ffffffff81409df3)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_readpage
```
```
In fs/fuse/file.c (ffffffff81410a1a)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/filemap.c (ffffffff81221479)
Location: include/linux/page-flags.h:518
Inline: True
```
```
In mm/shmem.c (ffffffff81243559)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff81286372)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff8128f3ee)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff812ad10f)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff812bc8ca)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff8130c2a0)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff81321d9a)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8132b367)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff8133f235)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/crypto/bio.c (ffffffff8134f2b1)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8136383f)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/inline.c (ffffffff813a7660)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813b3d27)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff813b98b5)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813c25bc)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff813cc832)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff813fde49)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813ffd13)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff81400370)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff81414ae2)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff81415083)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81422298)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (ffffffff81423433)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_readpage
```
```
In fs/fuse/file.c (ffffffff8142a62a)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
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
In mm/filemap.c (ffffffff8124f4b5)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In mm/shmem.c (ffffffff812720a9)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff812b8666)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff812c209a)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff812e2c4f)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff812f1df6)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff81345782)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8135d02a)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8136521e)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff81377845)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/iomap/buffered-io.c (ffffffff813aac93)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
```
```
In fs/ext4/inline.c (ffffffff813f27cb)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813ff476)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff814053ec)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff8140eb8d)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff814189fc)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff8144b8a7)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff8144d6d1)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8144ddd1)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff81462c97)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff81463343)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81470ec5)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (ffffffff814729b4)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_readpage
```
```
In fs/fuse/file.c (ffffffff8147a7ed)
Location: include/linux/page-flags.h:534
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/filemap.c (ffffffff81259e5a)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In mm/shmem.c (ffffffff8127ae19)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff812c3dd3)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff812cdd56)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff812ee07f)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff812fe377)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff81351ec0)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff81369b2a)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8137223a)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff813851a2)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/iomap/buffered-io.c (ffffffff813bc4dc)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
```
```
In fs/ext4/inline.c (ffffffff81404f1b)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81411c13)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff8141868e)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff81422093)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff8142c606)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff81467f87)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81469d11)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8146a38b)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e793)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff8147eb93)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8148b79d)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (ffffffff8148d354)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_readpage
```
```
In fs/fuse/file.c (ffffffff814954fd)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/filemap.c (ffffffff8125e09a)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In mm/shmem.c (ffffffff8127ff98)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff812cabd5)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff812d507b)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff812f3b6f)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff81305031)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff81358be4)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8136fcca)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff81378344)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff8138bf52)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/iomap/buffered-io.c (ffffffff813c322d)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
```
```
In fs/ext4/inline.c (ffffffff8140c328)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81418033)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff8141eedf)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff81428757)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff814332df)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff8146d592)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff8146f40d)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8146fa17)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff81484325)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff8148471d)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8149077a)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (ffffffff81492a54)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_readpage
```
```
In fs/fuse/file.c (ffffffff8149a55d)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/filemap.c (ffffffff8129a7bd)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In mm/shmem.c (ffffffff812be29b)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff8130fbd4)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff8131a68e)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff8133e50f)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff8134edc1)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff813a72d1)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff813bf56a)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff813c4bd4)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff813d9505)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/iomap/buffered-io.c (ffffffff81412b97)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
```
```
In fs/ext4/inline.c (ffffffff8145f21c)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8146b249)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff814725eb)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff8147c5bf)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff81486fd8)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff814c3e26)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff814c5dfd)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff814c6481)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff814db9a5)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff814dbd9d)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff814e8207)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (ffffffff814ea434)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_readpage
```
```
In fs/fuse/file.c (ffffffff814f1fca)
Location: include/linux/page-flags.h:558
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/filemap.c (ffffffff812f1ea1)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In mm/shmem.c (ffffffff8131b2e8)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff8137a5ee)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff81385b5a)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/khugepaged.c (ffffffff813c599a)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff8142c829)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff81447136)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8144ba98)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff81463582)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inline.c (ffffffff814dc25d)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff814eaf4e)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff814f3867)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff814fed9f)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff8150a60c)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff8154eb51)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81550d66)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff81551589)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff815696c0)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff81569a36)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff815771ae)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff8157f910)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/shmem.c (ffffffff8138cd26)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/page_io.c (ffffffff813f8097)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff81403949)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/libfs.c (ffffffff814ba099)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff814d4512)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/aio.c (ffffffff814f2672)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inline.c (ffffffff8157520d)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81584afe)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff8158de43)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff815995f9)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff815a5438)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff815ef0b9)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff815f1ac1)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff815f255e)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8160d24e)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d665)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8161b88e)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/file.c (ffffffff816255f0)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffff8162eeea)
Location: include/linux/page-flags.h:753
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In mm/page_io.c (ffffffff8142b0ce)
Location: include/linux/page-flags.h:747
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:__end_swap_bio_read
```
```
In mm/zswap.c (ffffffff8143789a)
Location: include/linux/page-flags.h:747
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/libfs.c (ffffffff814eef8d)
Location: include/linux/page-flags.h:747
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/aio.c (ffffffff815292a8)
Location: include/linux/page-flags.h:747
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/mballoc.c (ffffffff815c465c)
Location: include/linux/page-flags.h:747
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/squashfs/block.c (ffffffff81623ff3)
Location: include/linux/page-flags.h:747
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - fs/squashfs/block.c:squashfs_bio_read_cached
```
```
In fs/squashfs/file.c (ffffffff81627099)
Location: include/linux/page-flags.h:747
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81629bb1)
Location: include/linux/page-flags.h:747
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff8162a64d)
Location: include/linux/page-flags.h:747
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8164510e)
Location: include/linux/page-flags.h:747
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff81645524)
Location: include/linux/page-flags.h:747
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff816539f5)
Location: include/linux/page-flags.h:747
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/file.c (ffffffff8165d94e)
Location: include/linux/page-flags.h:747
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffff8166714d)
Location: include/linux/page-flags.h:747
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In fs/aio.c (ffffffff8155e178)
Location: include/linux/page-flags.h:768
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/mballoc.c (ffffffff815fc8ff)
Location: include/linux/page-flags.h:768
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/squashfs/block.c (ffffffff8165d093)
Location: include/linux/page-flags.h:768
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - fs/squashfs/block.c:squashfs_bio_read_cached
```
```
In fs/squashfs/file.c (ffffffff8166024c)
Location: include/linux/page-flags.h:768
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81662e01)
Location: include/linux/page-flags.h:768
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff81663971)
Location: include/linux/page-flags.h:768
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e63b)
Location: include/linux/page-flags.h:768
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff8167ea1d)
Location: include/linux/page-flags.h:768
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8168d002)
Location: include/linux/page-flags.h:768
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/file.c (ffffffff8169768b)
Location: include/linux/page-flags.h:768
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffff816a149a)
Location: include/linux/page-flags.h:768
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In mm/filemap.c (ffff8000102b0950)
Location: include/linux/page-flags.h:518
Inline: True
```
```
In mm/shmem.c (ffff8000102d57fc)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffff800010320988)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffff80001032c714)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffff80001034f3e8)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffff80001035db00)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffff8000103c0a98)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffff8000103d998c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffff8000103e691c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffff8000103fb1f4)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/crypto/bio.c (ffff800010410eac)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/iomap/buffered-io.c (ffff80001042af60)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/inline.c (ffff80001047af00)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffff8000104888d4)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffff8000104903dc)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffff800010499ff0)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffff8000104a4f8c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffff8000104dbef4)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffff8000104ddcd0)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffff8000104de384)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffff8000104f62ac)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffff8000104f66a4)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffff800010504f64)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (ffff800010506aa8)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_readpage
```
```
In fs/fuse/file.c (ffff80001050e69c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
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
In mm/filemap.c (c04db6d0)
Location: include/linux/page-flags.h:518
Inline: True
```
```
In mm/shmem.c (c04fd9ac)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (c0539574)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (c05429e4)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (c0551360)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/libfs.c (c059dfb8)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (c05b3e10)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (c05be790)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (c05d0514)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/crypto/bio.c (c05dd280)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/iomap/buffered-io.c (c05f36b8)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/inline.c (c063c84c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (c064ab74)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (c0651228)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (c065b76c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (c0666944)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (c069d6d0)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (c069f8e4)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (c069ffb0)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (c06b3c24)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (c06b4058)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (c06c13a4)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (c06c29ac)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_readpage
```
```
In fs/fuse/file.c (c06c9da8)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/filemap.c (c0000000003633a0)
Location: include/linux/page-flags.h:518
Inline: True
```
```
In mm/shmem.c (c00000000039566c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (c0000000003f5c94)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (c0000000004041b0)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (c0000000004317f0)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (c000000000449114)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (c0000000004bf208)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (c0000000004dfb58)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (c0000000004ecd88)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (c00000000050812c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/crypto/bio.c (c00000000051e5e8)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/iomap/buffered-io.c (c00000000053a6ec)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/inline.c (c00000000059e060)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (c0000000005aeed8)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (c0000000005b75c4)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (c0000000005c42fc)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (c0000000005d21d4)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (c0000000006171e0)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (c0000000006198c0)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (c00000000061a240)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (c0000000006371a8)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (c00000000063761c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (c00000000064a264)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (c00000000064bc9c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_readpage
```
```
In fs/fuse/file.c (c000000000655708)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/filemap.c (ffffffe0001d4c82)
Location: include/linux/page-flags.h:518
Inline: True
```
```
In mm/shmem.c (ffffffe0001f1258)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffe00022211c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffe00022b292)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffe00023e42a)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/libfs.c (ffffffe00028107c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffe000293550)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffe00029bc34)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffe0002aaab0)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/crypto/bio.c (ffffffe0002b90ce)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/iomap/buffered-io.c (ffffffe0002c7c9a)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/inline.c (ffffffe000305574)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffe00030ffb6)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffe00031534e)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffe00031d724)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffe000325e14)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffe000350b38)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffe00035277a)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffe000352d3a)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffe0003650a6)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffe0003653f2)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffe000371a0e)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (ffffffe000372ab2)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_readpage
```
```
In fs/fuse/file.c (ffffffe00037920e)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/filemap.c (ffffffff81219ac9)
Location: include/linux/page-flags.h:518
Inline: True
```
```
In mm/shmem.c (ffffffff8123bba9)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff8127e9c2)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff812879ce)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff812a56ef)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff812b4eaa)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff81304880)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8131a37a)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff81323947)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff81337815)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/crypto/bio.c (ffffffff81347891)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8135be1f)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/inline.c (ffffffff8139fc40)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813ac307)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff813b1e95)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813bab9c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff813c4e12)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff813f6429)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813f82f3)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813f8950)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8140d0c2)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff8140d663)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8141a878)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (ffffffff8141ba13)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_readpage
```
```
In fs/fuse/file.c (ffffffff81422c0a)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
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
In mm/filemap.c (ffffffff8120ccd9)
Location: include/linux/page-flags.h:518
Inline: True
```
```
In mm/shmem.c (ffffffff8122eba9)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff812707f2)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff8127982e)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff812971bf)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff812a5eee)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff812f54a0)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8130af1a)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff813144e7)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff81328545)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/crypto/bio.c (ffffffff81338571)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8134cabf)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/inline.c (ffffffff813906d0)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8139cd97)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff813a2925)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813ab62c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff813b5892)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff813e6ea9)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813e8d73)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813e93d0)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff813fdb42)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff813fe0e3)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8140b2f8)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (ffffffff8140c493)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_readpage
```
```
In fs/fuse/file.c (ffffffff8141368a)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
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
In mm/filemap.c (ffffffff81217869)
Location: include/linux/page-flags.h:518
Inline: True
```
```
In mm/shmem.c (ffffffff81239949)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff8127c762)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff812857de)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff812a34ff)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff812b2cba)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff81302670)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff81317e4a)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff81321417)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff813352e5)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/crypto/bio.c (ffffffff81345361)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813598ef)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/inline.c (ffffffff8139d4a0)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813a9b67)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff813af6f5)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813b83fc)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff813c22a2)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff813f37a9)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813f5673)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813f5cd0)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a442)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff8140a9e3)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81416a18)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (ffffffff81417bb3)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_readpage
```
```
In fs/fuse/file.c (ffffffff8141edaa)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
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
In mm/filemap.c (ffffffff81226919)
Location: include/linux/page-flags.h:518
Inline: True
```
```
In mm/shmem.c (ffffffff81249039)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff8128c332)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff81294e13)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff812b3d0f)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff812c30f7)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff81313c90)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff81329a5a)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8133316b)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff813482d5)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/crypto/bio.c (ffffffff81358641)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8136cfdf)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/inline.c (ffffffff813b1a10)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813be467)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff813c410f)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813cd10c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff813d742f)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff814093cd)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff8140b2b7)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8140b9d3)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff81420146)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff814206bb)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8142d778)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (ffffffff8142e9a3)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_readpage
```
```
In fs/fuse/file.c (ffffffff81435b0a)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
```
</details>
</li>
</ul>

## Differences

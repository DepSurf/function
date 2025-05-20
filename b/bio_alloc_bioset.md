# Function: <code>bio_alloc_bioset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b1750)
Location: block/bio.c:423
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/buffer.c:submit_bh_wbc
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/crypto.c:ext4_encrypted_zeroout
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_copy_kern
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_zeroout
  - drivers/md/dm.c:__clone_and_map_simple_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff813b1750-ffffffff813b19a1: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f5130)
Location: block/bio.c:422
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/buffer.c:submit_bh_wbc
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
  - fs/crypto/crypto.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:next_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__clone_and_map_simple_bio
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff813f5130-ffffffff813f5364: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140eb10)
Location: block/bio.c:426
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
  - fs/crypto/crypto.c:fscrypt_zeroout_range
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:next_bio
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__clone_and_map_simple_bio
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff8140eb10-ffffffff8140ed85: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141c6d0)
Location: block/bio.c:436
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:next_bio
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__clone_and_map_simple_bio
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff8141c6d0-ffffffff8141c8a7: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81447290)
Location: block/bio.c:436
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:next_bio
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__clone_and_map_simple_bio
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff81447290-ffffffff81447467: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8147a3e0)
Location: block/bio.c:436
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:next_bio
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff8147a3e0-ffffffff8147a5cb: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814988a0)
Location: block/bio.c:438
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap.c:iomap_dio_bio_actor
  - fs/iomap.c:iomap_dio_zero
  - fs/iomap.c:iomap_readpage_actor
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_clone_fast
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blk_next_bio
  - block/bounce.c:blk_queue_bounce
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814988a0-ffffffff81498a8b: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c6880)
Location: block/bio.c:426
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_clone_fast
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blk_next_bio
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814c6880-ffffffff814c6a6f: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814df680)
Location: block/bio.c:429
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_clone_fast
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blk_next_bio
  - block/bounce.c:__blk_queue_bounce
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814df680-ffffffff814df875: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153f0a0)
Location: block/bio.c:433
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_alloc_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:io_submit_init_bio
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/squashfs/block.c:squashfs_bio_read
  - block/bio.c:bio_clone_fast
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_map_kern
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff8153f0a0-ffffffff8153f2e6: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155b890)
Location: block/bio.c:437
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_alloc_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:io_submit_init_bio
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/squashfs/block.c:squashfs_bio_read
  - block/bio.c:bio_clone_fast
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_map_kern
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff8155b890-ffffffff8155baee: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, short unsigned int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81563f20)
Location: block/bio.c:398
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/squashfs/block.c:squashfs_bio_read
  - block/bio.c:bio_clone_fast
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff81563f20-ffffffff81564178: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, short unsigned int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c8100)
Location: block/bio.c:431
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/squashfs/block.c:squashfs_bio_read
  - block/fops.c:__blkdev_direct_IO
  - block/bio.c:bio_clone_fast
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff815c8100-ffffffff815c8465: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(struct block_device *bdev, short unsigned int nr_vecs, unsigned int opf, gfp_t gfp_mask, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81672de0)
Location: block/bio.c:470
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO
  - block/bio.c:bio_split
  - block/bio.c:blk_next_bio
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff81672de0-ffffffff816732cf: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(struct block_device *bdev, short unsigned int nr_vecs, blk_opf_t opf, gfp_t gfp_mask, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172e900)
Location: block/bio.c:493
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO
  - block/bio.c:bio_split
  - block/bio.c:blk_next_bio
  - block/blk-map.c:blk_rq_map_bio_alloc
  - drivers/md/md.c:md_super_write
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff8172e900-ffffffff8172ee29: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(struct block_device *bdev, short unsigned int nr_vecs, blk_opf_t opf, gfp_t gfp_mask, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8176ab30)
Location: block/bio.c:492
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/direct-io.c:dio_send_cur_page
  - fs/direct-io.c:dio_send_cur_page
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/fops.c:__blkdev_direct_IO_async
  - block/bio.c:bio_split
  - block/bio.c:blk_next_bio
  - block/blk-map.c:blk_rq_map_bio_alloc
  - drivers/md/md.c:md_super_write
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff8176ab30-ffffffff8176b059: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(struct block_device *bdev, short unsigned int nr_vecs, blk_opf_t opf, gfp_t gfp_mask, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817acfc0)
Location: block/bio.c:492
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:swap_read_folio
  - mm/page_io.c:__swap_writepage
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/direct-io.c:dio_send_cur_page
  - fs/direct-io.c:dio_send_cur_page
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/fops.c:__blkdev_direct_IO_async
  - block/bio.c:bio_split
  - block/bio.c:blk_next_bio
  - block/blk-map.c:blk_rq_map_bio_alloc
  - drivers/md/md.c:md_super_write
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff817acfc0-ffffffff817ad4e9: bio_alloc_bioset (STB_GLOBAL)
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
struct bio *bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dc1a0)
Location: block/bio.c:429
Inline: False
Direct callers:
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_clone_fast
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blk_next_bio
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffff8000105dc1a0-ffff8000105dc39c: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c07895c4)
Location: block/bio.c:429
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_clone_fast
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blk_next_bio
  - block/bounce.c:__blk_queue_bounce
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/dm.c:alloc_tio
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
c07895c4-c078982c: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076d0b0)
Location: block/bio.c:429
Inline: False
Direct callers:
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_clone_fast
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blk_next_bio
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
c00000000076d0b0-c00000000076d3a0: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041f608)
Location: block/bio.c:429
Inline: False
Direct callers:
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_clone_fast
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blk_next_bio
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffe00041f608-ffffffe00041f7a6: bio_alloc_bioset (STB_GLOBAL)
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
struct bio *bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d7c60)
Location: block/bio.c:429
Inline: False
Direct callers:
  - kernel/power/swap.c:swap_read_pages
  - kernel/power/swap.c:swap_read_pages
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_clone_fast
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blk_next_bio
  - block/bounce.c:__blk_queue_bounce
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814d7c60-ffffffff814d7e55: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c8610)
Location: block/bio.c:429
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_clone_fast
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blk_next_bio
  - block/bounce.c:__blk_queue_bounce
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814c8610-ffffffff814c8805: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d3cf0)
Location: block/bio.c:429
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_clone_fast
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blk_next_bio
  - block/bounce.c:__blk_queue_bounce
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814d3cf0-ffffffff814d3ee5: bio_alloc_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bio *bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ec880)
Location: block/bio.c:429
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_clone_fast
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blk_next_bio
  - block/bounce.c:__blk_queue_bounce
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814ec880-ffffffff814eca75: bio_alloc_bioset (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int nr_iovecs</code> ➡️ <code>unsigned int nr_iovecs</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int nr_iovecs</code> ➡️ <code>short unsigned int nr_iovecs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct block_device *bdev</code>
</li>
<li>
<b>Param added. </b>
<code>short unsigned int nr_vecs</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int opf</code>
</li>
<li>
<b>Param removed. </b>
<code>short unsigned int nr_iovecs</code>
</li>
<li>
<b>Param reordered. </b>
<code>gfp_mask, nr_iovecs, bs</code> ➡️ <code>bdev, nr_vecs, opf, gfp_mask, bs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int opf</code> ➡️ <code>blk_opf_t opf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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

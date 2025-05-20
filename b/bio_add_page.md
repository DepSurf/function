# Function: <code>bio_add_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b0260)
Location: block/bio.c:806
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
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/crypto.c:ext4_encrypted_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:md_super_write
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff813b0260-ffffffff813b0300: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f3cb0)
Location: block/bio.c:809
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
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/crypto.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/blk-lib.c:blkdev_issue_zeroout
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:md_super_write
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff813f3cb0-ffffffff813f3d50: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140d530)
Location: block/bio.c:814
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
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/crypto.c:fscrypt_zeroout_range
  - fs/iomap.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff8140d530-ffffffff8140d5d0: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141b170)
Location: block/bio.c:830
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
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff8141b170-ffffffff8141b1e7: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81445da0)
Location: block/bio.c:833
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff81445da0-ffffffff81445e18: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81478d80)
Location: block/bio.c:893
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff81478d80-ffffffff81478dd7: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81496fe0)
Location: block/bio.c:819
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff81496fe0-ffffffff81497037: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c57b0)
Location: block/bio.c:822
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814c57b0-ffffffff814c583d: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814de690)
Location: block/bio.c:861
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814de690-ffffffff814de71d: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153dc30)
Location: block/bio.c:933
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/squashfs/block.c:squashfs_bio_read
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:do_region
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff8153dc30-ffffffff8153dcbd: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155a7b0)
Location: block/bio.c:933
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/squashfs/block.c:squashfs_bio_read
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:do_region
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff8155a7b0-ffffffff8155a83d: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81562f80)
Location: block/bio.c:922
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
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:do_region
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff81562f80-ffffffff8156300b: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c68e0)
Location: block/bio.c:1005
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
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:do_region
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff815c68e0-ffffffff815c696b: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8167395d)
Location: block/bio.c:1084
Inline: True
Inline callers:
  - block/bio.c:bio_add_folio
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff81671790-ffffffff81671826: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172f8ed)
Location: block/bio.c:1136
Inline: True
Inline callers:
  - block/bio.c:bio_add_folio
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:md_super_write
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff8172cff0-ffffffff8172d086: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817692f0)
Location: block/bio.c:1093
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/direct-io.c:dio_send_cur_page
  - fs/direct-io.c:dio_send_cur_page
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff817692f0-ffffffff817693ca: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ab3e0)
Location: block/bio.c:1094
Inline: True
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/direct-io.c:dio_send_cur_page
  - fs/direct-io.c:dio_send_cur_page
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff817ab3e0-ffffffff817ab4a8: bio_add_page (STB_GLOBAL)
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
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105da2f8)
Location: block/bio.c:861
Inline: False
Direct callers:
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffff8000105da2f8-ffff8000105da3c4: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c0788008)
Location: block/bio.c:861
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
c0788008-c07880bc: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076b120)
Location: block/bio.c:861
Inline: False
Direct callers:
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
c00000000076b120-c00000000076b1f4: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041e0ec)
Location: block/bio.c:861
Inline: False
Direct callers:
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffe00041e0ec-ffffffe00041e168: bio_add_page (STB_GLOBAL)
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
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d6c70)
Location: block/bio.c:861
Inline: False
Direct callers:
  - kernel/power/swap.c:swap_read_pages
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814d6c70-ffffffff814d6cfd: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c7630)
Location: block/bio.c:861
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814c7630-ffffffff814c76bd: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d2d00)
Location: block/bio.c:861
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814d2d00-ffffffff814d2d8d: bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eb880)
Location: block/bio.c:861
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814eb880-ffffffff814eb90d: bio_add_page (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
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

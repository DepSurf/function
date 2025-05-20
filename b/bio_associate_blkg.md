# Function: <code>bio_associate_blkg</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81498330)
Location: block/bio.c:2076
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
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
  - fs/iomap.c:iomap_read_page_sync
  - fs/iomap.c:iomap_readpage_actor
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/blk-core.c:generic_make_request_checks
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:md_flush_request
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff81498330-ffffffff8149838a: bio_associate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c61b0)
Location: block/bio.c:2110
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/blk-core.c:generic_make_request_checks
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814c61b0-ffffffff814c620a: bio_associate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814de5b0)
Location: block/bio.c:2152
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/blk-core.c:generic_make_request_checks
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814de5b0-ffffffff814de60a: bio_associate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153ea60)
Location: block/bio.c:1731
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_alloc
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_alloc_ioend
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:io_submit_init_bio
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-core.c:blkcg_bio_issue_check
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_zone_mgmt
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map_range
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff8153ea60-ffffffff8153eaed: bio_associate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81586480)
Location: block/blk-cgroup.c:1862
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_alloc
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_alloc_ioend
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:io_submit_init_bio
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_zone_mgmt
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map_range
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff81586480-ffffffff815864e4: bio_associate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8158ce90)
Location: block/blk-cgroup.c:1871
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_alloc
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_zone_mgmt
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff8158ce90-ffffffff8158cef4: bio_associate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815f26f0)
Location: block/blk-cgroup.c:1865
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_alloc
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/squashfs/block.c:squashfs_bio_read
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-io.c:do_region
```
**Symbols:**

```
ffffffff815f26f0-ffffffff815f2754: bio_associate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a3f00)
Location: block/blk-cgroup.c:1953
Inline: False
Direct callers:
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_reset
  - drivers/md/dm.c:alloc_tio
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff816a3f00-ffffffff816a3f68: bio_associate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81762c60)
Location: block/blk-cgroup.c:1959
Inline: False
Direct callers:
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_reset
  - drivers/md/dm.c:alloc_tio
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff81762c60-ffffffff81762cc8: bio_associate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817a1930)
Location: block/blk-cgroup.c:2050
Inline: False
Direct callers:
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_reset
  - drivers/md/dm.c:alloc_tio
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff817a1930-ffffffff817a1998: bio_associate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e5470)
Location: block/blk-cgroup.c:2063
Inline: True
Direct callers:
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_reset
  - drivers/md/dm.c:alloc_tio
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff817e5470-ffffffff817e54ef: bio_associate_blkg (STB_GLOBAL)
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
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105db9f8)
Location: block/bio.c:2152
Inline: False
Direct callers:
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/blk-core.c:generic_make_request_checks
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffff8000105db9f8-ffff8000105dba68: bio_associate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c078858c)
Location: block/bio.c:2152
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_alloc
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/blk-core.c:generic_make_request_checks
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
c078858c-c07885f0: bio_associate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076b980)
Location: block/bio.c:2152
Inline: False
Direct callers:
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_alloc
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/blk-core.c:generic_make_request_checks
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
c00000000076b980-c00000000076ba20: bio_associate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041e620)
Location: block/bio.c:2152
Inline: False
Direct callers:
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_alloc
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/blk-core.c:generic_make_request_checks
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffe00041e620-ffffffe00041e680: bio_associate_blkg (STB_GLOBAL)
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
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d6b90)
Location: block/bio.c:2152
Inline: False
Direct callers:
  - kernel/power/swap.c:swap_read_pages
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/blk-core.c:generic_make_request_checks
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814d6b90-ffffffff814d6bea: bio_associate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c7550)
Location: block/bio.c:2152
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/blk-core.c:generic_make_request_checks
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814c7550-ffffffff814c75aa: bio_associate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d2c20)
Location: block/bio.c:2152
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/blk-core.c:generic_make_request_checks
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814d2c20-ffffffff814d2c7a: bio_associate_blkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bio_associate_blkg(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eb7a0)
Location: block/bio.c:2152
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:get_swap_bio
  - fs/buffer.c:submit_bh_wbc
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/blk-core.c:generic_make_request_checks
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff814eb7a0-ffffffff814eb7fe: bio_associate_blkg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

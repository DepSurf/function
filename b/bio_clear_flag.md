# Function: <code>bio_clear_flag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b096b)
Location: include/linux/bio.h:308
Inline: True
Inline callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_endio
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f407b)
Location: include/linux/bio.h:257
Inline: True
Inline callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_endio
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
In block/bio.c (ffffffff8140da2b)
Location: include/linux/bio.h:254
Inline: True
Inline callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_endio
```
```
In block/blk-throttle.c (ffffffff8143cb69)
Location: include/linux/bio.h:254
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
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
In block/bio.c (ffffffff8141d9f5)
Location: include/linux/bio.h:270
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff81425799)
Location: include/linux/bio.h:270
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-throttle.c (ffffffff8144ba65)
Location: include/linux/bio.h:270
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
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
In kernel/power/swap.c (ffffffff810e55b5)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8122451f)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff812b0736)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff812b3e13)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812b8562)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812b99ff)
Location: include/linux/bio.h:266
Inline: True
```
```
In fs/crypto/bio.c (ffffffff812d1d61)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap.c (ffffffff812e1b55)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff81342b92)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813433ee)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/bio.c (ffffffff814488e5)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff81450926)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-flush.c (ffffffff8145446b)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff81459d2d)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff81483250)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/md/md.c (ffffffff817ace51)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/dm.c (ffffffff817c1459)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-linear.c (ffffffff817c52b0)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff817c5ceb)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff817c92e2)
Location: include/linux/bio.h:266
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In kernel/power/swap.c (ffffffff810edad5)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff81246a1f)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff812d8527)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff812dc61f)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812e1743)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812e256e)
Location: include/linux/bio.h:275
Inline: True
```
```
In fs/crypto/bio.c (ffffffff812fc897)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap.c (ffffffff8130e285)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813709b5)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813711c6)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/bio.c (ffffffff8147ba53)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff81483c13)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-flush.c (ffffffff814878bb)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff8148d3dd)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff814b7ea1)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/md/md.c (ffffffff817f2f71)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:md_flush_request
```
```
In drivers/md/dm.c (ffffffff81809ad6)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-linear.c (ffffffff8180df00)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff8180eaae)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff81812097)
Location: include/linux/bio.h:275
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In kernel/power/swap.c (ffffffff810f9146)
Location: include/linux/bio.h:229
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8125ae3f)
Location: include/linux/bio.h:229
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff812ed9c1)
Location: include/linux/bio.h:229
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff812f1d8d)
Location: include/linux/bio.h:229
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812f63b0)
Location: include/linux/bio.h:229
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812f71be)
Location: include/linux/bio.h:229
Inline: True
```
```
In fs/crypto/bio.c (ffffffff813120fe)
Location: include/linux/bio.h:229
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap.c (ffffffff81323aaf)
Location: include/linux/bio.h:229
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_actor
  - fs/iomap.c:iomap_dio_zero
  - fs/iomap.c:iomap_read_page_sync
  - fs/iomap.c:iomap_readpage_actor
```
```
In fs/ext4/page-io.c (ffffffff81388e1a)
Location: include/linux/bio.h:229
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81389668)
Location: include/linux/bio.h:229
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/bio.c (ffffffff8149856f)
Location: include/linux/bio.h:229
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff8149f1d3)
Location: include/linux/bio.h:229
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-flush.c (ffffffff814a1a1c)
Location: include/linux/bio.h:229
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff814a6c5d)
Location: include/linux/bio.h:229
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff814cb96f)
Location: include/linux/bio.h:229
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (ffffffff8181ef45)
Location: include/linux/bio.h:229
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:md_flush_request
```
```
In drivers/md/dm.c (ffffffff818346ef)
Location: include/linux/bio.h:229
Inline: True
```
```
In drivers/md/dm-linear.c (ffffffff8183a0f9)
Location: include/linux/bio.h:229
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff8183aa6e)
Location: include/linux/bio.h:229
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff8183e006)
Location: include/linux/bio.h:229
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In kernel/power/swap.c (ffffffff81101836)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff81276013)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff8130f191)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff8131275c)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff8131532f)
Location: include/linux/bio.h:242
Inline: True
```
```
In fs/mpage.c (ffffffff813177ef)
Location: include/linux/bio.h:242
Inline: True
```
```
In fs/crypto/bio.c (ffffffff81339642)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (ffffffff8134bf53)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff8134d9c6)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813b2f1e)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813b3835)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/bio.c (ffffffff814c63f9)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff814cd2b5)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-flush.c (ffffffff814cfb5e)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff814d4b7c)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff814fa2a5)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (ffffffff818613c0)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/dm.c (ffffffff818764bf)
Location: include/linux/bio.h:242
Inline: True
```
```
In drivers/md/dm-linear.c (ffffffff8187cc89)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff8187d600)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff81880cda)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In kernel/power/swap.c (ffffffff8110dc66)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff81285af3)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff813220f1)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff813256ab)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff813281af)
Location: include/linux/bio.h:242
Inline: True
```
```
In fs/mpage.c (ffffffff8132a66f)
Location: include/linux/bio.h:242
Inline: True
```
```
In fs/crypto/bio.c (ffffffff8134f4c5)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (ffffffff81364223)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff81365c84)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813cbfa0)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813ccc5f)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/bio.c (ffffffff814df229)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff814e65fd)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-flush.c (ffffffff814e8ebe)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff814ede7c)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff81518211)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (ffffffff81892ff0)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/dm.c (ffffffff818a82bf)
Location: include/linux/bio.h:242
Inline: True
```
```
In drivers/md/dm-linear.c (ffffffff818aea69)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff818af3e0)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff818b2b98)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In kernel/power/swap.c (ffffffff81118c86)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff812b7be3)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff81359721)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff8135fc0f)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff8136236e)
Location: include/linux/bio.h:250
Inline: True
```
```
In fs/mpage.c (ffffffff81364178)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
```
```
In fs/crypto/bio.c (ffffffff8139597f)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (ffffffff813aa150)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_alloc_ioend
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff813ad0d4)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff81417431)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - fs/ext4/page-io.c:io_submit_init_bio
```
```
In fs/ext4/readpage.c (ffffffff81418cb2)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/block.c (ffffffff81449350)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In block/bio.c (ffffffff8153ee55)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff81543871)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-flush.c (ffffffff81547e12)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff8154d403)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff8157887d)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
```
In drivers/md/md.c (ffffffff81961698)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/dm.c (ffffffff819782ff)
Location: include/linux/bio.h:250
Inline: True
```
```
In drivers/md/dm-linear.c (ffffffff8197ecf9)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff8197f740)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map_range
```
```
In drivers/md/dm-io.c (ffffffff8198311a)
Location: include/linux/bio.h:250
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In kernel/power/swap.c (ffffffff81114756)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff812c32a3)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff813674b1)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff8136d48b)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff8136f60e)
Location: include/linux/bio.h:261
Inline: True
```
```
In fs/mpage.c (ffffffff81371078)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
```
```
In fs/crypto/bio.c (ffffffff813a6f2a)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/buffered-io.c (ffffffff813bb7a0)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_alloc_ioend
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff813be7c1)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff8142ae41)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - fs/ext4/page-io.c:io_submit_init_bio
```
```
In fs/ext4/readpage.c (ffffffff8142c8c9)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/block.c (ffffffff81465ac0)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In block/bio.c (ffffffff8155b661)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff81560753)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-flush.c (ffffffff81563b32)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff81569800)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff8159538a)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
```
In drivers/md/md.c (ffffffff81967fc8)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/dm-linear.c (ffffffff81983109)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff81983b30)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map_range
```
```
In drivers/md/dm-io.c (ffffffff81987237)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In kernel/power/swap.c (ffffffff81114f01)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff812caa82)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff8136dedf)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff81373d25)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81377308)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
```
```
In fs/mpage.c (ffffffff81377a2b)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
```
```
In fs/crypto/bio.c (ffffffff813adf85)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/buffered-io.c (ffffffff813c293d)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff813c5d85)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff81432701)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8143358e)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/block.c (ffffffff8146b25e)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In block/bio.c (ffffffff81563cf1)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff81568db7)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-flush.c (ffffffff8156c293)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff81571762)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff8159c128)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_mgmt
```
```
In drivers/md/md.c (ffffffff8194b55e)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/dm.c (ffffffff81960f1d)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:__send_empty_flush
```
```
In drivers/md/dm-linear.c (ffffffff8196753c)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff81967e1f)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff8196b8f4)
Location: include/linux/bio.h:264
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
  - drivers/md/dm-io.c:do_region
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
In kernel/power/swap.c (ffffffff81134fa1)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8130fa92)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff813bcbdf)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff813c38f7)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
```
```
In fs/mpage.c (ffffffff813c40ab)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
```
```
In fs/crypto/bio.c (ffffffff813fd98e)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/buffered-io.c (ffffffff814128a2)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/iomap/direct-io.c (ffffffff81415745)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff81485fc1)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81486d8f)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/block.c (ffffffff814c1aaa)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In block/fops.c (ffffffff815c5f52)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/bio.c (ffffffff815c79c1)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff815cd060)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-flush.c (ffffffff815d0463)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-merge.c (ffffffff815d3b62)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/blk-lib.c (ffffffff815d5e72)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff81604763)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
```
```
In drivers/md/md.c (ffffffff819f071e)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/dm-zone.c (ffffffff81a06231)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/md/dm.c (ffffffff81a0abbd)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:__send_empty_flush
```
```
In drivers/md/dm-linear.c (ffffffff81a0f7ac)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff81a1022f)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff81a13db4)
Location: include/linux/bio.h:263
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
  - drivers/md/dm-io.c:do_region
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
In fs/direct-io.c (ffffffff8144a7b8)
Location: include/linux/bio.h:238
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In block/bio.c (ffffffff816726c9)
Location: include/linux/bio.h:238
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-mq.c (ffffffff816862f6)
Location: include/linux/bio.h:238
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_update_request
```
```
In drivers/md/dm-zone.c (ffffffff81b6dea3)
Location: include/linux/bio.h:238
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/md/dm.c (ffffffff81b703d9)
Location: include/linux/bio.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_tio
```
```
In drivers/md/dm-linear.c (ffffffff81b77d8c)
Location: include/linux/bio.h:238
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff81b78d07)
Location: include/linux/bio.h:238
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
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
In block/fops.c (ffffffff8172c344)
Location: include/linux/bio.h:238
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO
```
```
In block/bio.c (ffffffff8172e049)
Location: include/linux/bio.h:238
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-mq.c (ffffffff81744446)
Location: include/linux/bio.h:238
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_update_request
```
```
In drivers/md/dm-zone.c (ffffffff81d0a3c1)
Location: include/linux/bio.h:238
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/md/dm.c (ffffffff81d0cce9)
Location: include/linux/bio.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_tio
```
```
In drivers/md/dm-linear.c (ffffffff81d152ec)
Location: include/linux/bio.h:238
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff81d163a7)
Location: include/linux/bio.h:238
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
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
In block/fops.c (ffffffff81768427)
Location: include/linux/bio.h:240
Inline: True
```
```
In block/bio.c (ffffffff8176a319)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-mq.c (ffffffff8177fe7a)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_update_request
```
```
In drivers/md/dm-zone.c (ffffffff81d734fb)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/md/dm.c (ffffffff81d75ab8)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_tio
```
```
In drivers/md/dm-linear.c (ffffffff81d7e43c)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff81d7f4c7)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
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
In block/fops.c (ffffffff817aa05a)
Location: include/linux/bio.h:240
Inline: True
```
```
In block/bio.c (ffffffff817ac779)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-mq.c (ffffffff817c16ba)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_update_request
```
```
In drivers/md/dm-zone.c (ffffffff81e2a601)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/md/dm.c (ffffffff81e2cbb8)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_tio
```
```
In drivers/md/dm-linear.c (ffffffff81e3590c)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff81e36ae7)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
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
In mm/page_io.c (ffff80001031fe1c)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffff8000103dae28)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffff8000103e0eb8)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffff8000103e3490)
Location: include/linux/bio.h:242
Inline: True
```
```
In fs/mpage.c (ffff8000103e5e0c)
Location: include/linux/bio.h:242
Inline: True
```
```
In fs/crypto/bio.c (ffff800010410c78)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (ffff80001042b548)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffff80001042cb24)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffff8000104a414c)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffff8000104a4d34)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/bio.c (ffff8000105dbc84)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffff8000105e3d5c)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-flush.c (ffff8000105e6e34)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffff8000105eca60)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffff80001061f8d0)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (ffff800010ae4684)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/dm.c (ffff800010afed7c)
Location: include/linux/bio.h:242
Inline: True
```
```
In drivers/md/dm-linear.c (ffff800010b05650)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffff800010b06048)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffff800010b0a320)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In kernel/power/swap.c (c03c0c40)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (c053878c)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (c05b4208)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (c05b812c)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (c05bb368)
Location: include/linux/bio.h:242
Inline: True
```
```
In fs/mpage.c (c05bd760)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
```
```
In fs/crypto/bio.c (c05dd424)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (c05f3f98)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (c05f57b4)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (c0665eac)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (c0666cd8)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/bio.c (c0789180)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (c0790ef0)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-flush.c (c0793b5c)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (c0798f80)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (c07c7428)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (c0bc7ca8)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/dm.c (c0bddeb4)
Location: include/linux/bio.h:242
Inline: True
```
```
In drivers/md/dm-linear.c (c0be438c)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (c0be5144)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (c0be87f4)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In mm/page_io.c (c0000000003f4d00)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (c0000000004e00b0)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (c0000000004e6f3c)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (c0000000004e9228)
Location: include/linux/bio.h:242
Inline: True
```
```
In fs/mpage.c (c0000000004ebcb8)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
```
```
In fs/crypto/bio.c (c00000000051e8d4)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (c00000000053c5e8)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (c00000000053e224)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (c0000000005d1348)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (c0000000005d20d4)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/bio.c (c00000000076c700)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (c00000000077791c)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-flush.c (c00000000077b710)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (c00000000078238c)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (c0000000007bf08c)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (c000000000bd0538)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/dm.c (c000000000becf78)
Location: include/linux/bio.h:242
Inline: True
```
```
In drivers/md/dm-linear.c (c000000000bf5ab8)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (c000000000bf6adc)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (c000000000bfbd1c)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In mm/page_io.c (ffffffe000221678)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffe000293846)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffe00029785a)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffe0002995d0)
Location: include/linux/bio.h:242
Inline: True
```
```
In fs/mpage.c (ffffffe00029b0ce)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
```
```
In fs/crypto/bio.c (ffffffe0002b92c4)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (ffffffe0002c8df6)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffe0002c9f00)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffe00032560a)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffe000325f34)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/bio.c (ffffffe00041f1c8)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffe00042560e)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-flush.c (ffffffe000427b9a)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffe00042c552)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffe0004522a8)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (ffffffe0006db878)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/dm.c (ffffffe0006ee78e)
Location: include/linux/bio.h:242
Inline: True
```
```
In drivers/md/dm-linear.c (ffffffe0006f45bc)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffe0006f4eb8)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffe0006f82fa)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In kernel/power/swap.c (ffffffff811066f2)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - kernel/power/swap.c:swap_read_pages
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8127e143)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff8131a6d1)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff8131dc8b)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff8132078f)
Location: include/linux/bio.h:242
Inline: True
```
```
In fs/mpage.c (ffffffff81322c4f)
Location: include/linux/bio.h:242
Inline: True
```
```
In fs/crypto/bio.c (ffffffff81347aa5)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (ffffffff8135c803)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff8135e264)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813c4580)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813c523f)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/bio.c (ffffffff814d7809)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff814debdd)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-flush.c (ffffffff814e149e)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff814e645c)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff815107f1)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (ffffffff81838e70)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/dm.c (ffffffff8184e13f)
Location: include/linux/bio.h:242
Inline: True
```
```
In drivers/md/dm-linear.c (ffffffff818548e9)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff81855260)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff81858a18)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In kernel/power/swap.c (ffffffff810f7126)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8126ff73)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff8130b271)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff8130e82b)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff8131132f)
Location: include/linux/bio.h:242
Inline: True
```
```
In fs/mpage.c (ffffffff813137ef)
Location: include/linux/bio.h:242
Inline: True
```
```
In fs/crypto/bio.c (ffffffff81338785)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (ffffffff8134d4a3)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff8134ef04)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813b5000)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813b5cbf)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/bio.c (ffffffff814c81c9)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff814cf57d)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-flush.c (ffffffff814d1e2e)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff814d69cc)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff81500b11)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (ffffffff818004e0)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/dm.c (ffffffff8181575f)
Location: include/linux/bio.h:242
Inline: True
```
```
In drivers/md/dm-linear.c (ffffffff8181bef9)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff8181c870)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff81820028)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In kernel/power/swap.c (ffffffff81104136)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8127bee3)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff813181a1)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff8131b75b)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff8131e25f)
Location: include/linux/bio.h:242
Inline: True
```
```
In fs/mpage.c (ffffffff8132071f)
Location: include/linux/bio.h:242
Inline: True
```
```
In fs/crypto/bio.c (ffffffff81345575)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (ffffffff8135a2d3)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff8135bd34)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813c1a10)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813c26cf)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/bio.c (ffffffff814d3899)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff814dac6d)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-flush.c (ffffffff814dd52e)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff814e24ec)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff8150c881)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (ffffffff818884a0)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/dm.c (ffffffff8189d76f)
Location: include/linux/bio.h:242
Inline: True
```
```
In drivers/md/dm-linear.c (ffffffff818a3f19)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff818a4890)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff818a8048)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In kernel/power/swap.c (ffffffff8110f526)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8128bac3)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff81329dc1)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff8132d53b)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff8132ff5f)
Location: include/linux/bio.h:242
Inline: True
```
```
In fs/mpage.c (ffffffff8133243f)
Location: include/linux/bio.h:242
Inline: True
```
```
In fs/crypto/bio.c (ffffffff81358855)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (ffffffff8136da17)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff8136f484)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813d6b70)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813d76ad)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/bio.c (ffffffff814ec429)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff814f39f8)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-flush.c (ffffffff814f638e)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff814fb37c)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff81525f61)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (ffffffff818a5a40)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/dm.c (ffffffff818b9acf)
Location: include/linux/bio.h:242
Inline: True
```
```
In drivers/md/dm-linear.c (ffffffff818c0159)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff818c0ad0)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff818c4288)
Location: include/linux/bio.h:242
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
</ul>

## Differences

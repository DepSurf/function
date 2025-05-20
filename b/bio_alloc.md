# Function: <code>bio_alloc</code>

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
In kernel/power/swap.c (ffffffff810d293a)
Location: include/linux/bio.h:444
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff811d1fce)
Location: include/linux/bio.h:444
Inline: True
```
```
In fs/buffer.c (ffffffff81244a42)
Location: include/linux/bio.h:444
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff81249dd7)
Location: include/linux/bio.h:444
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
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff8124d517)
Location: include/linux/bio.h:444
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
```
```
In fs/ext4/page-io.c (ffffffff812a0106)
Location: include/linux/bio.h:444
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff812e32cd)
Location: include/linux/bio.h:444
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/crypto.c (ffffffff812e5615)
Location: include/linux/bio.h:444
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_encrypted_zeroout
```
```
In block/blk-flush.c (ffffffff813bda8d)
Location: include/linux/bio.h:444
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff813c27f5)
Location: include/linux/bio.h:444
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_zeroout
```
```
In drivers/md/md.c (ffffffff81690d71)
Location: include/linux/bio.h:444
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
In kernel/power/swap.c (ffffffff810d76c1)
Location: include/linux/bio.h:393
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff811efb2e)
Location: include/linux/bio.h:393
Inline: True
```
```
In fs/buffer.c (ffffffff8126cf90)
Location: include/linux/bio.h:393
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff81274fbd)
Location: include/linux/bio.h:393
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
In fs/mpage.c (ffffffff81275c0d)
Location: include/linux/bio.h:393
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
```
```
In fs/crypto/crypto.c (ffffffff81288e7b)
Location: include/linux/bio.h:393
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_zeroout_range
```
```
In fs/ext4/page-io.c (ffffffff812cea95)
Location: include/linux/bio.h:393
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81313019)
Location: include/linux/bio.h:393
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-flush.c (ffffffff814019f3)
Location: include/linux/bio.h:393
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff814062a1)
Location: include/linux/bio.h:393
Inline: True
Inline callers:
  - block/blk-lib.c:next_bio
```
```
In drivers/md/md.c (ffffffff816f1a91)
Location: include/linux/bio.h:393
Inline: True
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
In kernel/power/swap.c (ffffffff810de22e)
Location: include/linux/bio.h:390
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff812004ce)
Location: include/linux/bio.h:390
Inline: True
```
```
In fs/buffer.c (ffffffff81280220)
Location: include/linux/bio.h:390
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff812839ff)
Location: include/linux/bio.h:390
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (ffffffff81288915)
Location: include/linux/bio.h:390
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
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff8128993d)
Location: include/linux/bio.h:390
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
```
```
In fs/crypto/crypto.c (ffffffff8129db44)
Location: include/linux/bio.h:390
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_zeroout_range
```
```
In fs/iomap.c (ffffffff812b0e3c)
Location: include/linux/bio.h:390
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff812e4890)
Location: include/linux/bio.h:390
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81328fbd)
Location: include/linux/bio.h:390
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-flush.c (ffffffff8141b653)
Location: include/linux/bio.h:390
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff81420531)
Location: include/linux/bio.h:390
Inline: True
Inline callers:
  - block/blk-lib.c:next_bio
```
```
In block/blk-zoned.c (ffffffff81448feb)
Location: include/linux/bio.h:390
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/md/md.c (ffffffff81723341)
Location: include/linux/bio.h:390
Inline: True
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
In kernel/power/swap.c (ffffffff810dd31e)
Location: include/linux/bio.h:407
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8120b12e)
Location: include/linux/bio.h:407
Inline: True
```
```
In fs/buffer.c (ffffffff8128db00)
Location: include/linux/bio.h:407
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff812910ce)
Location: include/linux/bio.h:407
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (ffffffff8129539f)
Location: include/linux/bio.h:407
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
In fs/mpage.c (ffffffff8129663d)
Location: include/linux/bio.h:407
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
```
```
In fs/crypto/bio.c (ffffffff812ae32b)
Location: include/linux/bio.h:407
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap.c (ffffffff812be223)
Location: include/linux/bio.h:407
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff8131e50a)
Location: include/linux/bio.h:407
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8131ed2a)
Location: include/linux/bio.h:407
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-flush.c (ffffffff81429343)
Location: include/linux/bio.h:407
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff8142e4e1)
Location: include/linux/bio.h:407
Inline: True
Inline callers:
  - block/blk-lib.c:next_bio
```
```
In block/blk-zoned.c (ffffffff8145751f)
Location: include/linux/bio.h:407
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/md/md.c (ffffffff8173a771)
Location: include/linux/bio.h:407
Inline: True
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
In kernel/power/swap.c (ffffffff810e556e)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff812244ba)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff812b06c0)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff812b3df2)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (ffffffff812b8526)
Location: include/linux/bio.h:403
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
In fs/mpage.c (ffffffff812b99cf)
Location: include/linux/bio.h:403
Inline: True
```
```
In fs/crypto/bio.c (ffffffff812d1d27)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap.c (ffffffff812e1b2d)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff81342b2a)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81343395)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-flush.c (ffffffff81454447)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff814596e1)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - block/blk-lib.c:next_bio
```
```
In block/blk-zoned.c (ffffffff8148322a)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/md/md.c (ffffffff817acd91)
Location: include/linux/bio.h:403
Inline: True
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
In kernel/power/swap.c (ffffffff810edab5)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff812469ef)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff812d84c6)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff812dc5ff)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (ffffffff812e172d)
Location: include/linux/bio.h:436
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
In fs/mpage.c (ffffffff812e2546)
Location: include/linux/bio.h:436
Inline: True
```
```
In fs/crypto/bio.c (ffffffff812fc85d)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap.c (ffffffff8130e25d)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff8137094e)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81371185)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-flush.c (ffffffff8148789c)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff8148cc45)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - block/blk-lib.c:next_bio
```
```
In block/blk-zoned.c (ffffffff814b7e7b)
Location: include/linux/bio.h:436
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/md/md.c (ffffffff817f2ea6)
Location: include/linux/bio.h:436
Inline: True
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
In kernel/power/swap.c (ffffffff810f9126)
Location: include/linux/bio.h:391
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8125ae0f)
Location: include/linux/bio.h:391
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff812ed984)
Location: include/linux/bio.h:391
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff812f1d6d)
Location: include/linux/bio.h:391
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (ffffffff812f639a)
Location: include/linux/bio.h:391
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
In fs/mpage.c (ffffffff812f7196)
Location: include/linux/bio.h:391
Inline: True
```
```
In fs/crypto/bio.c (ffffffff813120c4)
Location: include/linux/bio.h:391
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap.c (ffffffff81323a87)
Location: include/linux/bio.h:391
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_actor
  - fs/iomap.c:iomap_dio_zero
  - fs/iomap.c:iomap_readpage_actor
```
```
In fs/ext4/page-io.c (ffffffff81388dd6)
Location: include/linux/bio.h:391
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81389627)
Location: include/linux/bio.h:391
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-flush.c (ffffffff814a19fd)
Location: include/linux/bio.h:391
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff814a6575)
Location: include/linux/bio.h:391
Inline: True
Inline callers:
  - block/blk-lib.c:blk_next_bio
```
```
In drivers/md/md.c (ffffffff8181ee86)
Location: include/linux/bio.h:391
Inline: True
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
In kernel/power/swap.c (ffffffff81101815)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff81275fe3)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff8130f154)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff8131273b)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/direct-io.c (ffffffff8131531a)
Location: include/linux/bio.h:398
Inline: True
```
```
In fs/mpage.c (ffffffff813177c6)
Location: include/linux/bio.h:398
Inline: True
```
```
In fs/crypto/bio.c (ffffffff81339607)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (ffffffff8134b96e)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff8134d99d)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813b2eda)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813b37f4)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-flush.c (ffffffff814cfb3f)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff814d4475)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-lib.c:blk_next_bio
```
```
In drivers/md/md.c (ffffffff818612f6)
Location: include/linux/bio.h:398
Inline: True
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
In kernel/power/swap.c (ffffffff8110dc45)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff81285ac3)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff813220b4)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff8132568a)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/direct-io.c (ffffffff8132819a)
Location: include/linux/bio.h:398
Inline: True
```
```
In fs/mpage.c (ffffffff8132a646)
Location: include/linux/bio.h:398
Inline: True
```
```
In fs/crypto/bio.c (ffffffff8134f48a)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (ffffffff81363c3e)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff81365c5b)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813cbf5c)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813cca30)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-flush.c (ffffffff814e8e9f)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff814ed795)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-lib.c:blk_next_bio
```
```
In block/blk-zoned.c (ffffffff8151828a)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (ffffffff81892f26)
Location: include/linux/bio.h:398
Inline: True
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
In kernel/power/swap.c (ffffffff81118c65)
Location: include/linux/bio.h:406
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff812b7bb3)
Location: include/linux/bio.h:406
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff813596e4)
Location: include/linux/bio.h:406
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff8135fbee)
Location: include/linux/bio.h:406
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/direct-io.c (ffffffff81362359)
Location: include/linux/bio.h:406
Inline: True
```
```
In fs/mpage.c (ffffffff81364152)
Location: include/linux/bio.h:406
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
```
```
In fs/crypto/bio.c (ffffffff81395915)
Location: include/linux/bio.h:406
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (ffffffff813aa39b)
Location: include/linux/bio.h:406
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff813ad0ac)
Location: include/linux/bio.h:406
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff814173e5)
Location: include/linux/bio.h:406
Inline: True
Inline callers:
  - fs/ext4/page-io.c:io_submit_init_bio
```
```
In fs/ext4/readpage.c (ffffffff81418bfd)
Location: include/linux/bio.h:406
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/block.c (ffffffff814492e6)
Location: include/linux/bio.h:406
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In block/blk-flush.c (ffffffff81547de5)
Location: include/linux/bio.h:406
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff8154d3a7)
Location: include/linux/bio.h:406
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In drivers/md/md.c (ffffffff81961791)
Location: include/linux/bio.h:406
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
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
In kernel/power/swap.c (ffffffff81114735)
Location: include/linux/bio.h:417
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff812c3273)
Location: include/linux/bio.h:417
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff81367464)
Location: include/linux/bio.h:417
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff8136d46a)
Location: include/linux/bio.h:417
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/direct-io.c (ffffffff8136f5f9)
Location: include/linux/bio.h:417
Inline: True
```
```
In fs/mpage.c (ffffffff81371055)
Location: include/linux/bio.h:417
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
```
```
In fs/crypto/bio.c (ffffffff813a6ecb)
Location: include/linux/bio.h:417
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/buffered-io.c (ffffffff813bb9e3)
Location: include/linux/bio.h:417
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff813be799)
Location: include/linux/bio.h:417
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff8142ade5)
Location: include/linux/bio.h:417
Inline: True
Inline callers:
  - fs/ext4/page-io.c:io_submit_init_bio
```
```
In fs/ext4/readpage.c (ffffffff8142c7ed)
Location: include/linux/bio.h:417
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/block.c (ffffffff81465a56)
Location: include/linux/bio.h:417
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In block/blk-flush.c (ffffffff81563b1a)
Location: include/linux/bio.h:417
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff815697a4)
Location: include/linux/bio.h:417
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In drivers/md/md.c (ffffffff819680c7)
Location: include/linux/bio.h:417
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
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
In kernel/power/swap.c (ffffffff81114ef5)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff812caa69)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff8136dea4)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff81373d0a)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/direct-io.c (ffffffff81375eb1)
Location: include/linux/bio.h:420
Inline: True
```
```
In fs/mpage.c (ffffffff81377a15)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
```
```
In fs/crypto/bio.c (ffffffff813adf3b)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/buffered-io.c (ffffffff813c2adc)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff813c5d6e)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff814326c0)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff814334af)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/block.c (ffffffff8146b241)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In block/blk-lib.c (ffffffff8157170e)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
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
In kernel/power/swap.c (ffffffff81134f95)
Location: include/linux/bio.h:422
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8130fa79)
Location: include/linux/bio.h:422
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff813bcba4)
Location: include/linux/bio.h:422
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff813c229c)
Location: include/linux/bio.h:422
Inline: True
```
```
In fs/mpage.c (ffffffff813c4095)
Location: include/linux/bio.h:422
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
```
```
In fs/crypto/bio.c (ffffffff813fd931)
Location: include/linux/bio.h:422
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/buffered-io.c (ffffffff814129d8)
Location: include/linux/bio.h:422
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/iomap/direct-io.c (ffffffff8141572d)
Location: include/linux/bio.h:422
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff81485f80)
Location: include/linux/bio.h:422
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81486ce4)
Location: include/linux/bio.h:422
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/block.c (ffffffff814c1a8d)
Location: include/linux/bio.h:422
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In block/fops.c (ffffffff815c5f37)
Location: include/linux/bio.h:422
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO
```
```
In block/blk-lib.c (ffffffff815d5e1e)
Location: include/linux/bio.h:422
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
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
In kernel/power/swap.c (ffffffff81157247)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8137a4c3)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff81442fd4)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff81449272)
Location: include/linux/bio.h:420
Inline: True
```
```
In fs/mpage.c (ffffffff8144c55e)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (ffffffff81471152)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/buffered-io.c (ffffffff814896ca)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/iomap/direct-io.c (ffffffff8148c943)
Location: include/linux/bio.h:420
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815094f8)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8150a726)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/fops.c (ffffffff81670b2f)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO
```
```
In block/bio.c (ffffffff816732ee)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - block/bio.c:blk_next_bio
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
In kernel/power/swap.c (ffffffff81187f87)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff813f7f67)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff814d2293)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff814d7947)
Location: include/linux/bio.h:420
Inline: True
```
```
In fs/mpage.c (ffffffff814da984)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (ffffffff81502c42)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/buffered-io.c (ffffffff8151d03f)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/iomap/direct-io.c (ffffffff8151fe43)
Location: include/linux/bio.h:420
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815a40eb)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff815a51dc)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/fops.c (ffffffff8172c1bb)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO
```
```
In block/bio.c (ffffffff8172ee5e)
Location: include/linux/bio.h:420
Inline: True
Inline callers:
  - block/bio.c:blk_next_bio
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
In kernel/power/swap.c (ffffffff81199117)
Location: include/linux/bio.h:424
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8142b1a1)
Location: include/linux/bio.h:424
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff81508b3c)
Location: include/linux/bio.h:424
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff8150eeb6)
Location: include/linux/bio.h:424
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/direct-io.c (ffffffff81510a08)
Location: include/linux/bio.h:424
Inline: True
Inline callers:
  - fs/direct-io.c:dio_send_cur_page
  - fs/direct-io.c:dio_send_cur_page
```
```
In fs/crypto/bio.c (ffffffff8153a220)
Location: include/linux/bio.h:424
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/buffered-io.c (ffffffff815551e6)
Location: include/linux/bio.h:424
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/iomap/direct-io.c (ffffffff81557ef3)
Location: include/linux/bio.h:424
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815dab67)
Location: include/linux/bio.h:424
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/readpage.c (ffffffff815dbb7f)
Location: include/linux/bio.h:424
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/fops.c (ffffffff8176829e)
Location: include/linux/bio.h:424
Inline: True
```
```
In block/bio.c (ffffffff8176b08e)
Location: include/linux/bio.h:424
Inline: True
Inline callers:
  - block/bio.c:blk_next_bio
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
In kernel/power/swap.c (ffffffff811a817c)
Location: include/linux/bio.h:434
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8146495d)
Location: include/linux/bio.h:434
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio
  - mm/page_io.c:__swap_writepage
```
```
In fs/buffer.c (ffffffff8153d9a0)
Location: include/linux/bio.h:434
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/mpage.c (ffffffff81543744)
Location: include/linux/bio.h:434
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/direct-io.c (ffffffff81544ea8)
Location: include/linux/bio.h:434
Inline: True
Inline callers:
  - fs/direct-io.c:dio_send_cur_page
  - fs/direct-io.c:dio_send_cur_page
```
```
In fs/crypto/bio.c (ffffffff8156f5e0)
Location: include/linux/bio.h:434
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/buffered-io.c (ffffffff8158b4b8)
Location: include/linux/bio.h:434
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/iomap/direct-io.c (ffffffff8158e523)
Location: include/linux/bio.h:434
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff8161338f)
Location: include/linux/bio.h:434
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/readpage.c (ffffffff81614446)
Location: include/linux/bio.h:434
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/fops.c (ffffffff817a9ede)
Location: include/linux/bio.h:434
Inline: True
```
```
In block/bio.c (ffffffff817ad51e)
Location: include/linux/bio.h:434
Inline: True
Inline callers:
  - block/bio.c:blk_next_bio
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
In mm/page_io.c (ffff80001031fddc)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffff8000103dadec)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffff8000103e0e94)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (ffff8000103e346c)
Location: include/linux/bio.h:398
Inline: True
```
```
In fs/mpage.c (ffff8000103e5de4)
Location: include/linux/bio.h:398
Inline: True
```
```
In fs/crypto/bio.c (ffff800010410c58)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (ffff80001042bfe8)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffff80001042cafc)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffff8000104a4114)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffff8000104a4ccc)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-flush.c (ffff8000105e6e0c)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffff8000105ec3a4)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-lib.c:blk_next_bio
```
```
In block/blk-zoned.c (ffff80001061f958)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (ffff800010ae4598)
Location: include/linux/bio.h:398
Inline: True
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
In kernel/power/swap.c (c03c0c08)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (c053875c)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (c05b41c4)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (c05b8108)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/direct-io.c (c05bb354)
Location: include/linux/bio.h:398
Inline: True
```
```
In fs/mpage.c (c05bd730)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
```
```
In fs/crypto/bio.c (c05dd408)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (c05f38e8)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (c05f5790)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (c0665e68)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (c0666a94)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-flush.c (c0793b3c)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (c07987fc)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-lib.c:blk_next_bio
```
```
In block/blk-zoned.c (c07c7540)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (c0bc7be4)
Location: include/linux/bio.h:398
Inline: True
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
In mm/page_io.c (c0000000003f4cc8)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (c0000000004e006c)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (c0000000004e6f10)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (c0000000004e91f8)
Location: include/linux/bio.h:398
Inline: True
```
```
In fs/mpage.c (c0000000004ebc7c)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
```
```
In fs/crypto/bio.c (c00000000051e8b0)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (c00000000053b284)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (c00000000053e1f4)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (c0000000005d1300)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (c0000000005d205c)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-flush.c (c00000000077b6d0)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (c000000000781a14)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-lib.c:blk_next_bio
```
```
In block/blk-zoned.c (c0000000007bf138)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (c000000000bd03f0)
Location: include/linux/bio.h:398
Inline: True
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
In mm/page_io.c (ffffffe000221644)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffe000293816)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffe000297832)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (ffffffe0002995ae)
Location: include/linux/bio.h:398
Inline: True
```
```
In fs/mpage.c (ffffffe00029b0aa)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
  - fs/mpage.c:mpage_alloc
```
```
In fs/crypto/bio.c (ffffffe0002b926e)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (ffffffe0002c824e)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffe0002c9e56)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffe000325468)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffe000325ed2)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-flush.c (ffffffe000427b7a)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffe00042bfbc)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-lib.c:blk_next_bio
```
```
In block/blk-zoned.c (ffffffe00045231c)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (ffffffe0006db7aa)
Location: include/linux/bio.h:398
Inline: True
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
In kernel/power/swap.c (ffffffff811066b9)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - kernel/power/swap.c:swap_read_pages
  - kernel/power/swap.c:swap_read_pages
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8127e113)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff8131a694)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff8131dc6a)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/direct-io.c (ffffffff8132077a)
Location: include/linux/bio.h:398
Inline: True
```
```
In fs/mpage.c (ffffffff81322c26)
Location: include/linux/bio.h:398
Inline: True
```
```
In fs/crypto/bio.c (ffffffff81347a6a)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (ffffffff8135c21e)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff8135e23b)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813c453c)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813c5010)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-flush.c (ffffffff814e147f)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff814e5d75)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-lib.c:blk_next_bio
```
```
In block/blk-zoned.c (ffffffff8151086a)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (ffffffff81838da6)
Location: include/linux/bio.h:398
Inline: True
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
In kernel/power/swap.c (ffffffff810f7105)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8126ff43)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff8130b234)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff8130e80a)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/direct-io.c (ffffffff8131131a)
Location: include/linux/bio.h:398
Inline: True
```
```
In fs/mpage.c (ffffffff813137c6)
Location: include/linux/bio.h:398
Inline: True
```
```
In fs/crypto/bio.c (ffffffff8133874a)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (ffffffff8134cebe)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff8134eedb)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813b4fbc)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813b5a90)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-flush.c (ffffffff814d1e0f)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff814d62e5)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-lib.c:blk_next_bio
```
```
In block/blk-zoned.c (ffffffff81500b8a)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (ffffffff81800416)
Location: include/linux/bio.h:398
Inline: True
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
In kernel/power/swap.c (ffffffff81104115)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8127beb3)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff81318164)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff8131b73a)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/direct-io.c (ffffffff8131e24a)
Location: include/linux/bio.h:398
Inline: True
```
```
In fs/mpage.c (ffffffff813206f6)
Location: include/linux/bio.h:398
Inline: True
```
```
In fs/crypto/bio.c (ffffffff8134553a)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (ffffffff81359cee)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff8135bd0b)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813c19cc)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813c24a0)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-flush.c (ffffffff814dd50f)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff814e1e05)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-lib.c:blk_next_bio
```
```
In block/blk-zoned.c (ffffffff8150c8fa)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (ffffffff818883d6)
Location: include/linux/bio.h:398
Inline: True
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
In kernel/power/swap.c (ffffffff8110f505)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8128ba93)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - mm/page_io.c:get_swap_bio
```
```
In fs/buffer.c (ffffffff81329d84)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/block_dev.c (ffffffff8132d51a)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/direct-io.c (ffffffff8132ff4a)
Location: include/linux/bio.h:398
Inline: True
```
```
In fs/mpage.c (ffffffff81332416)
Location: include/linux/bio.h:398
Inline: True
```
```
In fs/crypto/bio.c (ffffffff8135881a)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/buffered-io.c (ffffffff8136d3fe)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffffffff8136f45b)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813d6b2c)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813d7630)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-flush.c (ffffffff814f636f)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-flush.c:blkdev_issue_flush
```
```
In block/blk-lib.c (ffffffff814facc5)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-lib.c:blk_next_bio
```
```
In block/blk-zoned.c (ffffffff81525fd5)
Location: include/linux/bio.h:398
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (ffffffff818a5976)
Location: include/linux/bio.h:398
Inline: True
```
</details>
</li>
</ul>

## Differences

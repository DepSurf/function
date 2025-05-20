# Function: <code>bio_set_op_attrs</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810de25a)
Location: include/linux/blk_types.h:212
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff81200bf6)
Location: include/linux/blk_types.h:212
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/buffer.c (ffffffff812802ef)
Location: include/linux/blk_types.h:212
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff81288935)
Location: include/linux/blk_types.h:212
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
In fs/mpage.c (ffffffff8128a34a)
Location: include/linux/blk_types.h:212
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/crypto.c (ffffffff8129db88)
Location: include/linux/blk_types.h:212
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_zeroout_range
```
```
In fs/iomap.c (ffffffff812b0dd1)
Location: include/linux/blk_types.h:212
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff812e449a)
Location: include/linux/blk_types.h:212
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_io_submit
```
```
In fs/ext4/readpage.c (ffffffff8132901f)
Location: include/linux/blk_types.h:212
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/bio.c (ffffffff8140fd7b)
Location: include/linux/blk_types.h:212
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
```
In block/blk-map.c (ffffffff8141d4b7)
Location: include/linux/blk_types.h:212
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-lib.c (ffffffff81420a69)
Location: include/linux/blk_types.h:212
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff8144900a)
Location: include/linux/blk_types.h:212
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/md/md.c (ffffffff817233ab)
Location: include/linux/blk_types.h:212
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
```
```
In drivers/md/dm-io.c (ffffffff8173d406)
Location: include/linux/blk_types.h:212
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In kernel/power/swap.c (ffffffff810dd34a)
Location: include/linux/blk_types.h:263
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8120b88b)
Location: include/linux/blk_types.h:263
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/buffer.c (ffffffff8128dbcf)
Location: include/linux/blk_types.h:263
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff812953e1)
Location: include/linux/blk_types.h:263
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
In fs/mpage.c (ffffffff8129716a)
Location: include/linux/blk_types.h:263
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (ffffffff812ae36d)
Location: include/linux/blk_types.h:263
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap.c (ffffffff812be1b8)
Location: include/linux/blk_types.h:263
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff8131e180)
Location: include/linux/blk_types.h:263
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_io_submit
```
```
In fs/ext4/readpage.c (ffffffff8131ed93)
Location: include/linux/blk_types.h:263
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-lib.c (ffffffff8142eabd)
Location: include/linux/blk_types.h:263
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff8145753e)
Location: include/linux/blk_types.h:263
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/md/md.c (ffffffff8173a831)
Location: include/linux/blk_types.h:263
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
```
```
In drivers/md/dm-io.c (ffffffff817570d9)
Location: include/linux/blk_types.h:263
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In kernel/power/swap.c (ffffffff810e55c7)
Location: include/linux/blk_types.h:271
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff81224db1)
Location: include/linux/blk_types.h:271
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/buffer.c (ffffffff812b07bd)
Location: include/linux/blk_types.h:271
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff812b858f)
Location: include/linux/blk_types.h:271
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
In fs/mpage.c (ffffffff812ba3da)
Location: include/linux/blk_types.h:271
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (ffffffff812d1da2)
Location: include/linux/blk_types.h:271
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap.c (ffffffff812e1ab1)
Location: include/linux/blk_types.h:271
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff81342790)
Location: include/linux/blk_types.h:271
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_io_submit
```
```
In fs/ext4/readpage.c (ffffffff8134342d)
Location: include/linux/blk_types.h:271
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-lib.c (ffffffff81459d46)
Location: include/linux/blk_types.h:271
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff8148326c)
Location: include/linux/blk_types.h:271
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/md/md.c (ffffffff817ace6c)
Location: include/linux/blk_types.h:271
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
```
```
In drivers/md/dm-io.c (ffffffff817c9314)
Location: include/linux/blk_types.h:271
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
In kernel/power/swap.c (ffffffff810edb00)
Location: include/linux/blk_types.h:367
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8124736a)
Location: include/linux/blk_types.h:367
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/buffer.c (ffffffff812d85ae)
Location: include/linux/blk_types.h:367
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff812e176d)
Location: include/linux/blk_types.h:367
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
In fs/mpage.c (ffffffff812e2f35)
Location: include/linux/blk_types.h:367
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (ffffffff812fc8ec)
Location: include/linux/blk_types.h:367
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap.c (ffffffff8130dff5)
Location: include/linux/blk_types.h:367
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff81370610)
Location: include/linux/blk_types.h:367
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_io_submit
```
```
In fs/ext4/readpage.c (ffffffff81371213)
Location: include/linux/blk_types.h:367
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-lib.c (ffffffff8148d40a)
Location: include/linux/blk_types.h:367
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff814b7ec9)
Location: include/linux/blk_types.h:367
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/md/md.c (ffffffff817f2f9a)
Location: include/linux/blk_types.h:367
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
```
```
In drivers/md/dm-io.c (ffffffff818120c7)
Location: include/linux/blk_types.h:367
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
In kernel/power/swap.c (ffffffff810f9166)
Location: include/linux/blk_types.h:375
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8125b7bc)
Location: include/linux/blk_types.h:375
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/buffer.c (ffffffff812eda58)
Location: include/linux/blk_types.h:375
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff812f63db)
Location: include/linux/blk_types.h:375
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
In fs/mpage.c (ffffffff812f7b95)
Location: include/linux/blk_types.h:375
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (ffffffff81312158)
Location: include/linux/blk_types.h:375
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap.c (ffffffff8132373a)
Location: include/linux/blk_types.h:375
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff81388aa1)
Location: include/linux/blk_types.h:375
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_io_submit
```
```
In fs/ext4/readpage.c (ffffffff813896c5)
Location: include/linux/blk_types.h:375
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-lib.c (ffffffff814a6c89)
Location: include/linux/blk_types.h:375
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff814cb990)
Location: include/linux/blk_types.h:375
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/lightnvm/core.c (ffffffff81698cf5)
Location: include/linux/blk_types.h:375
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/md/md.c (ffffffff8181ef6f)
Location: include/linux/blk_types.h:375
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
```
```
In drivers/md/dm-io.c (ffffffff8183e046)
Location: include/linux/blk_types.h:375
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
In kernel/power/swap.c (ffffffff8110185b)
Location: include/linux/blk_types.h:376
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff81276908)
Location: include/linux/blk_types.h:376
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/buffer.c (ffffffff8130f228)
Location: include/linux/blk_types.h:376
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff81315356)
Location: include/linux/blk_types.h:376
Inline: True
```
```
In fs/mpage.c (ffffffff813181d9)
Location: include/linux/blk_types.h:376
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (ffffffff8133969f)
Location: include/linux/blk_types.h:376
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/direct-io.c (ffffffff8134d788)
Location: include/linux/blk_types.h:376
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813b2b91)
Location: include/linux/blk_types.h:376
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_io_submit
```
```
In fs/ext4/readpage.c (ffffffff813b3892)
Location: include/linux/blk_types.h:376
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-lib.c (ffffffff814d4ba2)
Location: include/linux/blk_types.h:376
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff814fa2cb)
Location: include/linux/blk_types.h:376
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/lightnvm/core.c (ffffffff816d1745)
Location: include/linux/blk_types.h:376
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/md/md.c (ffffffff818613ea)
Location: include/linux/blk_types.h:376
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
```
```
In drivers/md/dm-io.c (ffffffff81880d1e)
Location: include/linux/blk_types.h:376
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
In kernel/power/swap.c (ffffffff8110dc8b)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff812863f8)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/buffer.c (ffffffff81322180)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff813281d6)
Location: include/linux/blk_types.h:384
Inline: True
```
```
In fs/mpage.c (ffffffff8132b034)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (ffffffff8134f522)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/direct-io.c (ffffffff81365a48)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813cbbf1)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_io_submit
```
```
In fs/ext4/readpage.c (ffffffff813cccbc)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-lib.c (ffffffff814edea2)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff8151823a)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/lightnvm/core.c (ffffffff816f56f5)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/md/md.c (ffffffff8189301a)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
```
```
In drivers/md/dm-io.c (ffffffff818b2bdc)
Location: include/linux/blk_types.h:384
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
In kernel/power/swap.c (ffffffff81118cab)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff812b86c3)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/buffer.c (ffffffff813597b0)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff81362395)
Location: include/linux/blk_types.h:409
Inline: True
```
```
In fs/mpage.c (ffffffff81364ce4)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (ffffffff813959eb)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/direct-io.c (ffffffff813acecb)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff81417fc7)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81418d0b)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-lib.c (ffffffff8154d429)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In drivers/lightnvm/core.c (ffffffff817adf55)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/md/md.c (ffffffff819616c2)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
```
```
In drivers/md/dm-io.c (ffffffff81983154)
Location: include/linux/blk_types.h:409
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
In kernel/power/swap.c (ffffffff8111477e)
Location: include/linux/blk_types.h:473
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff812c3cfc)
Location: include/linux/blk_types.h:473
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/buffer.c (ffffffff81367543)
Location: include/linux/blk_types.h:473
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff8136f638)
Location: include/linux/blk_types.h:473
Inline: True
```
```
In fs/mpage.c (ffffffff81371c64)
Location: include/linux/blk_types.h:473
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (ffffffff813a6f9a)
Location: include/linux/blk_types.h:473
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/direct-io.c (ffffffff813be5ae)
Location: include/linux/blk_types.h:473
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff8142bc48)
Location: include/linux/blk_types.h:473
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8142c928)
Location: include/linux/blk_types.h:473
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-lib.c (ffffffff81569829)
Location: include/linux/blk_types.h:473
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In drivers/lightnvm/core.c (ffffffff817c2ad5)
Location: include/linux/blk_types.h:473
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/md/md.c (ffffffff81967ff5)
Location: include/linux/blk_types.h:473
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
```
```
In drivers/md/dm-io.c (ffffffff81987274)
Location: include/linux/blk_types.h:473
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
In kernel/power/swap.c (ffffffff81114f35)
Location: include/linux/blk_types.h:447
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In fs/buffer.c (ffffffff8136df78)
Location: include/linux/blk_types.h:447
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff81375ee6)
Location: include/linux/blk_types.h:447
Inline: True
```
```
In fs/mpage.c (ffffffff81378f2f)
Location: include/linux/blk_types.h:447
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (ffffffff813adffd)
Location: include/linux/blk_types.h:447
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/direct-io.c (ffffffff813c55e1)
Location: include/linux/blk_types.h:447
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff81432911)
Location: include/linux/blk_types.h:447
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff814335fb)
Location: include/linux/blk_types.h:447
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-lib.c (ffffffff8157178b)
Location: include/linux/blk_types.h:447
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In drivers/lightnvm/core.c (ffffffff817a5f95)
Location: include/linux/blk_types.h:447
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/md/dm-io.c (ffffffff8196b936)
Location: include/linux/blk_types.h:447
Inline: True
Inline callers:
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
In kernel/power/swap.c (ffffffff81134fd5)
Location: include/linux/blk_types.h:438
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In fs/buffer.c (ffffffff813bcc78)
Location: include/linux/blk_types.h:438
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff813c22d1)
Location: include/linux/blk_types.h:438
Inline: True
```
```
In fs/mpage.c (ffffffff813c5a8f)
Location: include/linux/blk_types.h:438
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (ffffffff813fda15)
Location: include/linux/blk_types.h:438
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/direct-io.c (ffffffff81415382)
Location: include/linux/blk_types.h:438
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff814861d9)
Location: include/linux/blk_types.h:438
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81486e12)
Location: include/linux/blk_types.h:438
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-lib.c (ffffffff815d5e9b)
Location: include/linux/blk_types.h:438
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In drivers/md/dm-io.c (ffffffff81a13df6)
Location: include/linux/blk_types.h:438
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/page_io.c (ffff800010320a58)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/buffer.c (ffff8000103daeb0)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffff8000103e34b8)
Location: include/linux/blk_types.h:384
Inline: True
```
```
In fs/mpage.c (ffff8000103e6668)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (ffff800010410cec)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/direct-io.c (ffff80001042c8f0)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffff8000104a3d60)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_io_submit
```
```
In fs/ext4/readpage.c (ffff8000104a4d64)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-lib.c (ffff8000105eca84)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffff80001061f8f8)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/lightnvm/core.c (ffff8000108decf0)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/md/md.c (ffff800010ae46b0)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
```
```
In drivers/md/dm-io.c (ffff800010b0a35c)
Location: include/linux/blk_types.h:384
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
In kernel/power/swap.c (c03c0c60)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (c0539440)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/buffer.c (c05b428c)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (c05bb390)
Location: include/linux/blk_types.h:384
Inline: True
```
```
In fs/mpage.c (c05be264)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (c05dd498)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/direct-io.c (c05f5500)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (c0665c24)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_io_submit
```
```
In fs/ext4/readpage.c (c0666d4c)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-lib.c (c0798fa4)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (c07c7448)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/lightnvm/core.c (c09cde0c)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/md/md.c (c0bc7cd0)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
```
```
In drivers/md/dm-io.c (c0be882c)
Location: include/linux/blk_types.h:384
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
In mm/page_io.c (c0000000003f5d18)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/buffer.c (c0000000004e0144)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (c0000000004e9254)
Location: include/linux/blk_types.h:384
Inline: True
```
```
In fs/mpage.c (c0000000004ec960)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (c00000000051e948)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/direct-io.c (c00000000053df58)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (c0000000005d0e0c)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_io_submit
```
```
In fs/ext4/readpage.c (c0000000005d2120)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-lib.c (c0000000007823b4)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (c0000000007bf0b8)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/lightnvm/core.c (c000000000972b3c)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/md/md.c (c000000000bd0568)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
```
```
In drivers/md/dm-io.c (c000000000bfbd54)
Location: include/linux/blk_types.h:384
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
In mm/page_io.c (ffffffe000222054)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/buffer.c (ffffffe0002938c0)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffe0002995fa)
Location: include/linux/blk_types.h:384
Inline: True
```
```
In fs/mpage.c (ffffffe00029b98c)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (ffffffe0002b9310)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/direct-io.c (ffffffe0002c9cee)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffe0003252b8)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_io_submit
```
```
In fs/ext4/readpage.c (ffffffe000325f64)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-lib.c (ffffffe00042c578)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffe000452298)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/lightnvm/core.c (ffffffe000574f7c)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/md/md.c (ffffffe0006db8a2)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
```
```
In drivers/md/dm-io.c (ffffffe0006f832e)
Location: include/linux/blk_types.h:384
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
In kernel/power/swap.c (ffffffff8110671a)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - kernel/power/swap.c:swap_read_pages
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8127ea48)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/buffer.c (ffffffff8131a760)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff813207b6)
Location: include/linux/blk_types.h:384
Inline: True
```
```
In fs/mpage.c (ffffffff81323614)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (ffffffff81347b02)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/direct-io.c (ffffffff8135e028)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813c41d1)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_io_submit
```
```
In fs/ext4/readpage.c (ffffffff813c529c)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-lib.c (ffffffff814e6482)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff8151081a)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/lightnvm/core.c (ffffffff816baee5)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/md/md.c (ffffffff81838e9a)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
```
```
In drivers/md/dm-io.c (ffffffff81858a5c)
Location: include/linux/blk_types.h:384
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
In kernel/power/swap.c (ffffffff810f714b)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff81270878)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/buffer.c (ffffffff8130b300)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff81311356)
Location: include/linux/blk_types.h:384
Inline: True
```
```
In fs/mpage.c (ffffffff813141b4)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (ffffffff813387e2)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/direct-io.c (ffffffff8134ecc8)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813b4c51)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_io_submit
```
```
In fs/ext4/readpage.c (ffffffff813b5d1c)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-lib.c (ffffffff814d69f2)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff81500b3a)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/md/md.c (ffffffff8180050a)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
```
```
In drivers/md/dm-io.c (ffffffff8182006c)
Location: include/linux/blk_types.h:384
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
In kernel/power/swap.c (ffffffff8110415b)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8127c7e8)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/buffer.c (ffffffff81318230)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff8131e286)
Location: include/linux/blk_types.h:384
Inline: True
```
```
In fs/mpage.c (ffffffff813210e4)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (ffffffff813455d2)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/direct-io.c (ffffffff8135baf8)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813c1661)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_io_submit
```
```
In fs/ext4/readpage.c (ffffffff813c272c)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-lib.c (ffffffff814e2512)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff8150c8aa)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/lightnvm/core.c (ffffffff816e93b5)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/md/md.c (ffffffff818884ca)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
```
```
In drivers/md/dm-io.c (ffffffff818a808c)
Location: include/linux/blk_types.h:384
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
In kernel/power/swap.c (ffffffff8110f54b)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In mm/page_io.c (ffffffff8128c3b8)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/buffer.c (ffffffff81329e50)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/direct-io.c (ffffffff8132ff86)
Location: include/linux/blk_types.h:384
Inline: True
```
```
In fs/mpage.c (ffffffff81332e24)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/bio.c (ffffffff813588b2)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/direct-io.c (ffffffff8136f248)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/page-io.c (ffffffff813d67c1)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_io_submit
```
```
In fs/ext4/readpage.c (ffffffff813d770a)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-lib.c (ffffffff814fb3a2)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-zoned.c (ffffffff81525f8a)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/lightnvm/core.c (ffffffff81703bf5)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/md/md.c (ffffffff818a5a6a)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - drivers/md/md.c:sync_page_io
```
```
In drivers/md/dm-io.c (ffffffff818c42cc)
Location: include/linux/blk_types.h:384
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
</ul>

## Differences

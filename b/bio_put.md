# Function: <code>bio_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b1ba0)
Location: block/bio.c:538
Inline: True
Direct callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:end_swap_bio_write
  - mm/page_io.c:end_swap_bio_read
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_io_submit
  - fs/ext4/readpage.c:completion_pages
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/crypto.c:ext4_encrypted_zeroout
  - fs/ext4/crypto.c:ext4_encrypted_zeroout
  - fs/ext4/crypto.c:ext4_encrypted_zeroout
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern_endio
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_endio
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-lib.c:bio_batch_end_io
  - block/blk-lib.c:bio_batch_end_io
  - block/bounce.c:bounce_end_io
  - drivers/lightnvm/core.c:nvm_submit_ppa
  - drivers/block/virtio_blk.c:virtblk_serial_show
  - drivers/block/xen-blkfront.c:split_bio_end
  - drivers/block/xen-blkfront.c:split_bio_end
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:end_clone_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff813b1ba0-ffffffff813b1bc7: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f5550)
Location: block/bio.c:537
Inline: True
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/crypto.c:completion_pages
  - fs/crypto/crypto.c:fscrypt_zeroout_range
  - fs/crypto/crypto.c:fscrypt_zeroout_range
  - fs/crypto/crypto.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/readpage.c:mpage_end_io
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern_endio
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/bounce.c:bounce_end_io
  - drivers/lightnvm/core.c:__nvm_submit_ppa
  - drivers/block/xen-blkfront.c:split_bio_end
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff813f5550-ffffffff813f5577: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140ef70)
Location: block/bio.c:541
Inline: True
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/crypto.c:completion_pages
  - fs/crypto/crypto.c:fscrypt_zeroout_range
  - fs/crypto/crypto.c:fscrypt_zeroout_range
  - fs/crypto/crypto.c:fscrypt_zeroout_range
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/readpage.c:mpage_end_io
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern_endio
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/bounce.c:bounce_end_io
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/lightnvm/core.c:__nvm_submit_ppa
  - drivers/block/xen-blkfront.c:split_bio_end
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff8140ef70-ffffffff8140ef97: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141ca70)
Location: block/bio.c:555
Inline: True
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:completion_pages
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/readpage.c:mpage_end_io
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern_endio
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/bounce.c:bounce_end_io
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff8141ca70-ffffffff8141ca97: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81447640)
Location: block/bio.c:555
Inline: True
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:completion_pages
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/readpage.c:mpage_end_io
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern_endio
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/bounce.c:bounce_end_io
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff81447640-ffffffff81447667: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8147a740)
Location: block/bio.c:556
Inline: True
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:completion_pages
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/readpage.c:mpage_end_io
  - block/bio.c:bio_endio
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern_endio
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
  - block/bounce.c:bounce_end_io
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff8147a740-ffffffff8147a767: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81498510)
Location: block/bio.c:558
Inline: True
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:completion_pages
  - fs/iomap.c:iomap_dio_bio_actor
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/iomap.c:iomap_read_end_io
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/readpage.c:mpage_end_io
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern_endio
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/bounce.c:blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff81498510-ffffffff81498537: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c6390)
Location: block/bio.c:546
Inline: True
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:completion_pages
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/readpage.c:mpage_end_io
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern_endio
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff814c6390-ffffffff814c63b6: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814df1c0)
Location: block/bio.c:598
Inline: True
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:completion_pages
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern_endio
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff814df1c0-ffffffff814df1e6: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153ed70)
Location: block/bio.c:645
Inline: True
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/readpage.c:__read_end_io
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:__blk_rq_unmap_user
  - block/blk-map.c:__blk_rq_unmap_user
  - block/blk-map.c:__blk_rq_unmap_user
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_map_kern
  - block/blk-map.c:bio_map_kern_endio
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/bounce.c:bounce_end_io
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff8153ed70-ffffffff8153ed96: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155b580)
Location: block/bio.c:647
Inline: True
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/readpage.c:__read_end_io
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_map_kern
  - block/blk-map.c:bio_map_kern_endio
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/bounce.c:bounce_end_io
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff8155b580-ffffffff8155b5a6: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81563c10)
Location: block/bio.c:602
Inline: True
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/readpage.c:__read_end_io
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_map_kern_endio
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff81563c10-ffffffff81563c36: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c7810)
Location: block/bio.c:678
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/readpage.c:__read_end_io
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:blkdev_bio_end_io
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_map_kern_endio
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - drivers/md/md.c:md_end_io_acct
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dm_io_dec_pending
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff815c7810-ffffffff815c790e: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81672510)
Location: block/bio.c:736
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/readpage.c:__read_end_io
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:blkdev_bio_end_io
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_chain_endio
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-mq.c:blk_rq_prep_clone
  - block/blk-mq.c:blk_rq_prep_clone
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - drivers/md/md.c:md_end_io_acct
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dm_io_complete
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff81672510-ffffffff8167260a: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172e7bb)
Location: block/bio.c:799
Inline: True
Inline callers:
  - block/bio.c:bio_dirty_fn
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/readpage.c:__read_end_io
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:blkdev_bio_end_io
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_chain_endio
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-mq.c:blk_rq_prep_clone
  - block/blk-mq.c:blk_rq_prep_clone
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - drivers/md/md.c:md_end_io_acct
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:__dm_io_complete
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff8172dfb0-ffffffff8172dffb: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8176a1f0)
Location: block/bio.c:798
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/readpage.c:__read_end_io
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:blkdev_bio_end_io
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_chain_endio
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-mq.c:blk_rq_prep_clone
  - block/blk-mq.c:blk_rq_prep_clone
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - drivers/md/md.c:md_end_io_acct
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:__dm_io_complete
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff8176a1f0-ffffffff8176a23b: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ac4a0)
Location: block/bio.c:798
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/readpage.c:__read_end_io
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:blkdev_bio_end_io
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_chain_endio
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-mq.c:blk_rq_prep_clone
  - block/blk-mq.c:blk_rq_prep_clone
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - drivers/md/md.c:md_end_clone_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:__dm_io_complete
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff817ac4a0-ffffffff817ac4eb: bio_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dbba0)
Location: block/bio.c:598
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:completion_pages
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern_endio
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffff8000105dbba0-ffff8000105dbc14: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (c07890b8)
Location: block/bio.c:598
Inline: True
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:completion_pages
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern_endio
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
c07890b8-c078911c: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076c5e0)
Location: block/bio.c:598
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:completion_pages
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern_endio
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
c00000000076c5e0-c00000000076c638: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041f10c)
Location: block/bio.c:598
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:completion_pages
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_release_io_end
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern_endio
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffe00041f10c-ffffffe00041f164: bio_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d77a0)
Location: block/bio.c:598
Inline: True
Direct callers:
  - kernel/power/swap.c:swap_read_pages
  - kernel/power/swap.c:swap_read_pages
  - kernel/power/swap.c:swap_read_pages
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:completion_pages
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern_endio
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff814d77a0-ffffffff814d77c6: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c8160)
Location: block/bio.c:598
Inline: True
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:completion_pages
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern_endio
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff814c8160-ffffffff814c8186: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d3830)
Location: block/bio.c:598
Inline: True
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:completion_pages
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern_endio
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff814d3830-ffffffff814d3856: bio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bio_put(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ec3c0)
Location: block/bio.c:598
Inline: True
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:completion_pages
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_kern_endio
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:endio
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff814ec3c0-ffffffff814ec3e6: bio_put (STB_GLOBAL)
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

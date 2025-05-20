# Function: <code>bio_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void bio_init(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b0210)
Location: block/bio.c:269
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff813b0210-ffffffff813b025a: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void bio_init(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f51f7)
Location: block/bio.c:273
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff813f3c60-ffffffff813f3caa: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140ebd7)
Location: block/bio.c:273
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8140d4d0-ffffffff8140d523: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141b230)
Location: block/bio.c:277
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8141b230-ffffffff8141b283: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81445e60)
Location: block/bio.c:277
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81445e60-ffffffff81445eb3: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81478de0)
Location: block/bio.c:277
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81478de0-ffffffff81478e33: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81497040)
Location: block/bio.c:279
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap.c:iomap_read_page_sync
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff81497040-ffffffff81497093: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c49b0)
Location: block/bio.c:267
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814c49b0-ffffffff814c4a00: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814dd840)
Location: block/bio.c:270
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814dd840-ffffffff814dd893: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153f170)
Location: block/bio.c:274
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8153d1e0-ffffffff8153d233: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155b968)
Location: block/bio.c:278
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff81559cf0-ffffffff81559d43: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81563aff)
Location: block/bio.c:246
Inline: True
Inline callers:
  - block/bio.c:bio_kmalloc
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - block/blk-flush.c:blkdev_issue_flush
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff81562600-ffffffff81562653: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c7453)
Location: block/bio.c:251
Inline: True
Inline callers:
  - block/bio.c:bio_kmalloc
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
Direct callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - block/fops.c:__blkdev_direct_IO_simple
  - block/blk-flush.c:blkdev_issue_flush
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff815c6220-ffffffff815c62c2: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bio_init(struct bio *bio, struct block_device *bdev, struct bio_vec *table, short unsigned int max_vecs, unsigned int opf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81672314)
Location: block/bio.c:241
Inline: True
Inline callers:
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
Direct callers:
  - fs/iomap/buffered-io.c:iomap_read_folio_sync
  - fs/squashfs/block.c:squashfs_bio_read
  - block/fops.c:__blkdev_direct_IO_simple
  - block/fops.c:__blkdev_direct_IO_simple
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff81671080-ffffffff81671151: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bio_init(struct bio *bio, struct block_device *bdev, struct bio_vec *table, short unsigned int max_vecs, blk_opf_t opf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172dc64)
Location: block/bio.c:247
Inline: True
Inline callers:
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
Direct callers:
  - fs/iomap/buffered-io.c:iomap_read_folio_sync
  - fs/squashfs/block.c:squashfs_bio_read
  - block/fops.c:__blkdev_direct_IO_simple
  - block/fops.c:__blkdev_direct_IO_simple
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_bio_alloc
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff8172c810-ffffffff8172c8e1: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bio_init(struct bio *bio, struct block_device *bdev, struct bio_vec *table, short unsigned int max_vecs, blk_opf_t opf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81769ea4)
Location: block/bio.c:246
Inline: True
Inline callers:
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
Direct callers:
  - mm/page_io.c:swap_readpage_bdev_sync
  - mm/page_io.c:swap_writepage_bdev_sync
  - fs/iomap/buffered-io.c:iomap_read_folio_sync
  - fs/squashfs/block.c:squashfs_bio_read
  - block/fops.c:__blkdev_direct_IO_simple
  - block/fops.c:__blkdev_direct_IO_simple
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_kern
  - block/blk-map.c:blk_rq_map_bio_alloc
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff81768b90-ffffffff81768c61: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bio_init(struct bio *bio, struct block_device *bdev, struct bio_vec *table, short unsigned int max_vecs, blk_opf_t opf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ac054)
Location: block/bio.c:246
Inline: True
Inline callers:
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
Direct callers:
  - mm/page_io.c:swap_read_folio_bdev_sync
  - mm/page_io.c:swap_writepage_bdev_sync
  - fs/iomap/buffered-io.c:iomap_read_folio_sync
  - fs/squashfs/block.c:squashfs_bio_read
  - block/fops.c:__blkdev_direct_IO_simple
  - block/fops.c:__blkdev_direct_IO_simple
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_kern
  - block/blk-map.c:blk_rq_map_bio_alloc
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:sync_page_io
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff817aaa80-ffffffff817aab51: bio_init (STB_GLOBAL)
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
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105d9f18)
Location: block/bio.c:270
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffff8000105d9f18-ffff8000105d9f80: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c07873ec)
Location: block/bio.c:270
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
c07873ec-c0787430: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076a370)
Location: block/bio.c:270
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
c00000000076a370-c00000000076a3e4: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041f670)
Location: block/bio.c:270
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffe00041d8c6-ffffffe00041d910: bio_init (STB_GLOBAL)
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
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d5e20)
Location: block/bio.c:270
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814d5e20-ffffffff814d5e73: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c6840)
Location: block/bio.c:270
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814c6840-ffffffff814c6893: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d1eb0)
Location: block/bio.c:270
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814d1eb0-ffffffff814d1f03: bio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bio_init(struct bio *bio, struct bio_vec *table, short unsigned int max_vecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ea960)
Location: block/bio.c:270
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814ea960-ffffffff814ea9b3: bio_init (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bio_vec *table</code>
</li>
<li>
<b>Param added. </b>
<code>short unsigned int max_vecs</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct block_device *bdev</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int opf</code>
</li>
<li>
<b>Param reordered. </b>
<code>bio, table, max_vecs</code> ➡️ <code>bio, bdev, table, max_vecs, opf</code>
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

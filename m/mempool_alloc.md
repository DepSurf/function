# Function: <code>mempool_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8118fe80)
Location: mm/mempool.c:315
Inline: False
Direct callers:
  - fs/ext4/crypto.c:ext4_encrypt
  - fs/ext4/crypto.c:ext4_encrypted_zeroout
  - block/bio.c:bvec_alloc
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/blk-core.c:get_request
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/scsi_lib.c:scsi_sg_alloc
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_prep_fn
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff8118fe80-ffffffff8118ffed: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811a4030)
Location: mm/mempool.c:311
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_zeroout_range
  - fs/crypto/crypto.c:fscrypt_encrypt_page
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/blk-core.c:get_request
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-rq.c:dm_old_prep_fn
  - drivers/md/dm-rq.c:dm_old_prep_fn
```
**Symbols:**

```
ffffffff811a4030-ffffffff811a41b0: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811b4390)
Location: mm/mempool.c:311
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_zeroout_range
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/blk-core.c:get_request
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-rq.c:dm_old_prep_fn
  - drivers/md/dm-rq.c:dm_old_prep_fn
```
**Symbols:**

```
ffffffff811b4390-ffffffff811b4510: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811baf80)
Location: mm/mempool.c:311
Inline: False
Direct callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/blk-core.c:get_request
  - block/bounce.c:blk_queue_bounce
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff811baf80-ffffffff811bb103: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811cfb70)
Location: mm/mempool.c:312
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/blk-core.c:get_request
  - block/bounce.c:blk_queue_bounce
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff811cfb70-ffffffff811cfcf8: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811f0df0)
Location: mm/mempool.c:366
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/blk-core.c:get_request
  - block/bounce.c:blk_queue_bounce
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff811f0df0-ffffffff811f0f7a: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81202c50)
Location: mm/mempool.c:367
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bounce.c:blk_queue_bounce
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff81202c50-ffffffff81202dda: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8121a060)
Location: mm/mempool.c:375
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bounce.c:__blk_queue_bounce
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff8121a060-ffffffff8121a1db: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812279d0)
Location: mm/mempool.c:375
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bounce.c:__blk_queue_bounce
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff812279d0-ffffffff81227b4b: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81254340)
Location: mm/mempool.c:375
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bounce.c:__blk_queue_bounce
  - block/bio-integrity.c:bio_integrity_alloc
  - block/blk-crypto.c:__blk_crypto_rq_bio_prep
  - block/blk-crypto.c:__bio_crypt_clone
  - block/blk-crypto.c:bio_crypt_set_ctx
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
  - drivers/md/md.c:md_make_request
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff81254340-ffffffff812544bb: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8125ef30)
Location: mm/mempool.c:373
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bounce.c:__blk_queue_bounce
  - block/bio-integrity.c:bio_integrity_alloc
  - block/blk-crypto.c:__blk_crypto_rq_bio_prep
  - block/blk-crypto.c:__bio_crypt_clone
  - block/blk-crypto.c:bio_crypt_set_ctx
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
  - drivers/md/md.c:md_submit_bio
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff8125ef30-ffffffff8125f0a1: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81263ab0)
Location: mm/mempool.c:373
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bio-integrity.c:bio_integrity_alloc
  - block/blk-crypto.c:__blk_crypto_rq_bio_prep
  - block/blk-crypto.c:__bio_crypt_clone
  - block/blk-crypto.c:bio_crypt_set_ctx
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff81263ab0-ffffffff81263c1b: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812a0050)
Location: mm/mempool.c:375
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bio-integrity.c:bio_integrity_alloc
  - block/blk-crypto.c:__blk_crypto_rq_bio_prep
  - block/blk-crypto.c:__bio_crypt_clone
  - block/blk-crypto.c:bio_crypt_set_ctx
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff812a0050-ffffffff812a01f9: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812f7620)
Location: mm/mempool.c:374
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bio-integrity.c:bio_integrity_alloc
  - block/blk-crypto.c:__blk_crypto_rq_bio_prep
  - block/blk-crypto.c:__bio_crypt_clone
  - block/blk-crypto.c:bio_crypt_set_ctx
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff812f7620-ffffffff812f77dd: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81360f70)
Location: mm/mempool.c:380
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bio-integrity.c:bio_integrity_alloc
  - block/blk-crypto.c:__blk_crypto_rq_bio_prep
  - block/blk-crypto.c:__bio_crypt_clone
  - block/blk-crypto.c:bio_crypt_set_ctx
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff81360f70-ffffffff8136112c: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81393330)
Location: mm/mempool.c:380
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bio-integrity.c:bio_integrity_alloc
  - block/blk-crypto.c:__blk_crypto_rq_bio_prep
  - block/blk-crypto.c:__bio_crypt_clone
  - block/blk-crypto.c:bio_crypt_set_ctx
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/virtio_scsi.c:virtscsi_abort
  - drivers/scsi/virtio_scsi.c:virtscsi_device_reset
  - drivers/scsi/sd.c:sd_set_special_bvec
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff81393330-ffffffff813934ec: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff813bcfe0)
Location: mm/mempool.c:390
Inline: False
Direct callers:
  - mm/page_io.c:swap_read_folio_fs
  - mm/page_io.c:swap_writepage_fs
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bio-integrity.c:bio_integrity_alloc
  - block/blk-crypto.c:__blk_crypto_rq_bio_prep
  - block/blk-crypto.c:__bio_crypt_clone
  - block/blk-crypto.c:bio_crypt_set_ctx
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/virtio_scsi.c:virtscsi_abort
  - drivers/scsi/virtio_scsi.c:virtscsi_device_reset
  - drivers/scsi/sd.c:sd_set_special_bvec
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff813bcfe0-ffffffff813bd19c: mempool_alloc (STB_GLOBAL)
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
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffff8000102b58b0)
Location: mm/mempool.c:375
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffff8000102b58b0-ffff8000102b5a8c: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (c04e22d8)
Location: mm/mempool.c:375
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bounce.c:__blk_queue_bounce
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:btree_node_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
c04e22d8-c04e2450: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (c00000000036c220)
Location: mm/mempool.c:375
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
c00000000036c220-c00000000036c418: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffe0001d9fb4)
Location: mm/mempool.c:375
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffe0001d9fb4-ffffffe0001da0f6: mempool_alloc (STB_GLOBAL)
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
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81220020)
Location: mm/mempool.c:375
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bounce.c:__blk_queue_bounce
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff81220020-ffffffff8122019b: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812131d0)
Location: mm/mempool.c:375
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bounce.c:__blk_queue_bounce
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff812131d0-ffffffff8121334b: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8121ddc0)
Location: mm/mempool.c:375
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bounce.c:__blk_queue_bounce
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/virtio_scsi.c:virtscsi_abort
  - drivers/scsi/virtio_scsi.c:virtscsi_device_reset
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff8121ddc0-ffffffff8121df3b: mempool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *mempool_alloc(mempool_t *pool, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8122ce30)
Location: mm/mempool.c:375
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bvec_alloc
  - block/bounce.c:__blk_queue_bounce
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_alloc
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
**Symbols:**

```
ffffffff8122ce30-ffffffff8122cfa2: mempool_alloc (STB_GLOBAL)
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

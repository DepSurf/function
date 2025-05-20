# Function: <code>mempool_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81190210)
Location: mm/mempool.c:392
Inline: False
Direct callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_alloc
  - block/bio-integrity.c:bio_integrity_free
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_destroy
  - lib/btree.c:btree_remove_level
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/scsi/scsi_lib.c:scsi_sg_free
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:free_rq_clone
  - drivers/md/dm.c:free_rq_clone
  - drivers/md/dm.c:dm_requeue_original_request
  - drivers/md/dm.c:dm_softirq_done
  - drivers/md/dm.c:dm_prep_fn
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff81190210-ffffffff8119028d: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811a4220)
Location: mm/mempool.c:388
Inline: False
Direct callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/md/dm-rq.c:dm_old_prep_fn
  - drivers/md/dm-rq.c:dm_old_prep_fn
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
  - drivers/md/dm-rq.c:free_rq_clone
  - drivers/md/dm-rq.c:free_rq_clone
```
**Symbols:**

```
ffffffff811a4220-ffffffff811a429d: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811b4580)
Location: mm/mempool.c:388
Inline: False
Direct callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/blk-core.c:__blk_put_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/md/dm-rq.c:dm_old_prep_fn
  - drivers/md/dm-rq.c:dm_old_prep_fn
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
  - drivers/md/dm-rq.c:free_rq_clone
  - drivers/md/dm-rq.c:free_rq_clone
```
**Symbols:**

```
ffffffff811b4580-ffffffff811b45fd: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811bb190)
Location: mm/mempool.c:388
Inline: False
Direct callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/blk-core.c:__blk_put_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff811bb190-ffffffff811bb20e: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811cfd90)
Location: mm/mempool.c:389
Inline: False
Direct callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/blk-core.c:__blk_put_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff811cfd90-ffffffff811cfe14: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811f0cf0)
Location: mm/mempool.c:443
Inline: False
Direct callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/blk-core.c:__blk_put_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff811f0cf0-ffffffff811f0d73: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81202b50)
Location: mm/mempool.c:444
Inline: False
Direct callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:submit_flushes
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff81202b50-ffffffff81202bd3: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81219f70)
Location: mm/mempool.c:452
Inline: False
Direct callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff81219f70-ffffffff81219ff0: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812278e0)
Location: mm/mempool.c:452
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff812278e0-ffffffff81227960: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81254260)
Location: mm/mempool.c:452
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - block/blk-crypto.c:__blk_crypto_free_request
  - block/blk-crypto.c:__bio_crypt_free_ctx
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:rebalance
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/md.c:md_end_io
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff81254260-ffffffff812542e0: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8125ec30)
Location: mm/mempool.c:450
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - block/blk-crypto.c:__blk_crypto_free_request
  - block/blk-crypto.c:__bio_crypt_free_ctx
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:rebalance
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/md.c:md_end_io
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff8125ec30-ffffffff8125ecb0: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812637b0)
Location: mm/mempool.c:450
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - block/blk-crypto.c:__blk_crypto_free_request
  - block/blk-crypto.c:__bio_crypt_free_ctx
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:rebalance
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff812637b0-ffffffff81263830: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8129ff70)
Location: mm/mempool.c:452
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - block/blk-crypto.c:__blk_crypto_free_request
  - block/blk-crypto.c:__bio_crypt_free_ctx
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:rebalance
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff8129ff70-ffffffff8129fff0: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812f74f0)
Location: mm/mempool.c:451
Inline: False
Direct callers:
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:sio_write_complete
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - block/blk-crypto.c:__blk_crypto_free_request
  - block/blk-crypto.c:__bio_crypt_free_ctx
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:rebalance
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff812f74f0-ffffffff812f758c: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81360df0)
Location: mm/mempool.c:457
Inline: False
Direct callers:
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:sio_write_complete
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - block/blk-crypto.c:__blk_crypto_free_request
  - block/blk-crypto.c:__bio_crypt_free_ctx
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:rebalance
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff81360df0-ffffffff81360e8c: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff813931b0)
Location: mm/mempool.c:457
Inline: False
Direct callers:
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:sio_write_complete
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - block/blk-crypto.c:__blk_crypto_free_request
  - block/blk-crypto.c:__bio_crypt_free_ctx
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:rebalance
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff813931b0-ffffffff8139324c: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff813bce60)
Location: mm/mempool.c:504
Inline: False
Direct callers:
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:sio_write_complete
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - block/blk-crypto.c:__blk_crypto_free_request
  - block/blk-crypto.c:__bio_crypt_free_ctx
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:rebalance
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff813bce60-ffffffff813bcefc: mempool_free (STB_GLOBAL)
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
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffff8000102b57a0)
Location: mm/mempool.c:452
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - lib/sg_pool.c:sg_pool_free
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffff8000102b57a0-ffff8000102b58b0: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (c04e2190)
Location: mm/mempool.c:452
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
c04e2190-c04e2230: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (c00000000036c420)
Location: mm/mempool.c:452
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm-io.c:complete_io
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
c00000000036c420-c00000000036c51c: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffe0001d9e44)
Location: mm/mempool.c:452
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm-io.c:complete_io
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffe0001d9e44-ffffffe0001d9ed0: mempool_free (STB_GLOBAL)
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
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8121ff30)
Location: mm/mempool.c:452
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/nvme/host/pci.c:nvme_unmap_data
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff8121ff30-ffffffff8121ffb0: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812130e0)
Location: mm/mempool.c:452
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/nvme/host/pci.c:nvme_unmap_data
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff812130e0-ffffffff81213160: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8121dcd0)
Location: mm/mempool.c:452
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff8121dcd0-ffffffff8121dd50: mempool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mempool_free(void *element, mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8122cd40)
Location: mm/mempool.c:452
Inline: False
Direct callers:
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:__read_end_io
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_free
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_remove_level
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_free
  - lib/sg_pool.c:sg_pool_free
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm-io.c:dec_count
  - drivers/md/dm-kcopyd.c:run_complete_job
```
**Symbols:**

```
ffffffff8122cd40-ffffffff8122cdc0: mempool_free (STB_GLOBAL)
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

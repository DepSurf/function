# Function: <code>bio_endio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b2ea0)
Location: block/bio.c:1743
Inline: False
Direct callers:
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_verify_fn
  - drivers/block/brd.c:brd_make_request
  - drivers/block/xen-blkfront.c:split_bio_end
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff813b2ea0-ffffffff813b2eff: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f5580)
Location: block/bio.c:1742
Inline: False
Direct callers:
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_verify_fn
  - drivers/block/brd.c:brd_make_request
  - drivers/block/xen-blkfront.c:split_bio_end
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff813f5580-ffffffff813f55d9: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140efa0)
Location: block/bio.c:1797
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_verify_fn
  - drivers/block/xen-blkfront.c:split_bio_end
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff8140efa0-ffffffff8140eff9: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141d9e0)
Location: block/bio.c:1808
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_bio
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-mq.c:blk_mq_make_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff8141d9e0-ffffffff8141daf4: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814488d0)
Location: block/bio.c:1772
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff814488d0-ffffffff814489e2: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8147ba20)
Location: block/bio.c:1829
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff8147ba20-ffffffff8147bb44: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81498540)
Location: block/bio.c:1759
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-mq.c:blk_mq_make_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff81498540-ffffffff814986b0: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c63c0)
Location: block/bio.c:1796
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-mq.c:blk_mq_make_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff814c63c0-ffffffff814c654a: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814df1f0)
Location: block/bio.c:1838
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-mq.c:blk_mq_make_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff814df1f0-ffffffff814df342: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153ee20)
Location: block/bio.c:1414
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/iomap/buffered-io.c:iomap_submit_ioend
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/blk-crypto.c:__blk_crypto_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map_range
```
**Symbols:**

```
ffffffff8153ee20-ffffffff8153ef69: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155b630)
Location: block/bio.c:1417
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/iomap/buffered-io.c:iomap_submit_ioend
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:__submit_bio_noacct_mq
  - block/blk-core.c:__submit_bio_noacct_mq
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:submit_bio_checks
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/blk-crypto.c:__blk_crypto_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_submit_bio
  - drivers/md/md.c:md_submit_bio
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map_range
```
**Symbols:**

```
ffffffff8155b630-ffffffff8155b758: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81563cc0)
Location: block/bio.c:1380
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/iomap/buffered-io.c:iomap_submit_ioend
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:submit_bio_checks
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/blk-crypto.c:__blk_crypto_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_submit_bio
  - drivers/md/md.c:md_submit_bio
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff81563cc0-ffffffff81563e0e: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c7990)
Location: block/bio.c:1462
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_submit_ioend
  - block/fops.c:__blkdev_direct_IO
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:submit_bio_checks
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/blk-crypto.c:__blk_crypto_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - drivers/md/md.c:md_end_io_acct
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_submit_bio
  - drivers/md/md.c:md_submit_bio
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_io_dec_pending
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff815c7990-ffffffff815c7aea: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81672690)
Location: block/bio.c:1521
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_submit_ioend
  - block/fops.c:__blkdev_direct_IO
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:__bio_queue_enter
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_update_request
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/blk-crypto.c:__blk_crypto_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - drivers/md/md.c:md_end_io_acct
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_submit_bio
  - drivers/md/md.c:md_submit_bio
  - drivers/md/md.c:md_handle_request
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_io_complete
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff81672690-ffffffff81672811: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172e010)
Location: block/bio.c:1584
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_submit_ioend
  - block/fops.c:__blkdev_direct_IO
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:__bio_queue_enter
  - block/blk-merge.c:bio_split_rw
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_update_request
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/blk-crypto.c:__blk_crypto_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - drivers/md/md.c:md_end_io_acct
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_submit_bio
  - drivers/md/md.c:md_submit_bio
  - drivers/md/md.c:md_handle_request
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:__dm_io_complete
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff8172e010-ffffffff8172e18f: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8176a2e0)
Location: block/bio.c:1569
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_submit_ioend
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:__bio_queue_enter
  - block/blk-merge.c:bio_split_rw
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_update_request
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/blk-crypto.c:__blk_crypto_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - drivers/md/md.c:md_end_io_acct
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_submit_bio
  - drivers/md/md.c:md_submit_bio
  - drivers/md/md.c:md_handle_request
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:__dm_io_complete
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff8176a2e0-ffffffff8176a452: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ac740)
Location: block/bio.c:1576
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_submit_ioend
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:__bio_queue_enter
  - block/blk-merge.c:bio_split_rw
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_update_request
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/blk-crypto.c:__blk_crypto_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - drivers/md/md.c:md_end_clone_io
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_submit_bio
  - drivers/md/md.c:md_submit_bio
  - drivers/md/md.c:md_handle_request
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__dm_io_complete
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff817ac740-ffffffff817ac8b5: bio_endio (STB_GLOBAL)
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
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dbc18)
Location: block/bio.c:1838
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-mq.c:blk_mq_make_request
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffff8000105dbc18-ffff8000105dbdd0: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c078911c)
Location: block/bio.c:1838
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-mq.c:blk_mq_make_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
c078911c-c07892e8: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076c660)
Location: block/bio.c:1838
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-mq.c:blk_mq_make_request
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
c00000000076c660-c00000000076c8a0: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041f164)
Location: block/bio.c:1838
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-mq.c:blk_mq_make_request
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffe00041f164-ffffffe00041f2c8: bio_endio (STB_GLOBAL)
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
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d77d0)
Location: block/bio.c:1838
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-mq.c:blk_mq_make_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff814d77d0-ffffffff814d7922: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c8190)
Location: block/bio.c:1838
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-mq.c:blk_mq_make_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - drivers/nvdimm/pmem.c:pmem_make_request
  - drivers/nvdimm/btt.c:btt_make_request
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff814c8190-ffffffff814c82e2: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d3860)
Location: block/bio.c:1838
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-mq.c:blk_mq_make_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff814d3860-ffffffff814d39b2: bio_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bio_endio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ec3f0)
Location: block/bio.c:1838
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - block/bio.c:bio_chain_endio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-mq.c:blk_mq_make_request
  - block/bounce.c:bounce_end_io
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_submit_flush_data
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff814ec3f0-ffffffff814ec55e: bio_endio (STB_GLOBAL)
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

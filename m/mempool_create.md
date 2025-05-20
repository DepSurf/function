# Function: <code>mempool_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81190400)
Location: mm/mempool.c:179
Inline: False
Direct callers:
  - fs/ext4/crypto.c:ext4_init_crypto
  - block/bio.c:__bioset_create
  - block/bio.c:__bioset_create
  - block/bounce.c:init_emergency_isa_pool
  - lib/btree.c:btree_init
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/sd.c:init_sd
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff81190400-ffffffff8119041c: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811a4400)
Location: mm/mempool.c:175
Inline: False
Direct callers:
  - block/bio.c:__bioset_create
  - block/bio.c:__bioset_create
  - block/bounce.c:init_emergency_isa_pool
  - lib/btree.c:btree_init
  - drivers/scsi/sd.c:init_sd
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff811a4400-ffffffff811a441c: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811b4760)
Location: mm/mempool.c:175
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - block/bio.c:__bioset_create
  - block/bio.c:__bioset_create
  - block/bounce.c:init_emergency_isa_pool
  - lib/btree.c:btree_init
  - drivers/scsi/sd.c:init_sd
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff811b4760-ffffffff811b477c: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811bb360)
Location: mm/mempool.c:175
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - block/bio.c:bioset_create
  - block/bio.c:bioset_create
  - block/bounce.c:init_emergency_isa_pool
  - lib/btree.c:btree_init
  - drivers/scsi/sd.c:init_sd
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff811bb360-ffffffff811bb37c: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811cff90)
Location: mm/mempool.c:176
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - block/bio.c:bioset_create
  - block/bio.c:bioset_create
  - block/bounce.c:init_emergency_isa_pool
  - lib/btree.c:btree_init
  - drivers/scsi/sd.c:init_sd
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff811cff90-ffffffff811cffac: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811f11e0)
Location: mm/mempool.c:248
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff811f11e0-ffffffff811f11fc: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81203040)
Location: mm/mempool.c:249
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81203040-ffffffff8120305c: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8121a440)
Location: mm/mempool.c:253
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8121a440-ffffffff8121a45c: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81227db0)
Location: mm/mempool.c:253
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81227db0-ffffffff81227dcc: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812548f0)
Location: mm/mempool.c:253
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - block/blk-crypto.c:bio_crypt_ctx_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dmaengine_init_unmap_pool
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff812548f0-ffffffff81254971: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8125f330)
Location: mm/mempool.c:251
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - block/blk-crypto.c:bio_crypt_ctx_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dmaengine_init_unmap_pool
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff8125f330-ffffffff8125f3b1: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81263e90)
Location: mm/mempool.c:251
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - block/blk-crypto.c:bio_crypt_ctx_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff81263e90-ffffffff81263f11: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812a04c0)
Location: mm/mempool.c:253
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - block/blk-crypto.c:bio_crypt_ctx_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff812a04c0-ffffffff812a0541: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812f7af0)
Location: mm/mempool.c:252
Inline: False
Direct callers:
  - mm/page_io.c:sio_pool_init
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - block/blk-crypto.c:bio_crypt_ctx_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff812f7af0-ffffffff812f7b8c: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff813614a0)
Location: mm/mempool.c:258
Inline: False
Direct callers:
  - mm/page_io.c:sio_pool_init
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - block/blk-crypto.c:bio_crypt_ctx_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff813614a0-ffffffff8136153c: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81393860)
Location: mm/mempool.c:258
Inline: False
Direct callers:
  - mm/page_io.c:sio_pool_init
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - block/blk-crypto.c:bio_crypt_ctx_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/virtio_scsi.c:virtio_scsi_init
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff81393860-ffffffff813938fc: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff813bd530)
Location: mm/mempool.c:268
Inline: False
Direct callers:
  - mm/page_io.c:sio_pool_init
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - block/blk-crypto.c:bio_crypt_ctx_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/virtio_scsi.c:virtio_scsi_init
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff813bd530-ffffffff813bd5f9: mempool_create (STB_GLOBAL)
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
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffff8000102b53b0)
Location: mm/mempool.c:253
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffff8000102b53b0-ffff8000102b5404: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (c04e26b8)
Location: mm/mempool.c:253
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
```
**Symbols:**

```
c04e26b8-c04e26e8: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (c00000000036c8d0)
Location: mm/mempool.c:253
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
```
**Symbols:**

```
c00000000036c8d0-c00000000036c8ec: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffe0001da3dc)
Location: mm/mempool.c:253
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffe0001da3dc-ffffffe0001da426: mempool_create (STB_GLOBAL)
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
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81220400)
Location: mm/mempool.c:253
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81220400-ffffffff8122041c: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812135b0)
Location: mm/mempool.c:253
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff812135b0-ffffffff812135cc: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8121e1a0)
Location: mm/mempool.c:253
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/virtio_scsi.c:init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8121e1a0-ffffffff8121e1bc: mempool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
mempool_t *mempool_create(int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8122d210)
Location: mm/mempool.c:253
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - lib/btree.c:btree_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8122d210-ffffffff8122d22c: mempool_create (STB_GLOBAL)
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

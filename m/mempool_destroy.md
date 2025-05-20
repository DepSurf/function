# Function: <code>mempool_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8118fff0)
Location: mm/mempool.c:151
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create_node
  - fs/ext4/crypto.c:ext4_exit_crypto
  - block/bio.c:bioset_free
  - block/bio.c:bioset_free
  - block/blk-core.c:blk_exit_rl
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - lib/btree.c:btree_destroy
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:dm_free_md_mempools
  - drivers/md/dm.c:dm_free_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
```
**Symbols:**

```
ffffffff8118fff0-ffffffff81190048: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811a41b0)
Location: mm/mempool.c:147
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create_node
  - fs/crypto/crypto.c:fscrypt_destroy
  - block/bio.c:bioset_free
  - block/bio.c:bioset_free
  - block/blk-core.c:blk_exit_rl
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/dm.c:dm_free_md_mempools
  - drivers/md/dm.c:dm_free_md_mempools
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff811a41b0-ffffffff811a4208: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811b4510)
Location: mm/mempool.c:147
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create_node
  - fs/crypto/crypto.c:fscrypt_destroy
  - block/bio.c:bioset_free
  - block/bio.c:bioset_free
  - block/blk-core.c:blk_exit_rl
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/dm.c:dm_free_md_mempools
  - drivers/md/dm.c:dm_free_md_mempools
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff811b4510-ffffffff811b4568: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811bb110)
Location: mm/mempool.c:147
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create_node
  - fs/crypto/crypto.c:fscrypt_destroy
  - block/bio.c:bioset_free
  - block/bio.c:bioset_free
  - block/blk-core.c:blk_exit_rl
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff811bb110-ffffffff811bb17c: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811cfd00)
Location: mm/mempool.c:148
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create_node
  - fs/crypto/crypto.c:fscrypt_destroy
  - block/bio.c:bioset_free
  - block/bio.c:bioset_free
  - block/blk-core.c:blk_exit_rl
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff811cfd00-ffffffff811cfd72: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811f0ff0)
Location: mm/mempool.c:170
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_destroy
  - block/blk-core.c:blk_exit_rl
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff811f0ff0-ffffffff811f1013: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81202e50)
Location: mm/mempool.c:170
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_destroy
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81202e50-ffffffff81202e73: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8121a240)
Location: mm/mempool.c:170
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_destroy
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_destroy
```
**Symbols:**

```
ffffffff8121a240-ffffffff8121a265: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81227bb0)
Location: mm/mempool.c:170
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_destroy
```
**Symbols:**

```
ffffffff81227bb0-ffffffff81227bd5: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81254520)
Location: mm/mempool.c:170
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dmaengine_init_unmap_pool
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
```
**Symbols:**

```
ffffffff81254520-ffffffff81254547: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8125f130)
Location: mm/mempool.c:168
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dmaengine_init_unmap_pool
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
```
**Symbols:**

```
ffffffff8125f130-ffffffff8125f157: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81263ca0)
Location: mm/mempool.c:168
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
```
**Symbols:**

```
ffffffff81263ca0-ffffffff81263cc7: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812a0280)
Location: mm/mempool.c:170
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
```
**Symbols:**

```
ffffffff812a0280-ffffffff812a02a7: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812f7870)
Location: mm/mempool.c:169
Inline: False
Direct callers:
  - mm/page_io.c:sio_pool_init
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
```
**Symbols:**

```
ffffffff812f7870-ffffffff812f78a2: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff813611f0)
Location: mm/mempool.c:175
Inline: False
Direct callers:
  - mm/page_io.c:sio_pool_init
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:mddev_destroy_serial_pool
```
**Symbols:**

```
ffffffff813611f0-ffffffff81361222: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff813935b0)
Location: mm/mempool.c:175
Inline: False
Direct callers:
  - mm/page_io.c:sio_pool_init
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/virtio_scsi.c:virtio_scsi_fini
  - drivers/scsi/virtio_scsi.c:virtio_scsi_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:mddev_destroy_serial_pool
```
**Symbols:**

```
ffffffff813935b0-ffffffff813935e2: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff813bd260)
Location: mm/mempool.c:185
Inline: False
Direct callers:
  - mm/page_io.c:sio_pool_init
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/virtio_scsi.c:virtio_scsi_fini
  - drivers/scsi/virtio_scsi.c:virtio_scsi_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
```
**Symbols:**

```
ffffffff813bd260-ffffffff813bd292: mempool_destroy (STB_GLOBAL)
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
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffff8000102b50d8)
Location: mm/mempool.c:170
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_destroy
```
**Symbols:**

```
ffff8000102b50d8-ffff8000102b5110: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (c04e24c0)
Location: mm/mempool.c:170
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_destroy
```
**Symbols:**

```
c04e24c0-c04e24ec: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (c00000000036c1d0)
Location: mm/mempool.c:170
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_destroy
```
**Symbols:**

```
c00000000036c1d0-c00000000036c21c: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffe0001da152)
Location: mm/mempool.c:170
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_destroy
```
**Symbols:**

```
ffffffe0001da152-ffffffe0001da188: mempool_destroy (STB_GLOBAL)
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
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81220200)
Location: mm/mempool.c:170
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/nvme/host/pci.c:nvme_pci_free_ctrl
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_destroy
```
**Symbols:**

```
ffffffff81220200-ffffffff81220225: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812133b0)
Location: mm/mempool.c:170
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/nvme/host/pci.c:nvme_pci_free_ctrl
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_destroy
```
**Symbols:**

```
ffffffff812133b0-ffffffff812133d5: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8121dfa0)
Location: mm/mempool.c:170
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/virtio_scsi.c:fini
  - drivers/scsi/virtio_scsi.c:init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_destroy
```
**Symbols:**

```
ffffffff8121dfa0-ffffffff8121dfc5: mempool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mempool_destroy(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8122d010)
Location: mm/mempool.c:170
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - lib/btree.c:btree_destroy
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_destroy
```
**Symbols:**

```
ffffffff8122d010-ffffffff8122d035: mempool_destroy (STB_GLOBAL)
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

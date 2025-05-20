# Function: <code>mempool_create_slab_pool</code>

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
In block/bio.c (ffffffff813b0de3)
Location: include/linux/mempool.h:45
Inline: True
Inline callers:
  - block/bio.c:__bioset_create
  - block/bio.c:__bioset_create
```
```
In block/bio-integrity.c (ffffffff813e7500)
Location: include/linux/mempool.h:45
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81fa4695)
Location: include/linux/mempool.h:45
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81fae989)
Location: include/linux/mempool.h:45
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_queue
```
```
In drivers/scsi/sd.c (ffffffff81faebfd)
Location: include/linux/mempool.h:45
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
```
```
In drivers/md/dm.c (ffffffff816a4aba)
Location: include/linux/mempool.h:45
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-io.c (ffffffff816aac16)
Location: include/linux/mempool.h:45
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io_client_create
```
```
In drivers/md/dm-kcopyd.c (ffffffff816abee2)
Location: include/linux/mempool.h:45
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
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
In block/bio.c (ffffffff813f47d3)
Location: include/linux/mempool.h:46
Inline: True
Inline callers:
  - block/bio.c:__bioset_create
  - block/bio.c:__bioset_create
```
```
In block/bio-integrity.c (ffffffff8142d780)
Location: include/linux/mempool.h:46
Inline: True
```
```
In lib/sg_pool.c (ffffffff81fca315)
Location: include/linux/mempool.h:46
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81fd0c0b)
Location: include/linux/mempool.h:46
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81fdb640)
Location: include/linux/mempool.h:46
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
```
```
In drivers/md/dm.c (ffffffff81704c82)
Location: include/linux/mempool.h:46
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-io.c (ffffffff8170b0a6)
Location: include/linux/mempool.h:46
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io_client_create
```
```
In drivers/md/dm-kcopyd.c (ffffffff8170c402)
Location: include/linux/mempool.h:46
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
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
In block/bio.c (ffffffff8140e1c3)
Location: include/linux/mempool.h:46
Inline: True
Inline callers:
  - block/bio.c:__bioset_create
  - block/bio.c:__bioset_create
```
```
In block/bio-integrity.c (ffffffff81447560)
Location: include/linux/mempool.h:46
Inline: True
```
```
In lib/sg_pool.c (ffffffff82007330)
Location: include/linux/mempool.h:46
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff8200e583)
Location: include/linux/mempool.h:46
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff82019171)
Location: include/linux/mempool.h:46
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
```
```
In drivers/md/dm.c (ffffffff81736b32)
Location: include/linux/mempool.h:46
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-io.c (ffffffff8173cf76)
Location: include/linux/mempool.h:46
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io_client_create
```
```
In drivers/md/dm-kcopyd.c (ffffffff8173e432)
Location: include/linux/mempool.h:46
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
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
In block/bio.c (ffffffff8141be32)
Location: include/linux/mempool.h:46
Inline: True
Inline callers:
  - block/bio.c:bioset_create
  - block/bio.c:bioset_create
```
```
In block/bio-integrity.c (ffffffff81455960)
Location: include/linux/mempool.h:46
Inline: True
```
```
In lib/sg_pool.c (ffffffff820e8369)
Location: include/linux/mempool.h:46
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff820efeee)
Location: include/linux/mempool.h:46
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff820fb188)
Location: include/linux/mempool.h:46
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
```
```
In drivers/md/dm.c (ffffffff8174ff5d)
Location: include/linux/mempool.h:46
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-io.c (ffffffff81756c36)
Location: include/linux/mempool.h:46
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io_client_create
```
```
In drivers/md/dm-kcopyd.c (ffffffff81758252)
Location: include/linux/mempool.h:46
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
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
In block/bio.c (ffffffff81446ae2)
Location: include/linux/mempool.h:47
Inline: True
Inline callers:
  - block/bio.c:bioset_create
  - block/bio.c:bioset_create
```
```
In block/bio-integrity.c (ffffffff814815d0)
Location: include/linux/mempool.h:47
Inline: True
```
```
In lib/sg_pool.c (ffffffff826f115b)
Location: include/linux/mempool.h:47
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff826f96df)
Location: include/linux/mempool.h:47
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff82704832)
Location: include/linux/mempool.h:47
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
```
```
In drivers/md/dm.c (ffffffff817c213a)
Location: include/linux/mempool.h:47
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-io.c (ffffffff817c8e46)
Location: include/linux/mempool.h:47
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io_client_create
```
```
In drivers/md/dm-kcopyd.c (ffffffff817ca4c2)
Location: include/linux/mempool.h:47
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
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
In lib/sg_pool.c (ffffffff8271b06e)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (ffffffff82723b9b)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_bus_init
```
```
In drivers/scsi/sd.c (ffffffff8272e5af)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In lib/sg_pool.c (ffffffff828d2f9d)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (ffffffff828dbcaf)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_bus_init
```
```
In drivers/scsi/sd.c (ffffffff828e6f92)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In lib/sg_pool.c (ffffffff828ecfd0)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (ffffffff828f65b0)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_bus_init
```
```
In drivers/scsi/sd.c (ffffffff829017c7)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/ext4/readpage.c (ffffffff828e8690)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_init_post_read_processing
```
```
In lib/sg_pool.c (ffffffff828f6109)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (ffffffff828ff607)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_bus_init
```
```
In drivers/scsi/sd.c (ffffffff8290a9e1)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/ext4/readpage.c (ffffffff82d03220)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_init_post_read_processing
```
```
In block/blk-crypto.c (ffffffff82d091a7)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - block/blk-crypto.c:bio_crypt_ctx_init
```
```
In block/blk-crypto-fallback.c (ffffffff81582190)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In lib/sg_pool.c (ffffffff82d097fd)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (ffffffff82d168c6)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_init_unmap_pool
```
```
In drivers/scsi/sd.c (ffffffff82d20487)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/ext4/readpage.c (ffffffff82ff0523)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_init_post_read_processing
```
```
In block/blk-crypto.c (ffffffff82ff675a)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - block/blk-crypto.c:bio_crypt_ctx_init
```
```
In block/blk-crypto-fallback.c (ffffffff8159f160)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In lib/sg_pool.c (ffffffff82ff6da2)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (ffffffff8300453d)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_init_unmap_pool
```
```
In drivers/scsi/sd.c (ffffffff8300e262)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/ext4/readpage.c (ffffffff831fade4)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_init_post_read_processing
```
```
In block/blk-crypto.c (ffffffff83201442)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - block/blk-crypto.c:bio_crypt_ctx_init
```
```
In block/blk-crypto-fallback.c (ffffffff815a5f90)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In lib/sg_pool.c (ffffffff83201a87)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (ffffffff8320eff8)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_bus_init
```
```
In drivers/scsi/sd.c (ffffffff832190ff)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/ext4/readpage.c (ffffffff832e1d30)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_init_post_read_processing
```
```
In block/blk-crypto.c (ffffffff832e8a81)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - block/blk-crypto.c:bio_crypt_ctx_init
```
```
In block/blk-crypto-fallback.c (ffffffff8160eaac)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In lib/sg_pool.c (ffffffff832e913d)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (ffffffff832f7dd7)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_bus_init
```
```
In drivers/scsi/sd.c (ffffffff83302bd5)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/ext4/readpage.c (ffffffff83497f2b)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_init_post_read_processing
```
```
In block/blk-crypto.c (ffffffff834a0164)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - block/blk-crypto.c:bio_crypt_ctx_init
```
```
In block/blk-crypto-fallback.c (ffffffff816c3244)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In lib/sg_pool.c (ffffffff834a0863)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (ffffffff834b04a3)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_bus_init
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
In fs/ext4/readpage.c (ffffffff83ecd6a6)
Location: include/linux/mempool.h:72
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_init_post_read_processing
```
```
In block/blk-crypto.c (ffffffff83ed8e29)
Location: include/linux/mempool.h:72
Inline: True
Inline callers:
  - block/blk-crypto.c:bio_crypt_ctx_init
```
```
In block/blk-crypto-fallback.c (ffffffff817846c5)
Location: include/linux/mempool.h:72
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In lib/sg_pool.c (ffffffff83ed98c0)
Location: include/linux/mempool.h:72
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (ffffffff83ee9f11)
Location: include/linux/mempool.h:72
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_bus_init
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
In fs/ext4/readpage.c (ffffffff836f2746)
Location: include/linux/mempool.h:72
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_init_post_read_processing
```
```
In block/blk-crypto.c (ffffffff836fe889)
Location: include/linux/mempool.h:72
Inline: True
Inline callers:
  - block/blk-crypto.c:bio_crypt_ctx_init
```
```
In block/blk-crypto-fallback.c (ffffffff817c4a30)
Location: include/linux/mempool.h:72
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In lib/sg_pool.c (ffffffff836ff360)
Location: include/linux/mempool.h:72
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (ffffffff8370f915)
Location: include/linux/mempool.h:72
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_bus_init
```
```
In drivers/scsi/virtio_scsi.c (ffffffff8371fc44)
Location: include/linux/mempool.h:72
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtio_scsi_init
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
In fs/ext4/readpage.c (ffffffff839258e6)
Location: include/linux/mempool.h:73
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_init_post_read_processing
```
```
In block/blk-crypto.c (ffffffff83932099)
Location: include/linux/mempool.h:73
Inline: True
Inline callers:
  - block/blk-crypto.c:bio_crypt_ctx_init
```
```
In block/blk-crypto-fallback.c (ffffffff8180971f)
Location: include/linux/mempool.h:73
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In lib/sg_pool.c (ffffffff83932bb0)
Location: include/linux/mempool.h:73
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (ffffffff839430e5)
Location: include/linux/mempool.h:73
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_bus_init
```
```
In drivers/scsi/virtio_scsi.c (ffffffff83953614)
Location: include/linux/mempool.h:73
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtio_scsi_init
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
In fs/ext4/readpage.c (ffff80001146237c)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_init_post_read_processing
```
```
In lib/sg_pool.c (ffff800011470428)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (ffff80001148ec04)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_bus_init
```
```
In drivers/scsi/sd.c (ffff80001149a21c)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/ext4/readpage.c (c153a218)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_init_post_read_processing
```
```
In lib/sg_pool.c (c1549534)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (c158e674)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_bus_init
```
```
In drivers/scsi/sd.c (c159af90)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/ext4/readpage.c (c00000000138e204)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_init_post_read_processing
```
```
In lib/sg_pool.c (c0000000013a0a3c)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (c0000000013a4918)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_bus_init
```
```
In drivers/scsi/sd.c (c0000000013adf80)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/ext4/readpage.c (ffffffe00001e1f6)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_init_post_read_processing
```
```
In lib/sg_pool.c (ffffffe00002a776)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (ffffffe00002d7c2)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_bus_init
```
```
In drivers/scsi/sd.c (ffffffe000033658)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/ext4/readpage.c (ffffffff828d1544)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_init_post_read_processing
```
```
In lib/sg_pool.c (ffffffff828defbd)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (ffffffff828e6e4d)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_bus_init
```
```
In drivers/scsi/sd.c (ffffffff828f1d86)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/ext4/readpage.c (ffffffff828c9c60)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_init_post_read_processing
```
```
In lib/sg_pool.c (ffffffff828d76d9)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (ffffffff828df674)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_bus_init
```
```
In drivers/scsi/sd.c (ffffffff828e9231)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/ext4/readpage.c (ffffffff828e42c4)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_init_post_read_processing
```
```
In lib/sg_pool.c (ffffffff828f1d5c)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (ffffffff828fa92a)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_bus_init
```
```
In drivers/scsi/virtio_scsi.c (ffffffff82905c75)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:init
```
```
In drivers/scsi/sd.c (ffffffff82905ddc)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/ext4/readpage.c (ffffffff828e96da)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_init_post_read_processing
```
```
In lib/sg_pool.c (ffffffff828f715d)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_init
```
```
In drivers/dma/dmaengine.c (ffffffff8290065b)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_bus_init
```
```
In drivers/scsi/sd.c (ffffffff8290ba43)
Location: include/linux/mempool.h:67
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
```
</details>
</li>
</ul>

## Differences

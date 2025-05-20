# Function: <code>bioset_init</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814797d0)
Location: block/bio.c:1987
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init_from_src
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff814797d0-ffffffff81479a5a: bioset_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81497830)
Location: block/bio.c:1919
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init_from_src
  - block/blk-core.c:blk_alloc_queue_node
  - block/bounce.c:init_emergency_isa_pool
  - block/bounce.c:init_emergency_isa_pool
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff81497830-ffffffff81497aba: bioset_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c51d0)
Location: block/bio.c:1953
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init_from_src
  - block/blk-core.c:blk_alloc_queue_node
  - block/bounce.c:init_emergency_isa_pool
  - block/bounce.c:init_emergency_isa_pool
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff814c51d0-ffffffff814c545c: bioset_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814de0e0)
Location: block/bio.c:1995
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init_from_src
  - block/blk-core.c:blk_alloc_queue_node
  - block/bounce.c:init_emergency_isa_pool
  - block/bounce.c:init_emergency_isa_pool
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff814de0e0-ffffffff814de36c: bioset_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153eaf0)
Location: block/bio.c:1574
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_init
  - fs/iomap/buffered-io.c:iomap_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init_from_src
  - block/blk-core.c:__blk_alloc_queue
  - block/bounce.c:init_bounce_bioset
  - block/bounce.c:init_bounce_bioset
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff8153eaf0-ffffffff8153ec7a: bioset_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155b300)
Location: block/bio.c:1577
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_init
  - fs/iomap/buffered-io.c:iomap_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init_from_src
  - block/blk-core.c:blk_alloc_queue
  - block/bounce.c:init_bounce_bioset
  - block/bounce.c:init_bounce_bioset
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff8155b300-ffffffff8155b48a: bioset_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815633b0)
Location: block/bio.c:1540
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_init
  - fs/iomap/buffered-io.c:iomap_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init_from_src
  - block/blk-core.c:blk_alloc_queue
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff815633b0-ffffffff81563602: bioset_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c7ce0)
Location: block/bio.c:1625
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_init
  - block/fops.c:blkdev_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init_from_src
  - block/blk-core.c:blk_alloc_queue
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff815c7ce0-ffffffff815c7f7e: bioset_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81672a10)
Location: block/bio.c:1683
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_init
  - block/fops.c:blkdev_init
  - block/bio.c:init_bio
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_alloc_queue
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff81672a10-ffffffff81672c94: bioset_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172e4d0)
Location: block/bio.c:1746
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_init
  - block/fops.c:blkdev_init
  - block/bio.c:init_bio
  - block/genhd.c:__alloc_disk_node
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff8172e4d0-ffffffff8172e754: bioset_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8176a7a0)
Location: block/bio.c:1731
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_init
  - block/fops.c:blkdev_init
  - block/bio.c:init_bio
  - block/genhd.c:__alloc_disk_node
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff8176a7a0-ffffffff8176aa24: bioset_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817acc00)
Location: block/bio.c:1738
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_init
  - block/fops.c:blkdev_init
  - block/bio.c:init_bio
  - block/genhd.c:__alloc_disk_node
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff817acc00-ffffffff817aceb3: bioset_init (STB_GLOBAL)
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
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105da788)
Location: block/bio.c:1995
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init_from_src
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffff8000105da788-ffff8000105da9fc: bioset_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c0787af4)
Location: block/bio.c:1995
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init_from_src
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
c0787af4-c0787d84: bioset_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076abf0)
Location: block/bio.c:1995
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init_from_src
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
c00000000076abf0-c00000000076afbc: bioset_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041dd7e)
Location: block/bio.c:1995
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init_from_src
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffe00041dd7e-ffffffe00041dfdc: bioset_init (STB_GLOBAL)
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
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d66c0)
Location: block/bio.c:1995
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init_from_src
  - block/blk-core.c:blk_alloc_queue_node
  - block/bounce.c:init_emergency_isa_pool
  - block/bounce.c:init_emergency_isa_pool
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff814d66c0-ffffffff814d694c: bioset_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c7080)
Location: block/bio.c:1995
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init_from_src
  - block/blk-core.c:blk_alloc_queue_node
  - block/bounce.c:init_emergency_isa_pool
  - block/bounce.c:init_emergency_isa_pool
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff814c7080-ffffffff814c730c: bioset_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d2750)
Location: block/bio.c:1995
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init_from_src
  - block/blk-core.c:blk_alloc_queue_node
  - block/bounce.c:init_emergency_isa_pool
  - block/bounce.c:init_emergency_isa_pool
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff814d2750-ffffffff814d29dc: bioset_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bioset_init(struct bio_set *bs, unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eb270)
Location: block/bio.c:1995
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init_from_src
  - block/blk-core.c:blk_alloc_queue_node
  - block/bounce.c:init_emergency_isa_pool
  - block/bounce.c:init_emergency_isa_pool
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff814eb270-ffffffff814eb4fc: bioset_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

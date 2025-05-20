# Function: <code>bio_uninit</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141da80)
Location: block/bio.c:243
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
**Symbols:**

```
ffffffff8141c9a0-ffffffff8141c9b0: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81448970)
Location: block/bio.c:243
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
**Symbols:**

```
ffffffff81447570-ffffffff81447580: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8147bacc)
Location: block/bio.c:243
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
**Symbols:**

```
ffffffff8147a670-ffffffff8147a680: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81498603)
Location: block/bio.c:245
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
**Symbols:**

```
ffffffff814980a0-ffffffff814980e6: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c649c)
Location: block/bio.c:233
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
**Symbols:**

```
ffffffff814c5f50-ffffffff814c5f96: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814de980)
Location: block/bio.c:233
Inline: True
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
**Symbols:**

```
ffffffff814de980-ffffffff814de9e0: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153e200)
Location: block/bio.c:235
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8153e200-ffffffff8153e272: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155a520)
Location: block/bio.c:235
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff8155a520-ffffffff8155a59e: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81562d00)
Location: block/bio.c:203
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff81562d00-ffffffff81562d7e: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c6970)
Location: block/bio.c:208
Inline: False
Direct callers:
  - block/fops.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_endio
  - block/bio.c:bio_put
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff815c6970-ffffffff815c69ee: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81671830)
Location: block/bio.c:209
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/fops.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_endio
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_put
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_map_kern_endio
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff81671830-ffffffff816718b9: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172d0a0)
Location: block/bio.c:215
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/fops.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_endio
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_map_kern_endio
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff8172d0a0-ffffffff8172d129: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81769440)
Location: block/bio.c:214
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/fops.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_endio
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_copy_kern
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_map_kern_endio
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff81769440-ffffffff817694c9: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ab4c0)
Location: block/bio.c:214
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/fops.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_endio
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_copy_kern
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_map_kern_endio
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff817ab4c0-ffffffff817ab549: bio_uninit (STB_GLOBAL)
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
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105db618)
Location: block/bio.c:233
Inline: True
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
**Symbols:**

```
ffff8000105db618-ffff8000105db6c8: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (c0788ed4)
Location: block/bio.c:233
Inline: True
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
**Symbols:**

```
c0788ed4-c0788f84: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076c3b0)
Location: block/bio.c:233
Inline: True
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
**Symbols:**

```
c00000000076c3b0-c00000000076c4bc: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041e78c)
Location: block/bio.c:233
Inline: True
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
**Symbols:**

```
ffffffe00041e78c-ffffffe00041e814: bio_uninit (STB_GLOBAL)
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
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d6f60)
Location: block/bio.c:233
Inline: True
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
**Symbols:**

```
ffffffff814d6f60-ffffffff814d6fc0: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c7920)
Location: block/bio.c:233
Inline: True
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
**Symbols:**

```
ffffffff814c7920-ffffffff814c7980: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d2ff0)
Location: block/bio.c:233
Inline: True
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
**Symbols:**

```
ffffffff814d2ff0-ffffffff814d3050: bio_uninit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bio_uninit(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ec0f0)
Location: block/bio.c:233
Inline: True
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
**Symbols:**

```
ffffffff814ec0f0-ffffffff814ec167: bio_uninit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

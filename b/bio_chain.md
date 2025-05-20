# Function: <code>bio_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b07d0)
Location: block/bio.c:330
Inline: True
Direct callers:
  - block/blk-merge.c:blk_queue_split
```
**Symbols:**

```
ffffffff813b07d0-ffffffff813b0802: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f4340)
Location: block/bio.c:329
Inline: True
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-lib.c:next_bio
```
**Symbols:**

```
ffffffff813f4340-ffffffff813f4371: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140dd30)
Location: block/bio.c:333
Inline: True
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-lib.c:next_bio
```
**Symbols:**

```
ffffffff8140dd30-ffffffff8140dd61: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141b990)
Location: block/bio.c:337
Inline: True
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-lib.c:next_bio
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff8141b990-ffffffff8141b9c1: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81446590)
Location: block/bio.c:337
Inline: True
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-lib.c:next_bio
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff81446590-ffffffff814465c1: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814794c0)
Location: block/bio.c:337
Inline: True
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-lib.c:next_bio
  - block/bounce.c:blk_queue_bounce
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814794c0-ffffffff814794f1: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814974b0)
Location: block/bio.c:339
Inline: True
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-lib.c:blk_next_bio
  - block/bounce.c:blk_queue_bounce
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814974b0-ffffffff814974e1: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c4db0)
Location: block/bio.c:327
Inline: True
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-lib.c:blk_next_bio
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814c4db0-ffffffff814c4de0: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ddc50)
Location: block/bio.c:330
Inline: True
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-lib.c:blk_next_bio
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814ddc50-ffffffff814ddc81: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153d7d0)
Location: block/bio.c:334
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - block/blk-merge.c:__blk_queue_split
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/bounce.c:__blk_queue_bounce
  - block/blk-crypto-fallback.c:blk_crypto_split_bio_if_needed
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8153d7d0-ffffffff8153d801: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155a3c0)
Location: block/bio.c:338
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - block/blk-merge.c:__blk_queue_split
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/bounce.c:__blk_queue_bounce
  - block/blk-crypto-fallback.c:blk_crypto_split_bio_if_needed
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8155a3c0-ffffffff8155a3f0: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81562b80)
Location: block/bio.c:302
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - block/blk-merge.c:__blk_queue_split
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - drivers/md/md.c:md_submit_discard_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff81562b80-ffffffff81562bb0: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c6350)
Location: block/bio.c:335
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - block/blk-merge.c:__blk_queue_split
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - drivers/md/md.c:md_submit_discard_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff815c6350-ffffffff815c6380: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81673300)
Location: block/bio.c:333
Inline: True
Inline callers:
  - block/bio.c:blk_next_bio
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - block/blk-merge.c:__blk_queue_split
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - drivers/md/md.c:md_submit_discard_bio
  - drivers/md/dm.c:dm_split_and_process_bio
```
**Symbols:**

```
ffffffff81671040-ffffffff81671078: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172ee70)
Location: block/bio.c:339
Inline: True
Inline callers:
  - block/bio.c:blk_next_bio
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - block/blk-merge.c:__bio_split_to_limits
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - drivers/md/md.c:md_submit_discard_bio
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
**Symbols:**

```
ffffffff8172c7c0-ffffffff8172c7f8: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8176b0a0)
Location: block/bio.c:338
Inline: True
Inline callers:
  - block/bio.c:blk_next_bio
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - block/blk-merge.c:__bio_split_to_limits
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - drivers/md/md.c:md_submit_discard_bio
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
**Symbols:**

```
ffffffff81768b40-ffffffff81768b78: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ad530)
Location: block/bio.c:338
Inline: True
Inline callers:
  - block/bio.c:blk_next_bio
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - block/blk-merge.c:__bio_split_to_limits
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - drivers/md/md.c:md_submit_discard_bio
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
**Symbols:**

```
ffffffff817aaa30-ffffffff817aaa68: bio_chain (STB_GLOBAL)
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
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105db1d8)
Location: block/bio.c:330
Inline: True
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-lib.c:blk_next_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffff8000105db1d8-ffff8000105db258: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (c0787dc0)
Location: block/bio.c:330
Inline: True
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-lib.c:blk_next_bio
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
c0787dc0-c0787e30: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076a200)
Location: block/bio.c:330
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-lib.c:blk_next_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
c00000000076a200-c00000000076a268: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041e30c)
Location: block/bio.c:330
Inline: True
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-lib.c:blk_next_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffe00041e30c-ffffffe00041e36a: bio_chain (STB_GLOBAL)
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
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d6230)
Location: block/bio.c:330
Inline: True
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-lib.c:blk_next_bio
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814d6230-ffffffff814d6261: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c6ee0)
Location: block/bio.c:330
Inline: True
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-lib.c:blk_next_bio
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814c6ee0-ffffffff814c6f11: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d22c0)
Location: block/bio.c:330
Inline: True
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-lib.c:blk_next_bio
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814d22c0-ffffffff814d22f1: bio_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bio_chain(struct bio *bio, struct bio *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eade0)
Location: block/bio.c:330
Inline: True
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-lib.c:blk_next_bio
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814eade0-ffffffff814eae11: bio_chain (STB_GLOBAL)
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

# Function: <code>bio_segments</code>

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
In block/bio.c (ffffffff813b1c64)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - block/bio.c:bio_clone_bioset
```
```
In block/blk-merge.c (ffffffff813c0a7b)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - block/blk-merge.c:blk_recount_segments
```
```
In drivers/block/loop.c (ffffffff815710ed)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff8157848f)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_recover
  - drivers/block/xen-blkfront.c:blkif_recover
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
In block/bio.c (ffffffff813f684f)
Location: include/linux/bio.h:191
Inline: True
Inline callers:
  - block/bio.c:bio_clone_bioset
```
```
In block/blk-merge.c (ffffffff81404b8c)
Location: include/linux/bio.h:191
Inline: True
Inline callers:
  - block/blk-merge.c:blk_recount_segments
```
```
In drivers/block/loop.c (ffffffff815c5fa3)
Location: include/linux/bio.h:191
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/block/xen-blkfront.c (ffffffff815cdc3b)
Location: include/linux/bio.h:191
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
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
In block/bio.c (ffffffff814102af)
Location: include/linux/bio.h:186
Inline: True
Inline callers:
  - block/bio.c:bio_clone_bioset
```
```
In block/blk-merge.c (ffffffff8141e2fc)
Location: include/linux/bio.h:186
Inline: True
Inline callers:
  - block/blk-merge.c:blk_recount_segments
```
```
In drivers/block/loop.c (ffffffff815f4503)
Location: include/linux/bio.h:186
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/block/xen-blkfront.c (ffffffff815fa696)
Location: include/linux/bio.h:186
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
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
In block/bio.c (ffffffff8141dce9)
Location: include/linux/bio.h:202
Inline: True
Inline callers:
  - block/bio.c:bio_clone_bioset
```
```
In block/blk-merge.c (ffffffff8142bb31)
Location: include/linux/bio.h:202
Inline: True
Inline callers:
  - block/blk-merge.c:blk_recount_segments
```
```
In drivers/block/loop.c (ffffffff81608833)
Location: include/linux/bio.h:202
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
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
In block/bio.c (ffffffff81447779)
Location: include/linux/bio.h:198
Inline: True
Inline callers:
  - block/bio.c:bio_clone_bioset
```
```
In block/blk-merge.c (ffffffff81456d41)
Location: include/linux/bio.h:198
Inline: True
Inline callers:
  - block/blk-merge.c:blk_recount_segments
```
```
In drivers/block/loop.c (ffffffff81670442)
Location: include/linux/bio.h:198
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
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
In block/bio.c (ffffffff8147a875)
Location: include/linux/bio.h:207
Inline: True
Inline callers:
  - block/bio.c:bio_clone_bioset
```
```
In block/blk-merge.c (ffffffff8148a1b4)
Location: include/linux/bio.h:207
Inline: True
Inline callers:
  - block/blk-merge.c:blk_recount_segments
```
```
In drivers/block/loop.c (ffffffff816ac967)
Location: include/linux/bio.h:207
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
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
In block/blk-merge.c (ffffffff814a4aac)
Location: include/linux/bio.h:161
Inline: True
Inline callers:
  - block/blk-merge.c:blk_recount_segments
```
```
In block/bounce.c (ffffffff814be330)
Location: include/linux/bio.h:161
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In drivers/block/loop.c (ffffffff816cccc7)
Location: include/linux/bio.h:161
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814eca48)
Location: include/linux/bio.h:174
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff81505e98)
Location: include/linux/bio.h:174
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
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
In block/bounce.c (ffffffff81566665)
Location: include/linux/bio.h:182
Inline: True
```
```
In block/blk-crypto-fallback.c (ffffffff815826d5)
Location: include/linux/bio.h:182
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
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
In block/bounce.c (ffffffff815815a5)
Location: include/linux/bio.h:193
Inline: True
```
```
In block/blk-crypto-fallback.c (ffffffff8159f615)
Location: include/linux/bio.h:193
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff815a6325)
Location: include/linux/bio.h:196
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff8160ee45)
Location: include/linux/bio.h:195
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff816c36d5)
Location: include/linux/bio.h:172
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff81784b75)
Location: include/linux/bio.h:172
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff817c4ed5)
Location: include/linux/bio.h:174
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff81809bc5)
Location: include/linux/bio.h:174
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bounce.c (c07b3288)
Location: include/linux/bio.h:174
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814fe478)
Location: include/linux/bio.h:174
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814ee988)
Location: include/linux/bio.h:174
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814fa508)
Location: include/linux/bio.h:174
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff81513568)
Location: include/linux/bio.h:174
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
</details>
</li>
</ul>

## Differences

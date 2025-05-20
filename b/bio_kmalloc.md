# Function: <code>bio_kmalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b2262)
Location: include/linux/bio.h:454
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_copy_kern
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f625c)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140fc4c)
Location: include/linux/bio.h:400
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141d5cc)
Location: include/linux/bio.h:412
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8144845c)
Location: include/linux/bio.h:408
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8147b5ad)
Location: include/linux/bio.h:441
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8149971d)
Location: include/linux/bio.h:396
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (ffffffff814c787d)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (ffffffff814e096e)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
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
In fs/squashfs/block.c (ffffffff8144931a)
Location: include/linux/bio.h:411
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In block/blk-map.c (ffffffff81549fba)
Location: include/linux/bio.h:411
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_map_kern
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
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
In fs/squashfs/block.c (ffffffff81465a8a)
Location: include/linux/bio.h:422
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In block/blk-map.c (ffffffff81565d6a)
Location: include/linux/bio.h:422
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_map_kern
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bio *bio_kmalloc(gfp_t gfp_mask, short unsigned int nr_iovecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81563ab0)
Location: block/bio.c:480
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
**Symbols:**

```
ffffffff81563ab0-ffffffff81563b33: bio_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bio *bio_kmalloc(gfp_t gfp_mask, short unsigned int nr_iovecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c7400)
Location: block/bio.c:513
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
**Symbols:**

```
ffffffff815c7400-ffffffff815c74f4: bio_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bio *bio_kmalloc(short unsigned int nr_vecs, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff816713a0)
Location: block/bio.c:575
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
**Symbols:**

```
ffffffff816713a0-ffffffff816713d8: bio_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bio *bio_kmalloc(short unsigned int nr_vecs, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172cb50)
Location: block/bio.c:600
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_bio_alloc
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
**Symbols:**

```
ffffffff8172cb50-ffffffff8172cb88: bio_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bio *bio_kmalloc(short unsigned int nr_vecs, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81768ed0)
Location: block/bio.c:599
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_kern
  - block/blk-map.c:blk_rq_map_bio_alloc
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
**Symbols:**

```
ffffffff81768ed0-ffffffff81768f08: bio_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bio *bio_kmalloc(short unsigned int nr_vecs, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817aaf00)
Location: block/bio.c:599
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_kern
  - block/blk-map.c:blk_rq_map_bio_alloc
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
**Symbols:**

```
ffffffff817aaf00-ffffffff817aaf38: bio_kmalloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dd4ec)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (c078a938)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076ec50)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe0004205ee)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
</details>
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
In block/bio.c (ffffffff814d8f4e)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (ffffffff814c98fe)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (ffffffff814d4fde)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
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
In block/bio.c (ffffffff814edb8e)
Location: include/linux/bio.h:403
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>short unsigned int nr_vecs</code>
</li>
<li>
<b>Param removed. </b>
<code>short unsigned int nr_iovecs</code>
</li>
<li>
<b>Param reordered. </b>
<code>gfp_mask, nr_iovecs</code> ➡️ <code>nr_vecs, gfp_mask</code>
</li>
</ul>
</details>
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

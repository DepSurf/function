# Function: <code>bio_free_pages</code>

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
In block/bio.c (ffffffff813b201c)
Location: block/bio.c:1069
Inline: True
Inline callers:
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
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
In block/bio.c (ffffffff813f63a8)
Location: block/bio.c:1071
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140fd88)
Location: block/bio.c:1125
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
```
**Symbols:**

```
ffffffff8140da50-ffffffff8140da90: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141d6ee)
Location: block/bio.c:1141
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
```
**Symbols:**

```
ffffffff8141b690-ffffffff8141b6d2: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8144857e)
Location: block/bio.c:1146
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
```
**Symbols:**

```
ffffffff814462c0-ffffffff81446302: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8147b6c9)
Location: block/bio.c:1201
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
```
**Symbols:**

```
ffffffff81479290-ffffffff814792d2: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81499839)
Location: block/bio.c:1125
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
```
**Symbols:**

```
ffffffff81497460-ffffffff814974a2: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c5d30)
Location: block/bio.c:1183
Inline: False
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
```
**Symbols:**

```
ffffffff814c5d30-ffffffff814c5dca: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814def30)
Location: block/bio.c:1222
Inline: False
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
```
**Symbols:**

```
ffffffff814def30-ffffffff814defca: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153de80)
Location: block/bio.c:1272
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:__blk_rq_unmap_user
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff8153de80-ffffffff8153df1a: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155abc0)
Location: block/bio.c:1275
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff8155abc0-ffffffff8155ac5a: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815631c0)
Location: block/bio.c:1239
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff815631c0-ffffffff8156325a: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c6db0)
Location: block/bio.c:1321
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff815c6db0-ffffffff815c6e4a: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81671ae0)
Location: block/bio.c:1380
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff81671ae0-ffffffff81671bb2: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172d390)
Location: block/bio.c:1443
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff8172d390-ffffffff8172d462: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81769910)
Location: block/bio.c:1428
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_copy_kern
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff81769910-ffffffff817699c9: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ab120)
Location: block/bio.c:1440
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_copy_kern
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff817ab120-ffffffff817ab1d9: bio_free_pages (STB_GLOBAL)
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
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105db118)
Location: block/bio.c:1222
Inline: False
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
```
**Symbols:**

```
ffff8000105db118-ffff8000105db1d8: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c0788ca8)
Location: block/bio.c:1222
Inline: False
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
```
**Symbols:**

```
c0788ca8-c0788d4c: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076c900)
Location: block/bio.c:1222
Inline: False
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
```
**Symbols:**

```
c00000000076c900-c00000000076c9f4: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041ee58)
Location: block/bio.c:1222
Inline: False
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
```
**Symbols:**

```
ffffffe00041ee58-ffffffe00041eef4: bio_free_pages (STB_GLOBAL)
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
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d7510)
Location: block/bio.c:1222
Inline: False
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
```
**Symbols:**

```
ffffffff814d7510-ffffffff814d75aa: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c7ed0)
Location: block/bio.c:1222
Inline: False
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
```
**Symbols:**

```
ffffffff814c7ed0-ffffffff814c7f6a: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d35a0)
Location: block/bio.c:1222
Inline: False
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
```
**Symbols:**

```
ffffffff814d35a0-ffffffff814d363a: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bio_free_pages(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ebff0)
Location: block/bio.c:1222
Inline: False
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
```
**Symbols:**

```
ffffffff814ebff0-ffffffff814ec08a: bio_free_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

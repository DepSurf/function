# Function: <code>bio_iov_iter_get_pages</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140d750)
Location: block/bio.c:863
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff8140d750-ffffffff8140d862: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141b4b0)
Location: block/bio.c:879
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff8141b4b0-ffffffff8141b5cb: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814460f0)
Location: block/bio.c:882
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff814460f0-ffffffff8144620b: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81479090)
Location: block/bio.c:965
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff81479090-ffffffff814791db: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81498cc0)
Location: block/bio.c:890
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff81498cc0-ffffffff81498dfd: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c6d20)
Location: block/bio.c:944
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff814c6d20-ffffffff814c6fad: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814dfb90)
Location: block/bio.c:983
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff814dfb90-ffffffff814dfe1d: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153f840)
Location: block/bio.c:1100
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff8153f840-ffffffff8153f950: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155c060)
Location: block/bio.c:1103
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff8155c060-ffffffff8155c170: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81564580)
Location: block/bio.c:1107
Inline: True
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff81564580-ffffffff81564a07: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c8c70)
Location: block/bio.c:1201
Inline: True
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
```
**Symbols:**

```
ffffffff815c8c70-ffffffff815c8d8c: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio.c (0)
Location: block/bio.c:1272
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
```
**Symbols:**

```
ffffffff81e8b39b-ffffffff81e8b3d1: bio_iov_iter_get_pages.cold (STB_LOCAL)
ffffffff81673a20-ffffffff81673de2: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172f9d0)
Location: block/bio.c:1337
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
```
**Symbols:**

```
ffffffff8172f9d0-ffffffff8172fa3d: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio.c (0)
Location: block/bio.c:1317
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO_simple
```
**Symbols:**

```
ffffffff820f5aa0-ffffffff820f5ab5: bio_iov_iter_get_pages.cold (STB_LOCAL)
ffffffff8176bbf0-ffffffff8176bc9b: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ae090)
Location: block/bio.c:1329
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO_simple
```
**Symbols:**

```
ffffffff817ae090-ffffffff817ae126: bio_iov_iter_get_pages (STB_GLOBAL)
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
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dc720)
Location: block/bio.c:983
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffff8000105dc720-ffff8000105dc9d0: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c0789b40)
Location: block/bio.c:983
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
c0789b40-c0789e68: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076d840)
Location: block/bio.c:983
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
c00000000076d840-c00000000076dc50: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041fae6)
Location: block/bio.c:983
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffe00041fae6-ffffffe00041fcfc: bio_iov_iter_get_pages (STB_GLOBAL)
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
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d8170)
Location: block/bio.c:983
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff814d8170-ffffffff814d83fd: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c8b20)
Location: block/bio.c:983
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff814c8b20-ffffffff814c8dad: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d4200)
Location: block/bio.c:983
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff814d4200-ffffffff814d448d: bio_iov_iter_get_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bio_iov_iter_get_pages(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ecdb0)
Location: block/bio.c:983
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff814ecdb0-ffffffff814ed03d: bio_iov_iter_get_pages (STB_GLOBAL)
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

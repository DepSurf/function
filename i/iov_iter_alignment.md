# Function: <code>iov_iter_alignment</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fb400)
Location: lib/iov_iter.c:555
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff813fb400-ffffffff813fb4f9: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81442f10)
Location: lib/iov_iter.c:504
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/ext4/file.c:ext4_file_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81442f10-ffffffff814430c4: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81460620)
Location: lib/iov_iter.c:845
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_actor
  - fs/ext4/file.c:ext4_file_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81460620-ffffffff81460808: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814655f0)
Location: lib/iov_iter.c:972
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_actor
  - fs/ext4/file.c:ext4_file_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff814655f0-ffffffff814657a1: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81491470)
Location: lib/iov_iter.c:974
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_actor
  - fs/ext4/file.c:ext4_file_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81491470-ffffffff8149160c: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c6440)
Location: lib/iov_iter.c:1104
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_actor
  - fs/ext4/file.c:ext4_file_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff814c6440-ffffffff814c65d7: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814dab90)
Location: lib/iov_iter.c:1176
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_bio_actor
  - fs/ext4/file.c:ext4_file_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff814dab90-ffffffff814dad48: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81506650)
Location: lib/iov_iter.c:1190
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/ext4/file.c:ext4_file_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81506650-ffffffff81506820: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81524520)
Location: lib/iov_iter.c:1190
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/ext4/file.c:ext4_file_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81524520-ffffffff815246f0: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81588d40)
Location: lib/iov_iter.c:1224
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/ext4/file.c:ext4_dio_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81588d40-ffffffff81588f27: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a5490)
Location: lib/iov_iter.c:1231
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/ext4/file.c:ext4_dio_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff815a5490-ffffffff815a5618: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815ac4b0)
Location: lib/iov_iter.c:1358
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/ext4/file.c:ext4_dio_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff815ac4b0-ffffffff815ac8b1: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81614190)
Location: lib/iov_iter.c:1268
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81614190-ffffffff816142b9: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e0ad0)
Location: lib/iov_iter.c:1320
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/crypto/inline_crypt.c:fscrypt_dio_supported
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff816e0ad0-ffffffff816e0c11: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d0fe0)
Location: lib/iov_iter.c:1237
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff817d0fe0-ffffffff817d1120: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8180fd90)
Location: lib/iov_iter.c:924
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff8180fd90-ffffffff8180fea0: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81855a00)
Location: lib/iov_iter.c:821
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/file.c:ext4_file_read_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81855a00-ffffffff81855b1a: iov_iter_alignment (STB_GLOBAL)
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
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062eb60)
Location: lib/iov_iter.c:1190
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/ext4/file.c:ext4_file_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffff80001062eb60-ffff80001062ed90: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d5460)
Location: lib/iov_iter.c:1190
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/ext4/file.c:ext4_file_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
c07d5460-c07d56a0: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d22e0)
Location: lib/iov_iter.c:1190
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/ext4/file.c:ext4_file_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
c0000000007d22e0-c0000000007d2608: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045df66)
Location: lib/iov_iter.c:1190
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/ext4/file.c:ext4_file_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffe00045df66-ffffffe00045e118: iov_iter_alignment (STB_GLOBAL)
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
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151cb00)
Location: lib/iov_iter.c:1190
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/ext4/file.c:ext4_file_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff8151cb00-ffffffff8151ccd0: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150cdf0)
Location: lib/iov_iter.c:1190
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/ext4/file.c:ext4_file_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff8150cdf0-ffffffff8150cfc0: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81518b90)
Location: lib/iov_iter.c:1190
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/ext4/file.c:ext4_file_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81518b90-ffffffff81518d60: iov_iter_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int iov_iter_alignment(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81532380)
Location: lib/iov_iter.c:1190
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/ext4/file.c:ext4_file_write_iter
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81532380-ffffffff81532550: iov_iter_alignment (STB_GLOBAL)
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

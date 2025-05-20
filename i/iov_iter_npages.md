# Function: <code>iov_iter_npages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fb500)
Location: lib/iov_iter.c:751
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff813fb500-ffffffff813fb673: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81442cd0)
Location: lib/iov_iter.c:707
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81442cd0-ffffffff81442f0f: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81460810)
Location: lib/iov_iter.c:1182
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81460810-ffffffff81460acd: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81465980)
Location: lib/iov_iter.c:1306
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81465980-ffffffff81465bd2: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81491a60)
Location: lib/iov_iter.c:1308
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/bio.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81491a60-ffffffff81491cb0: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c69f0)
Location: lib/iov_iter.c:1438
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/bio.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff814c69f0-ffffffff814c6c4a: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814db1d0)
Location: lib/iov_iter.c:1530
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_bio_actor
  - fs/iomap.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/bio.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff814db1d0-ffffffff814db44d: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81506aa0)
Location: lib/iov_iter.c:1551
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/bio.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81506aa0-ffffffff81506d49: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81524bb0)
Location: lib/iov_iter.c:1551
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/bio.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81524bb0-ffffffff81524e59: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815893b0)
Location: lib/iov_iter.c:1586
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/blk-map.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff815893b0-ffffffff81589676: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a7b50)
Location: lib/iov_iter.c:1592
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/blk-map.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff815a7b50-ffffffff815a7dc1: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815ad380)
Location: lib/iov_iter.c:1864
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/blk-map.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff815ad380-ffffffff815ad860: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816143b0)
Location: lib/iov_iter.c:1752
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/fops.c:__blkdev_direct_IO
  - block/blk-map.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff816143b0-ffffffff81614534: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e0de0)
Location: lib/iov_iter.c:1801
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/fops.c:__blkdev_direct_IO
  - block/blk-map.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff816e0de0-ffffffff816e0fb1: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d1ff0)
Location: lib/iov_iter.c:1653
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/fops.c:__blkdev_direct_IO
  - block/blk-map.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff817d1ff0-ffffffff817d21a1: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8180ff50)
Location: lib/iov_iter.c:1281
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/blk-map.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff8180ff50-ffffffff818100d3: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81855bd0)
Location: lib/iov_iter.c:1106
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/blk-map.c:bio_map_user_iov
  - block/bio-integrity.c:bio_integrity_map_user
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81855bd0-ffffffff81855d56: iov_iter_npages (STB_GLOBAL)
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
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062efb8)
Location: lib/iov_iter.c:1551
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/bio.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffff80001062efb8-ffff80001062f294: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d5914)
Location: lib/iov_iter.c:1551
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/bio.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
c07d5914-c07d5c24: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d2950)
Location: lib/iov_iter.c:1551
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/bio.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
c0000000007d2950-c0000000007d2d9c: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045e52a)
Location: lib/iov_iter.c:1551
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/bio.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffe00045e52a-ffffffe00045e77e: iov_iter_npages (STB_GLOBAL)
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
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151d190)
Location: lib/iov_iter.c:1551
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/bio.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff8151d190-ffffffff8151d439: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150d480)
Location: lib/iov_iter.c:1551
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/bio.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff8150d480-ffffffff8150d729: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81519220)
Location: lib/iov_iter.c:1551
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/bio.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81519220-ffffffff815194c9: iov_iter_npages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iov_iter_npages(const struct iov_iter *i, int maxpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81532a10)
Location: lib/iov_iter.c:1551
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/bio.c:bio_map_user_iov
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81532a10-ffffffff81532cb9: iov_iter_npages (STB_GLOBAL)
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

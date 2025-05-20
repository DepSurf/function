# Function: <code>bio_check_pages_dirty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b2d30)
Location: block/bio.c:1645
Inline: False
Direct callers:
  - fs/direct-io.c:dio_bio_complete
```
**Symbols:**

```
ffffffff813b2d30-ffffffff813b2df8: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f64e0)
Location: block/bio.c:1644
Inline: False
Direct callers:
  - fs/direct-io.c:dio_bio_complete
```
**Symbols:**

```
ffffffff813f64e0-ffffffff813f6602: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140fec0)
Location: block/bio.c:1699
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff8140fec0-ffffffff8140ffe2: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141d840)
Location: block/bio.c:1705
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff8141d840-ffffffff8141d92f: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814486d0)
Location: block/bio.c:1669
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff814486d0-ffffffff814487e9: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8147b810)
Location: block/bio.c:1725
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff8147b810-ffffffff8147b92e: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814999f0)
Location: block/bio.c:1642
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff814999f0-ffffffff81499b20: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c7aa0)
Location: block/bio.c:1691
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff814c7aa0-ffffffff814c7bc4: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814e0ba0)
Location: block/bio.c:1733
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff814e0ba0-ffffffff814e0cc4: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153fa00)
Location: block/bio.c:1359
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff8153fa00-ffffffff8153fb16: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155c220)
Location: block/bio.c:1362
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff8155c220-ffffffff8155c336: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81564ac0)
Location: block/bio.c:1326
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff81564ac0-ffffffff81564bed: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c8e40)
Location: block/bio.c:1408
Inline: False
Direct callers:
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/fops.c:blkdev_bio_end_io
```
**Symbols:**

```
ffffffff815c8e40-ffffffff815c8f6d: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81673ed0)
Location: block/bio.c:1467
Inline: False
Direct callers:
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io
```
**Symbols:**

```
ffffffff81673ed0-ffffffff81674097: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172fb40)
Location: block/bio.c:1530
Inline: False
Direct callers:
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io
```
**Symbols:**

```
ffffffff8172fb40-ffffffff8172fd07: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8176bd90)
Location: block/bio.c:1515
Inline: False
Direct callers:
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io
```
**Symbols:**

```
ffffffff8176bd90-ffffffff8176bf35: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffffffff817ac634)
Location: block/bio.c:1522
Inline: True
Direct callers:
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io
```
**Symbols:**

```
ffffffff821d2d70-ffffffff821d2d89: bio_check_pages_dirty.cold (STB_LOCAL)
ffffffff817ac500-ffffffff817ac693: bio_check_pages_dirty (STB_GLOBAL)
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
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dd6b8)
Location: block/bio.c:1733
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffff8000105dd6b8-ffff8000105dd84c: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c078aaf4)
Location: block/bio.c:1733
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
c078aaf4-c078ac28: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076ef70)
Location: block/bio.c:1733
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
c00000000076ef70-c00000000076f120: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe000420790)
Location: block/bio.c:1733
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffe000420790-ffffffe0004208a8: bio_check_pages_dirty (STB_GLOBAL)
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
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d9180)
Location: block/bio.c:1733
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff814d9180-ffffffff814d92a4: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c9b30)
Location: block/bio.c:1733
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff814c9b30-ffffffff814c9c54: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d5210)
Location: block/bio.c:1733
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff814d5210-ffffffff814d5334: bio_check_pages_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eddc0)
Location: block/bio.c:1733
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff814eddc0-ffffffff814edee4: bio_check_pages_dirty (STB_GLOBAL)
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

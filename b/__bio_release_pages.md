# Function: <code>__bio_release_pages</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bio_release_pages(struct bio *bio, bool mark_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81672180)
Location: block/bio.c:1120
Inline: False
Direct callers:
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff81672180-ffffffff816722e5: __bio_release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bio_release_pages(struct bio *bio, bool mark_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172dac0)
Location: block/bio.c:1172
Inline: False
Direct callers:
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff8172dac0-ffffffff8172dc25: __bio_release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bio_release_pages(struct bio *bio, bool mark_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81769830)
Location: block/bio.c:1148
Inline: False
Direct callers:
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff81769830-ffffffff817698f7: __bio_release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __bio_release_pages(struct bio *bio, bool mark_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio.c (0)
Location: block/bio.c:1149
Inline: False
Direct callers:
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_dirty_fn
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff821d2ceb-ffffffff821d2d0b: __bio_release_pages.cold (STB_LOCAL)
ffffffff817ab7c0-ffffffff817ab94e: __bio_release_pages (STB_GLOBAL)
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
In <code>armhf</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

# Function: <code>bio_release_pages</code>

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
In block/bio.c (ffffffff813b2e49)
Location: block/bio.c:1592
Inline: True
Inline callers:
  - block/bio.c:bio_dirty_fn
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
In block/bio.c (ffffffff813f665f)
Location: block/bio.c:1591
Inline: True
Inline callers:
  - block/bio.c:bio_dirty_fn
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
In block/bio.c (ffffffff8141003f)
Location: block/bio.c:1646
Inline: True
Inline callers:
  - block/bio.c:bio_dirty_fn
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
In block/bio.c (ffffffff8141d97e)
Location: block/bio.c:1652
Inline: True
Inline callers:
  - block/bio.c:bio_dirty_fn
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
In block/bio.c (ffffffff8144883e)
Location: block/bio.c:1616
Inline: True
Inline callers:
  - block/bio.c:bio_dirty_fn
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
In block/bio.c (ffffffff8147b98c)
Location: block/bio.c:1672
Inline: True
Inline callers:
  - block/bio.c:bio_dirty_fn
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
In block/bio.c (ffffffff81499962)
Location: block/bio.c:1595
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_release_pages(struct bio *bio, bool mark_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffffffff814c7ab6)
Location: block/bio.c:836
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff814c5dd0-ffffffff814c5eff: bio_release_pages.part.0 (STB_LOCAL)
ffffffff814c6d00-ffffffff814c6d1b: bio_release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_release_pages(struct bio *bio, bool mark_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffffffff814e0bb6)
Location: block/bio.c:875
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff814defd0-ffffffff814df0ff: bio_release_pages.part.0 (STB_LOCAL)
ffffffff814dfb70-ffffffff814dfb8b: bio_release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_release_pages(struct bio *bio, bool mark_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffffffff8153fa18)
Location: block/bio.c:947
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/blk-map.c:__blk_rq_unmap_user
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff8153e2e0-ffffffff8153e3e1: bio_release_pages.part.0 (STB_LOCAL)
ffffffff8153e3f0-ffffffff8153e40b: bio_release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_release_pages(struct bio *bio, bool mark_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffffffff8155c238)
Location: block/bio.c:947
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff8155b1e0-ffffffff8155b2de: bio_release_pages.part.0 (STB_LOCAL)
ffffffff8155b2e0-ffffffff8155b2fb: bio_release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_release_pages(struct bio *bio, bool mark_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffffffff81564ad8)
Location: block/bio.c:936
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff81563930-ffffffff81563a29: bio_release_pages.part.0 (STB_LOCAL)
ffffffff81563a30-ffffffff81563a4b: bio_release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_release_pages(struct bio *bio, bool mark_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffffffff815c8e58)
Location: block/bio.c:1019
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
Direct callers:
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:__blkdev_direct_IO_simple
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff815c72e0-ffffffff815c73d6: bio_release_pages.part.0 (STB_LOCAL)
ffffffff815c73e0-ffffffff815c73fb: bio_release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81448d7d)
Location: include/linux/bio.h:485
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/iomap/direct-io.c (ffffffff8148d985)
Location: include/linux/bio.h:485
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In block/fops.c (ffffffff8166fcc1)
Location: include/linux/bio.h:485
Inline: True
Inline callers:
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/bio.c (ffffffff81673f07)
Location: include/linux/bio.h:485
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
```
```
In block/blk-map.c (ffffffff8167ebcd)
Location: include/linux/bio.h:485
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_map_user_iov
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff814d71aa)
Location: include/linux/bio.h:485
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/iomap/direct-io.c (ffffffff81521145)
Location: include/linux/bio.h:485
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In block/fops.c (ffffffff8172b191)
Location: include/linux/bio.h:485
Inline: True
Inline callers:
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/bio.c (ffffffff8172fb77)
Location: include/linux/bio.h:485
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
```
```
In block/blk-map.c (ffffffff8173bb54)
Location: include/linux/bio.h:485
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_map_user_iov
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff815101c5)
Location: include/linux/bio.h:493
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/iomap/direct-io.c (ffffffff81559178)
Location: include/linux/bio.h:493
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In block/fops.c (ffffffff817679d8)
Location: include/linux/bio.h:493
Inline: True
Inline callers:
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/bio.c (ffffffff8176bda5)
Location: include/linux/bio.h:493
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
```
```
In block/blk-map.c (ffffffff81778294)
Location: include/linux/bio.h:493
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_map_user_iov
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81544675)
Location: include/linux/bio.h:508
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/iomap/direct-io.c (ffffffff8158f8c0)
Location: include/linux/bio.h:508
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In block/fops.c (ffffffff817a9638)
Location: include/linux/bio.h:508
Inline: True
Inline callers:
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/bio.c (ffffffff817ac701)
Location: include/linux/bio.h:508
Inline: True
Inline callers:
  - block/bio.c:bio_dirty_fn
```
```
In block/blk-map.c (ffffffff817ba674)
Location: include/linux/bio.h:508
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_map_user_iov
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_release_pages(struct bio *bio, bool mark_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffff8000105dd6d8)
Location: block/bio.c:875
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffff8000105db258-ffff8000105db398: bio_release_pages.part.0 (STB_LOCAL)
ffff8000105dc6e0-ffff8000105dc71c: bio_release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_release_pages(struct bio *bio, bool mark_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (c078ab18)
Location: block/bio.c:875
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
c0788d4c-c0788e44: bio_release_pages.part.0 (STB_LOCAL)
c0789b18-c0789b40: bio_release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_release_pages(struct bio *bio, bool mark_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (c00000000076ef98)
Location: block/bio.c:875
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
c00000000076ca40-c00000000076cc60: bio_release_pages.part.0 (STB_LOCAL)
c00000000076d820-c00000000076d840: bio_release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_release_pages(struct bio *bio, bool mark_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffffffe0004207b0)
Location: block/bio.c:875
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffffffe00041eef4-ffffffe00041efe0: bio_release_pages.part.0 (STB_LOCAL)
ffffffe00041faac-ffffffe00041fae6: bio_release_pages (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_release_pages(struct bio *bio, bool mark_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffffffff814d9196)
Location: block/bio.c:875
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff814d75b0-ffffffff814d76df: bio_release_pages.part.0 (STB_LOCAL)
ffffffff814d8150-ffffffff814d816b: bio_release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_release_pages(struct bio *bio, bool mark_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffffffff814c9b46)
Location: block/bio.c:875
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff814c7f70-ffffffff814c809f: bio_release_pages.part.0 (STB_LOCAL)
ffffffff814c8b00-ffffffff814c8b1b: bio_release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_release_pages(struct bio *bio, bool mark_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffffffff814d5226)
Location: block/bio.c:875
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff814d3640-ffffffff814d376f: bio_release_pages.part.0 (STB_LOCAL)
ffffffff814d41e0-ffffffff814d41fb: bio_release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bio_release_pages(struct bio *bio, bool mark_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffffffff814eddd6)
Location: block/bio.c:875
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
Direct callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_bio_complete
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff814ec1d0-ffffffff814ec2ff: bio_release_pages.part.0 (STB_LOCAL)
ffffffff814ecd90-ffffffff814ecdab: bio_release_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

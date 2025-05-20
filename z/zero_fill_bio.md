# Function: <code>zero_fill_bio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void zero_fill_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b10f0)
Location: block/bio.c:515
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_rw_aio_complete
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff813b10f0-ffffffff813b121e: zero_fill_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void zero_fill_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f4ac0)
Location: block/bio.c:514
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_complete
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff813f4ac0-ffffffff813f4be4: zero_fill_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void zero_fill_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140e4b0)
Location: block/bio.c:518
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_complete
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff8140e4b0-ffffffff8140e5db: zero_fill_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void zero_fill_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141c000)
Location: block/bio.c:532
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff8141c000-ffffffff8141c117: zero_fill_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void zero_fill_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81446bd0)
Location: block/bio.c:532
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff81446bd0-ffffffff81446ce7: zero_fill_bio (STB_GLOBAL)
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
In drivers/block/loop.c (ffffffff816ad6ed)
Location: include/linux/bio.h:529
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
```
```
In drivers/md/dm-io.c (ffffffff81811e1e)
Location: include/linux/bio.h:529
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
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
In block/bio.c (ffffffff81499291)
Location: include/linux/bio.h:478
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In drivers/block/loop.c (ffffffff816cda40)
Location: include/linux/bio.h:478
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
```
```
In drivers/md/dm-io.c (ffffffff8183ddae)
Location: include/linux/bio.h:478
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c74dd)
Location: include/linux/bio.h:474
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In drivers/block/loop.c (ffffffff81709cad)
Location: include/linux/bio.h:474
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
```
```
In drivers/md/dm-io.c (ffffffff81880a75)
Location: include/linux/bio.h:474
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814e0375)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In drivers/block/loop.c (ffffffff8172dfb1)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
```
```
In drivers/md/dm-io.c (ffffffff818b2935)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
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
In block/blk-map.c (ffffffff8154a4ce)
Location: include/linux/bio.h:465
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
```
```
In drivers/block/loop.c (ffffffff817e75c7)
Location: include/linux/bio.h:465
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_read_simple
```
```
In drivers/md/dm-io.c (ffffffff81982fc5)
Location: include/linux/bio.h:465
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
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
In block/blk-map.c (ffffffff815662a5)
Location: include/linux/bio.h:476
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
```
```
In drivers/block/loop.c (ffffffff817fc1f7)
Location: include/linux/bio.h:476
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_read_simple
```
```
In drivers/md/dm-io.c (ffffffff819870e5)
Location: include/linux/bio.h:476
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void zero_fill_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81563260)
Location: block/bio.c:496
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_read_transfer
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff81563260-ffffffff815633ac: zero_fill_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void zero_fill_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c6e50)
Location: block/bio.c:529
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_read_transfer
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff815c6e50-ffffffff815c6f9c: zero_fill_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void zero_fill_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81671d60)
Location: block/bio.c:585
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/loop.c:lo_read_simple
  - drivers/block/loop.c:lo_read_simple
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff81671d60-ffffffff81671ead: zero_fill_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void zero_fill_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172d950)
Location: block/bio.c:610
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/loop.c:lo_read_simple
  - drivers/block/loop.c:lo_read_simple
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff8172d950-ffffffff8172daae: zero_fill_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void zero_fill_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81769cf0)
Location: block/bio.c:609
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/loop.c:lo_read_simple
  - drivers/block/loop.c:lo_read_simple
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff81769cf0-ffffffff81769e66: zero_fill_bio (STB_GLOBAL)
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
In block/blk-map.c (ffffffff817ba351)
Location: include/linux/bio.h:503
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
```
```
In drivers/block/loop.c (ffffffff81bcedab)
Location: include/linux/bio.h:503
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/loop.c:lo_read_simple
```
```
In drivers/md/dm-io.c (ffffffff81e3abe1)
Location: include/linux/bio.h:503
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dced4)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In drivers/block/loop.c (ffff800010923518)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
```
```
In drivers/md/dm-io.c (ffff800010b0a120)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (c078a38c)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In drivers/block/loop.c (c0a09430)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
```
```
In drivers/md/dm-io.c (c0be85a8)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076e3a8)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In drivers/block/loop.c (c0000000009c9bd0)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
```
```
In drivers/md/dm-io.c (c000000000bfba70)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00042014e)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In drivers/block/loop.c (ffffffe0005a2684)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
```
```
In drivers/md/dm-io.c (ffffffe0006f810c)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d8955)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In drivers/block/loop.c (ffffffff816f3d91)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
```
```
In drivers/md/dm-io.c (ffffffff818587b5)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c9305)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In drivers/block/loop.c (ffffffff816cde91)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
```
```
In drivers/md/dm-io.c (ffffffff8181fdc5)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d49e5)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In drivers/block/loop.c (ffffffff81721471)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
```
```
In drivers/md/dm-io.c (ffffffff818a7de5)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ed595)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In drivers/block/loop.c (ffffffff8173c836)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
```
```
In drivers/md/dm-io.c (ffffffff818c4025)
Location: include/linux/bio.h:475
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
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
</ul>

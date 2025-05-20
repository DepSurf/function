# Function: <code>zero_fill_bio_iter</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void zero_fill_bio_iter(struct bio *bio, struct bvec_iter start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81479d50)
Location: block/bio.c:533
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff81479d50-ffffffff81479e67: zero_fill_bio_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void zero_fill_bio_iter(struct bio *bio, struct bvec_iter start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81497b60)
Location: block/bio.c:535
Inline: False
Direct callers:
  - block/bio.c:bio_copy_user_iov
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff81497b60-ffffffff81497c77: zero_fill_bio_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void zero_fill_bio_iter(struct bio *bio, struct bvec_iter start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c54f0)
Location: block/bio.c:523
Inline: False
Direct callers:
  - block/bio.c:bio_copy_user_iov
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff814c54f0-ffffffff814c5698: zero_fill_bio_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void zero_fill_bio_iter(struct bio *bio, struct bvec_iter start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814de780)
Location: block/bio.c:526
Inline: False
Direct callers:
  - block/bio.c:bio_copy_user_iov
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff814de780-ffffffff814de928: zero_fill_bio_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void zero_fill_bio_iter(struct bio *bio, struct bvec_iter start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153e070)
Location: block/bio.c:530
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_read_simple
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff8153e070-ffffffff8153e1f9: zero_fill_bio_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void zero_fill_bio_iter(struct bio *bio, struct bvec_iter start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155acc0)
Location: block/bio.c:532
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_read_simple
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff8155acc0-ffffffff8155ae0c: zero_fill_bio_iter (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void zero_fill_bio_iter(struct bio *bio, struct bvec_iter start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817abea0)
Location: block/bio.c:609
Inline: False
Direct callers:
  - block/blk-map.c:bio_copy_user_iov
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/loop.c:lo_read_simple
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff817abea0-ffffffff817ac016: zero_fill_bio_iter (STB_GLOBAL)
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
void zero_fill_bio_iter(struct bio *bio, struct bvec_iter start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dab08)
Location: block/bio.c:526
Inline: False
Direct callers:
  - block/bio.c:bio_copy_user_iov
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffff8000105dab08-ffff8000105dac88: zero_fill_bio_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void zero_fill_bio_iter(struct bio *bio, struct bvec_iter start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c07885f0)
Location: block/bio.c:526
Inline: False
Direct callers:
  - block/bio.c:bio_copy_user_iov
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
c07885f0-c078879c: zero_fill_bio_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void zero_fill_bio_iter(struct bio *bio, struct bvec_iter start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076ba20)
Location: block/bio.c:526
Inline: False
Direct callers:
  - block/bio.c:bio_copy_user_iov
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
c00000000076ba20-c00000000076bc74: zero_fill_bio_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void zero_fill_bio_iter(struct bio *bio, struct bvec_iter start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041e864)
Location: block/bio.c:526
Inline: False
Direct callers:
  - block/bio.c:bio_copy_user_iov
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffe00041e864-ffffffe00041ea06: zero_fill_bio_iter (STB_GLOBAL)
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
void zero_fill_bio_iter(struct bio *bio, struct bvec_iter start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d6d60)
Location: block/bio.c:526
Inline: False
Direct callers:
  - block/bio.c:bio_copy_user_iov
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff814d6d60-ffffffff814d6f08: zero_fill_bio_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void zero_fill_bio_iter(struct bio *bio, struct bvec_iter start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c7720)
Location: block/bio.c:526
Inline: False
Direct callers:
  - block/bio.c:bio_copy_user_iov
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff814c7720-ffffffff814c78c8: zero_fill_bio_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void zero_fill_bio_iter(struct bio *bio, struct bvec_iter start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d2df0)
Location: block/bio.c:526
Inline: False
Direct callers:
  - block/bio.c:bio_copy_user_iov
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff814d2df0-ffffffff814d2f98: zero_fill_bio_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void zero_fill_bio_iter(struct bio *bio, struct bvec_iter start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eb910)
Location: block/bio.c:526
Inline: False
Direct callers:
  - block/bio.c:bio_copy_user_iov
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm-io.c:endio
```
**Symbols:**

```
ffffffff814eb910-ffffffff814ebab8: zero_fill_bio_iter (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

# Function: <code>ll_back_merge_fn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff813c0bb0)
Location: block/blk-merge.c:495
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
```
**Symbols:**

```
ffffffff813c0bb0-ffffffff813c0ec5: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81404ce0)
Location: block/blk-merge.c:521
Inline: False
```
**Symbols:**

```
ffffffff81404ce0-ffffffff81405052: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8141e9f0)
Location: block/blk-merge.c:516
Inline: False
```
**Symbols:**

```
ffffffff8141e9f0-ffffffff8141ee95: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8142c780)
Location: block/blk-merge.c:499
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
```
**Symbols:**

```
ffffffff8142c780-ffffffff8142cce7: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81457990)
Location: block/blk-merge.c:500
Inline: False
```
**Symbols:**

```
ffffffff81457990-ffffffff81457ef7: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8148aeb0)
Location: block/blk-merge.c:509
Inline: False
```
**Symbols:**

```
ffffffff8148aeb0-ffffffff8148b3df: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814a4ba0)
Location: block/blk-merge.c:551
Inline: False
```
**Symbols:**

```
ffffffff814a4ba0-ffffffff814a50bf: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d2c70)
Location: block/blk-merge.c:519
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
```
**Symbols:**

```
ffffffff814d2c70-ffffffff814d319e: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814ebfa0)
Location: block/blk-merge.c:572
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
```
**Symbols:**

```
ffffffff814ebfa0-ffffffff814ec4ce: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8154c240)
Location: block/blk-merge.c:565
Inline: False
Direct callers:
  - block/blk-core.c:bio_attempt_back_merge
  - block/blk-map.c:blk_rq_append_bio
```
**Symbols:**

```
ffffffff8154c240-ffffffff8154c497: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ll_back_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81568580)
Location: block/blk-merge.c:581
Inline: True
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-merge.c:bio_attempt_back_merge
```
**Symbols:**

```
ffffffff81568580-ffffffff81568a3d: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ll_back_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81570370)
Location: block/blk-merge.c:584
Inline: True
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-merge.c:bio_attempt_back_merge
```
**Symbols:**

```
ffffffff81570370-ffffffff815705bb: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ll_back_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d4a10)
Location: block/blk-merge.c:586
Inline: True
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-merge.c:bio_attempt_back_merge
```
**Symbols:**

```
ffffffff815d4a10-ffffffff815d4c6e: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81680880)
Location: block/blk-merge.c:604
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-merge.c:bio_attempt_back_merge
```
**Symbols:**

```
ffffffff81680880-ffffffff81680aa4: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173dd40)
Location: block/blk-merge.c:642
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-merge.c:bio_attempt_back_merge
```
**Symbols:**

```
ffffffff8173dd40-ffffffff8173df51: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8177a290)
Location: block/blk-merge.c:636
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-merge.c:bio_attempt_back_merge
```
**Symbols:**

```
ffffffff8177a290-ffffffff8177a4a1: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bc670)
Location: block/blk-merge.c:632
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-merge.c:bio_attempt_back_merge
```
**Symbols:**

```
ffffffff817bc670-ffffffff817bc883: ll_back_merge_fn (STB_GLOBAL)
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
int ll_back_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffff8000105eaa40)
Location: block/blk-merge.c:572
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
```
**Symbols:**

```
ffff8000105eaa40-ffff8000105eaf30: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c0797024)
Location: block/blk-merge.c:572
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
```
**Symbols:**

```
c0797024-c07974a8: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c00000000077fce0)
Location: block/blk-merge.c:572
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
```
**Symbols:**

```
c00000000077fce0-c00000000078025c: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffe00042ace2)
Location: block/blk-merge.c:572
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
```
**Symbols:**

```
ffffffe00042ace2-ffffffe00042b04a: ll_back_merge_fn (STB_GLOBAL)
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
int ll_back_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e4580)
Location: block/blk-merge.c:572
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
```
**Symbols:**

```
ffffffff814e4580-ffffffff814e4aae: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d4e60)
Location: block/blk-merge.c:572
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
```
**Symbols:**

```
ffffffff814d4e60-ffffffff814d5272: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e0610)
Location: block/blk-merge.c:572
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
```
**Symbols:**

```
ffffffff814e0610-ffffffff814e0b3e: ll_back_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ll_back_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814f9490)
Location: block/blk-merge.c:572
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
```
**Symbols:**

```
ffffffff814f9490-ffffffff814f99be: ll_back_merge_fn (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int nr_segs</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, req, bio</code> ➡️ <code>req, bio, nr_segs</code>
</li>
</ul>
</details>
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

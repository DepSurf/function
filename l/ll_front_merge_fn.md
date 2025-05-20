# Function: <code>ll_front_merge_fn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ll_front_merge_fn(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff813c0ed0)
Location: block/blk-merge.c:518
Inline: False
```
**Symbols:**

```
ffffffff813c0ed0-ffffffff813c11e5: ll_front_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ll_front_merge_fn(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81405060)
Location: block/blk-merge.c:544
Inline: False
```
**Symbols:**

```
ffffffff81405060-ffffffff814053ce: ll_front_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ll_front_merge_fn(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8141eea0)
Location: block/blk-merge.c:537
Inline: False
```
**Symbols:**

```
ffffffff8141eea0-ffffffff8141f341: ll_front_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ll_front_merge_fn(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8142ccf0)
Location: block/blk-merge.c:520
Inline: False
```
**Symbols:**

```
ffffffff8142ccf0-ffffffff8142d206: ll_front_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ll_front_merge_fn(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81457f00)
Location: block/blk-merge.c:521
Inline: False
```
**Symbols:**

```
ffffffff81457f00-ffffffff81458416: ll_front_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ll_front_merge_fn(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8148b3e0)
Location: block/blk-merge.c:530
Inline: False
```
**Symbols:**

```
ffffffff8148b3e0-ffffffff8148b8c6: ll_front_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ll_front_merge_fn(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814a50c0)
Location: block/blk-merge.c:572
Inline: False
```
**Symbols:**

```
ffffffff814a50c0-ffffffff814a5589: ll_front_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ll_front_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d31a0)
Location: block/blk-merge.c:535
Inline: False
```
**Symbols:**

```
ffffffff814d31a0-ffffffff814d3687: ll_front_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ll_front_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814ec4d0)
Location: block/blk-merge.c:588
Inline: False
```
**Symbols:**

```
ffffffff814ec4d0-ffffffff814ec9b7: ll_front_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ll_front_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8154c4a0)
Location: block/blk-merge.c:583
Inline: False
Direct callers:
  - block/blk-core.c:bio_attempt_front_merge
```
**Symbols:**

```
ffffffff8154c4a0-ffffffff8154c9b2: ll_front_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ll_front_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81567d60)
Location: block/blk-merge.c:599
Inline: False
Direct callers:
  - block/blk-merge.c:bio_attempt_front_merge
```
**Symbols:**

```
ffffffff81567d60-ffffffff815681c2: ll_front_merge_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81570c49)
Location: block/blk-merge.c:602
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d52f9)
Location: block/blk-merge.c:604
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff816810e7)
Location: block/blk-merge.c:622
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173e66e)
Location: block/blk-merge.c:660
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8177abce)
Location: block/blk-merge.c:654
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bcfae)
Location: block/blk-merge.c:650
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
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
int ll_front_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffff8000105eaf30)
Location: block/blk-merge.c:588
Inline: False
```
**Symbols:**

```
ffff8000105eaf30-ffff8000105eb3a8: ll_front_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ll_front_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c07974a8)
Location: block/blk-merge.c:588
Inline: False
```
**Symbols:**

```
c07974a8-c0797904: ll_front_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ll_front_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c000000000780260)
Location: block/blk-merge.c:588
Inline: False
```
**Symbols:**

```
c000000000780260-c00000000078079c: ll_front_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ll_front_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffe00042b04a)
Location: block/blk-merge.c:588
Inline: False
```
**Symbols:**

```
ffffffe00042b04a-ffffffe00042b382: ll_front_merge_fn (STB_GLOBAL)
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
int ll_front_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e4ab0)
Location: block/blk-merge.c:588
Inline: False
```
**Symbols:**

```
ffffffff814e4ab0-ffffffff814e4f97: ll_front_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ll_front_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d5280)
Location: block/blk-merge.c:588
Inline: False
```
**Symbols:**

```
ffffffff814d5280-ffffffff814d565b: ll_front_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ll_front_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e0b40)
Location: block/blk-merge.c:588
Inline: False
```
**Symbols:**

```
ffffffff814e0b40-ffffffff814e1027: ll_front_merge_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ll_front_merge_fn(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814f99c0)
Location: block/blk-merge.c:588
Inline: False
```
**Symbols:**

```
ffffffff814f99c0-ffffffff814f9ea7: ll_front_merge_fn (STB_GLOBAL)
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

# Function: <code>blk_bio_segment_split</code>

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
In block/blk-merge.c (ffffffff813c05e3)
Location: block/blk-merge.c:83
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
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
In block/blk-merge.c (ffffffff81404570)
Location: block/blk-merge.c:85
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
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
In block/blk-merge.c (ffffffff8141dccf)
Location: block/blk-merge.c:85
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
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
In block/blk-merge.c (ffffffff8142c2d0)
Location: block/blk-merge.c:99
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
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
In block/blk-merge.c (ffffffff814574e3)
Location: block/blk-merge.c:100
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
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
In block/blk-merge.c (ffffffff8148a441)
Location: block/blk-merge.c:100
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
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
In block/blk-merge.c (ffffffff814a3fa5)
Location: block/blk-merge.c:164
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d2608)
Location: block/blk-merge.c:197
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814eb987)
Location: block/blk-merge.c:240
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bio *blk_bio_segment_split(struct request_queue *q, struct bio *bio, struct bio_set *bs, unsigned int *segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8154b660)
Location: block/blk-merge.c:244
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
```
**Symbols:**

```
ffffffff8154b660-ffffffff8154b908: blk_bio_segment_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bio *blk_bio_segment_split(struct request_queue *q, struct bio *bio, struct bio_set *bs, unsigned int *segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81566fa0)
Location: block/blk-merge.c:245
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
```
**Symbols:**

```
ffffffff81566fa0-ffffffff8156723a: blk_bio_segment_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bio *blk_bio_segment_split(struct request_queue *q, struct bio *bio, struct bio_set *bs, unsigned int *segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8156f2c0)
Location: block/blk-merge.c:245
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
```
**Symbols:**

```
ffffffff8156f2c0-ffffffff8156f57b: blk_bio_segment_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bio *blk_bio_segment_split(struct request_queue *q, struct bio *bio, struct bio_set *bs, unsigned int *segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d3960)
Location: block/blk-merge.c:245
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
```
**Symbols:**

```
ffffffff815d3960-ffffffff815d3c22: blk_bio_segment_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bio *blk_bio_segment_split(struct request_queue *q, struct bio *bio, struct bio_set *bs, unsigned int *segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8167f770)
Location: block/blk-merge.c:265
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
```
**Symbols:**

```
ffffffff8167f770-ffffffff8167fa54: blk_bio_segment_split (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffff8000105ea3a8)
Location: block/blk-merge.c:240
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c0796a2c)
Location: block/blk-merge.c:240
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c00000000077f380)
Location: block/blk-merge.c:240
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffe00042a764)
Location: block/blk-merge.c:240
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e3f67)
Location: block/blk-merge.c:240
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d4847)
Location: block/blk-merge.c:240
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814dfff7)
Location: block/blk-merge.c:240
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814f8e57)
Location: block/blk-merge.c:240
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>

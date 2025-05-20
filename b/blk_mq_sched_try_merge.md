# Function: <code>blk_mq_sched_try_merge</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81435260)
Location: block/blk-mq-sched.c:151
Inline: False
```
**Symbols:**

```
ffffffff81435260-ffffffff81435394: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81461090)
Location: block/blk-mq-sched.c:239
Inline: False
```
**Symbols:**

```
ffffffff81461090-ffffffff814611ca: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81494960)
Location: block/blk-mq-sched.c:238
Inline: False
```
**Symbols:**

```
ffffffff81494960-ffffffff81494aca: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814aea90)
Location: block/blk-mq-sched.c:225
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff814aea90-ffffffff814aec03: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814dcd30)
Location: block/blk-mq-sched.c:226
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff814dcd30-ffffffff814dceb3: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814f61a0)
Location: block/blk-mq-sched.c:226
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff814f61a0-ffffffff814f6323: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81556cc0)
Location: block/blk-mq-sched.c:291
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff81556cc0-ffffffff81556e43: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81569000)
Location: block/blk-merge.c:1120
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff81569000-ffffffff815691bf: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81570f60)
Location: block/blk-merge.c:1123
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff81570f60-ffffffff8157111f: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d5620)
Location: block/blk-merge.c:1106
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff815d5620-ffffffff815d57df: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff816813f0)
Location: block/blk-merge.c:1095
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff816813f0-ffffffff816815be: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173e990)
Location: block/blk-merge.c:1164
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff8173e990-ffffffff8173eb5e: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8177aef0)
Location: block/blk-merge.c:1160
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff8177aef0-ffffffff8177b0c2: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bd2e0)
Location: block/blk-merge.c:1156
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff817bd2e0-ffffffff817bd4b2: blk_mq_sched_try_merge (STB_GLOBAL)
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
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffff8000105f6518)
Location: block/blk-mq-sched.c:226
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffff8000105f6518-ffff8000105f66b0: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c07a1ef0)
Location: block/blk-mq-sched.c:226
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
c07a1ef0-c07a2094: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c00000000078e8c0)
Location: block/blk-mq-sched.c:226
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
c00000000078e8c0-c00000000078ead0: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffe00043401a)
Location: block/blk-mq-sched.c:226
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffe00043401a-ffffffe000434132: blk_mq_sched_try_merge (STB_GLOBAL)
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
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814ee780)
Location: block/blk-mq-sched.c:226
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff814ee780-ffffffff814ee903: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814decd0)
Location: block/blk-mq-sched.c:226
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff814decd0-ffffffff814dee53: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814ea810)
Location: block/blk-mq-sched.c:226
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff814ea810-ffffffff814ea993: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool blk_mq_sched_try_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **merged_request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81503800)
Location: block/blk-mq-sched.c:226
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff81503800-ffffffff81503983: blk_mq_sched_try_merge (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param reordered. </b>
<code>q, bio, merged_request</code> ➡️ <code>q, bio, nr_segs, merged_request</code>
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

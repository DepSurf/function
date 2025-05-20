# Function: <code>__blk_mq_sched_bio_merge</code>

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
bool __blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81435830)
Location: block/blk-mq-sched.c:227
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81435830-ffffffff814359b6: __blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814615c0)
Location: block/blk-mq-sched.c:315
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814615c0-ffffffff81461752: __blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81494fe0)
Location: block/blk-mq-sched.c:330
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81494fe0-ffffffff814950bd: __blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814af050)
Location: block/blk-mq-sched.c:320
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814af050-ffffffff814af19b: __blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814dd310)
Location: block/blk-mq-sched.c:324
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814dd310-ffffffff814dd411: __blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814f6780)
Location: block/blk-mq-sched.c:324
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814f6780-ffffffff814f6881: __blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81557230)
Location: block/blk-mq-sched.c:389
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81557230-ffffffff81557334: __blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815738c0)
Location: block/blk-mq-sched.c:347
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff815738c0-ffffffff815739b7: __blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8157b950)
Location: block/blk-mq-sched.c:357
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff8157b950-ffffffff8157ba44: __blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815e0cb0)
Location: block/blk-mq-sched.c:366
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff815e0cb0-ffffffff815e0e39: __blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
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
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool __blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffff8000105f6d70)
Location: block/blk-mq-sched.c:324
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffff8000105f6d70-ffff8000105f6eec: __blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c07a2530)
Location: block/blk-mq-sched.c:324
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
c07a2530-c07a2650: __blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c00000000078f200)
Location: block/blk-mq-sched.c:324
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
c00000000078f200-c00000000078f3e0: __blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffe000434558)
Location: block/blk-mq-sched.c:324
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffe000434558-ffffffe000434668: __blk_mq_sched_bio_merge (STB_GLOBAL)
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
bool __blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814eed60)
Location: block/blk-mq-sched.c:324
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814eed60-ffffffff814eee61: __blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814df2a0)
Location: block/blk-mq-sched.c:324
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814df2a0-ffffffff814df3a1: __blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814eadf0)
Location: block/blk-mq-sched.c:324
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814eadf0-ffffffff814eaef1: __blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81503dd0)
Location: block/blk-mq-sched.c:324
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81503dd0-ffffffff81503ece: __blk_mq_sched_bio_merge (STB_GLOBAL)
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

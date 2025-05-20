# Function: <code>blk_mq_bio_list_merge</code>

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
bool blk_mq_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81494ad0)
Location: block/blk-mq-sched.c:274
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff81494ad0-ffffffff81494bef: blk_mq_bio_list_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool blk_mq_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814aec10)
Location: block/blk-mq-sched.c:261
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff814aec10-ffffffff814aed2f: blk_mq_bio_list_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool blk_mq_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814dcec0)
Location: block/blk-mq-sched.c:262
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff814dcec0-ffffffff814dcff0: blk_mq_bio_list_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool blk_mq_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814f6330)
Location: block/blk-mq-sched.c:262
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff814f6330-ffffffff814f6460: blk_mq_bio_list_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool blk_mq_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81556b90)
Location: block/blk-mq-sched.c:327
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff81556b90-ffffffff81556cc0: blk_mq_bio_list_merge (STB_GLOBAL)
```
</details>
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
bool blk_mq_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffff8000105f66b0)
Location: block/blk-mq-sched.c:262
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffff8000105f66b0-ffff8000105f682c: blk_mq_bio_list_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool blk_mq_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c07a2094)
Location: block/blk-mq-sched.c:262
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
c07a2094-c07a21cc: blk_mq_bio_list_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool blk_mq_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c00000000078ead0)
Location: block/blk-mq-sched.c:262
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
c00000000078ead0-c00000000078ecbc: blk_mq_bio_list_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool blk_mq_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffe000434132)
Location: block/blk-mq-sched.c:262
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffe000434132-ffffffe000434226: blk_mq_bio_list_merge (STB_GLOBAL)
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
bool blk_mq_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814ee910)
Location: block/blk-mq-sched.c:262
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff814ee910-ffffffff814eea40: blk_mq_bio_list_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool blk_mq_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814dee60)
Location: block/blk-mq-sched.c:262
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff814dee60-ffffffff814def90: blk_mq_bio_list_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool blk_mq_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814ea9a0)
Location: block/blk-mq-sched.c:262
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff814ea9a0-ffffffff814eaad0: blk_mq_bio_list_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool blk_mq_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81503990)
Location: block/blk-mq-sched.c:262
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff81503990-ffffffff81503ac0: blk_mq_bio_list_merge (STB_GLOBAL)
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

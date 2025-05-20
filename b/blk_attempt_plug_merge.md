# Function: <code>blk_attempt_plug_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int *request_count, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813bacf0)
Location: block/blk-core.c:1613
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff813bacf0-ffffffff813baddb: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int *request_count, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fea70)
Location: block/blk-core.c:1574
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff813fea70-ffffffff813feb75: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int *request_count, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81418460)
Location: block/blk-core.c:1547
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81418460-ffffffff81418565: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int *request_count, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81426460)
Location: block/blk-core.c:1674
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81426460-ffffffff8142655f: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int *request_count, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814518b0)
Location: block/blk-core.c:1794
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814518b0-ffffffff814519af: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int *request_count, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81484b20)
Location: block/blk-core.c:1891
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81484b20-ffffffff81484c24: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149faa0)
Location: block/blk-core.c:685
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff8149faa0-ffffffff8149fb95: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cdbd0)
Location: block/blk-core.c:684
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814cdbd0-ffffffff814cdce4: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e6ef0)
Location: block/blk-core.c:692
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814e6ef0-ffffffff814e7004: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81545cb0)
Location: block/blk-core.c:748
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81545cb0-ffffffff81545dc4: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81569550)
Location: block/blk-merge.c:1057
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff81569550-ffffffff8156962b: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815714c0)
Location: block/blk-merge.c:1060
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff815714c0-ffffffff8157159b: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d5b80)
Location: block/blk-merge.c:1043
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff815d5b80-ffffffff815d5c5b: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-merge.c (0)
Location: block/blk-merge.c:1038
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_attempt_bio_merge
```
**Symbols:**

```
ffffffff81e8b630-ffffffff81e8b64b: blk_attempt_plug_merge.cold (STB_LOCAL)
ffffffff81681900-ffffffff816819e7: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-merge.c (0)
Location: block/blk-merge.c:1107
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_attempt_bio_merge
```
**Symbols:**

```
ffffffff82075dde-ffffffff82075df9: blk_attempt_plug_merge.cold (STB_LOCAL)
ffffffff8173ef00-ffffffff8173efff: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-merge.c (0)
Location: block/blk-merge.c:1103
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_attempt_bio_merge
```
**Symbols:**

```
ffffffff820f5cca-ffffffff820f5ce5: blk_attempt_plug_merge.cold (STB_LOCAL)
ffffffff8177b470-ffffffff8177b569: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-merge.c (0)
Location: block/blk-merge.c:1099
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_attempt_bio_merge
```
**Symbols:**

```
ffffffff821d31ba-ffffffff821d31ef: blk_attempt_plug_merge.cold (STB_LOCAL)
ffffffff817bd860-ffffffff817bd959: blk_attempt_plug_merge (STB_GLOBAL)
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
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e4850)
Location: block/blk-core.c:692
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffff8000105e4850-ffff8000105e49a4: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0791a8c)
Location: block/blk-core.c:692
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
c0791a8c-c0791be0: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0000000007786c0)
Location: block/blk-core.c:692
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
c0000000007786c0-c0000000007788a0: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000425f6e)
Location: block/blk-core.c:692
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffe000425f6e-ffffffe00042606c: blk_attempt_plug_merge (STB_GLOBAL)
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
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814df4d0)
Location: block/blk-core.c:692
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814df4d0-ffffffff814df5e4: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cfe70)
Location: block/blk-core.c:692
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814cfe70-ffffffff814cff84: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814db560)
Location: block/blk-core.c:692
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814db560-ffffffff814db674: blk_attempt_plug_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool blk_attempt_plug_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs, struct request **same_queue_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f43d0)
Location: block/blk-core.c:692
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814f43d0-ffffffff814f44e4: blk_attempt_plug_merge (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int *request_count</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, bio, request_count, same_queue_rq</code> ➡️ <code>q, bio, same_queue_rq</code>
</li>
</ul>
</details>
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
<code>q, bio, same_queue_rq</code> ➡️ <code>q, bio, nr_segs, same_queue_rq</code>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct request **same_queue_rq</code>
</li>
</ul>
</details>
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

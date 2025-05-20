# Function: <code>blk_queue_bounce</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_bounce(struct request_queue *q, struct bio **bio_orig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff813d4f00)
Location: block/bounce.c:238
Inline: True
Direct callers:
  - block/blk-core.c:blk_make_request
  - block/blk-core.c:blk_queue_bio
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff813d4f00-ffffffff813d525c: blk_queue_bounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_bounce(struct request_queue *q, struct bio **bio_orig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff8141abb0)
Location: block/bounce.c:238
Inline: True
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff8141abb0-ffffffff8141af13: blk_queue_bounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_bounce(struct request_queue *q, struct bio **bio_orig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814360e0)
Location: block/bounce.c:238
Inline: True
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814360e0-ffffffff8143645d: blk_queue_bounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_bounce(struct request_queue *q, struct bio **bio_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff81442cf0)
Location: block/bounce.c:259
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81442cf0-ffffffff814430a0: blk_queue_bounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_bounce(struct request_queue *q, struct bio **bio_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff8146f760)
Location: block/bounce.c:262
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff8146f760-ffffffff8146fb22: blk_queue_bounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_queue_bounce(struct request_queue *q, struct bio **bio_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814a3a80)
Location: block/bounce.c:267
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814a3a80-ffffffff814a3e53: blk_queue_bounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_queue_bounce(struct request_queue *q, struct bio **bio_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814be140)
Location: block/bounce.c:355
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814be140-ffffffff814be862: blk_queue_bounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_queue_bounce(struct request_queue *q, struct bio **bio_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814ed090)
Location: block/bounce.c:360
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814ed090-ffffffff814ed0f6: blk_queue_bounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_queue_bounce(struct request_queue *q, struct bio **bio_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff815064d0)
Location: block/bounce.c:360
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff815064d0-ffffffff81506533: blk_queue_bounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_queue_bounce(struct request_queue *q, struct bio **bio_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff81566e20)
Location: block/bounce.c:362
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81566e20-ffffffff81566e81: blk_queue_bounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_queue_bounce(struct request_queue *q, struct bio **bio_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff81581c50)
Location: block/bounce.c:361
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff81581c50-ffffffff81581cb1: blk_queue_bounce (STB_GLOBAL)
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
In block/blk-mq.c (0)
Location: block/blk.h:324
Inline: True
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
In block/blk-mq.c (0)
Location: block/blk.h:330
Inline: True
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
In block/blk-mq.c (0)
Location: block/blk.h:382
Inline: True
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
In block/blk-mq.c (0)
Location: block/blk.h:387
Inline: True
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
In block/blk-mq.c (0)
Location: block/blk.h:390
Inline: True
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
In block/blk-mq.c (0)
Location: block/blk.h:388
Inline: True
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
In block/blk-map.c (0)
Location: block/blk.h:341
Inline: True
```
```
In block/blk-mq.c (0)
Location: block/blk.h:341
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_queue_bounce(struct request_queue *q, struct bio **bio_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (c07b3960)
Location: block/bounce.c:360
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
c07b3960-c07b39f8: blk_queue_bounce (STB_GLOBAL)
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
In block/blk-map.c (0)
Location: block/blk.h:341
Inline: True
```
```
In block/blk-mq.c (0)
Location: block/blk.h:341
Inline: True
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
In block/blk-map.c (0)
Location: block/blk.h:341
Inline: True
```
```
In block/blk-mq.c (0)
Location: block/blk.h:341
Inline: True
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
void blk_queue_bounce(struct request_queue *q, struct bio **bio_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814feab0)
Location: block/bounce.c:360
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814feab0-ffffffff814feb13: blk_queue_bounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_queue_bounce(struct request_queue *q, struct bio **bio_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814eefc0)
Location: block/bounce.c:360
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814eefc0-ffffffff814ef023: blk_queue_bounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_queue_bounce(struct request_queue *q, struct bio **bio_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814fab40)
Location: block/bounce.c:360
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814fab40-ffffffff814faba3: blk_queue_bounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_queue_bounce(struct request_queue *q, struct bio **bio_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff81513bf0)
Location: block/bounce.c:360
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81513bf0-ffffffff81513c53: blk_queue_bounce (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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

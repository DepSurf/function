# Function: <code>bio_attempt_back_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_back_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813baae0)
Location: block/blk-core.c:1545
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_attempt_merge
```
**Symbols:**

```
ffffffff813baae0-ffffffff813babdb: bio_attempt_back_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_back_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fe870)
Location: block/blk-core.c:1506
Inline: True
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff813fe870-ffffffff813fe964: bio_attempt_back_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_back_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81418270)
Location: block/blk-core.c:1479
Inline: True
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81418270-ffffffff81418354: bio_attempt_back_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_back_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814260d0)
Location: block/blk-core.c:1582
Inline: True
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814260d0-ffffffff814261b2: bio_attempt_back_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_back_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81451510)
Location: block/blk-core.c:1702
Inline: True
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81451510-ffffffff814515f5: bio_attempt_back_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_back_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81484780)
Location: block/blk-core.c:1799
Inline: True
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81484780-ffffffff81484867: bio_attempt_back_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_back_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149f750)
Location: block/blk-core.c:597
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8149f750-ffffffff8149f81e: bio_attempt_back_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_back_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd850)
Location: block/blk-core.c:595
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814cd850-ffffffff814cd923: bio_attempt_back_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_back_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e6b40)
Location: block/blk-core.c:599
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814e6b40-ffffffff814e6c2b: bio_attempt_back_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool bio_attempt_back_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815458d0)
Location: block/blk-core.c:651
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff815458d0-ffffffff815459c7: bio_attempt_back_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_back_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81568e20)
Location: block/blk-merge.c:933
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81568e20-ffffffff81568ee9: bio_attempt_back_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_back_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81570b50)
Location: block/blk-merge.c:936
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81570b50-ffffffff81570c19: bio_attempt_back_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_back_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d5200)
Location: block/blk-merge.c:919
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff815d5200-ffffffff815d52c6: bio_attempt_back_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_back_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81680fd0)
Location: block/blk-merge.c:916
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81680fd0-ffffffff816810bb: bio_attempt_back_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_back_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173e4e0)
Location: block/blk-merge.c:981
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8173e4e0-ffffffff8173e612: bio_attempt_back_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_back_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8177aa40)
Location: block/blk-merge.c:977
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8177aa40-ffffffff8177ab72: bio_attempt_back_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_back_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bce20)
Location: block/blk-merge.c:973
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff817bce20-ffffffff817bcf5c: bio_attempt_back_merge (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_back_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e43f8)
Location: block/blk-core.c:599
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffff8000105e43f8-ffff8000105e453c: bio_attempt_back_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_back_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0791694)
Location: block/blk-core.c:599
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
c0791694-c07917bc: bio_attempt_back_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_back_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000778150)
Location: block/blk-core.c:599
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
c000000000778150-c0000000007782d8: bio_attempt_back_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_back_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000425bfa)
Location: block/blk-core.c:599
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffe000425bfa-ffffffe000425cf4: bio_attempt_back_merge (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_back_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814df120)
Location: block/blk-core.c:599
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814df120-ffffffff814df20b: bio_attempt_back_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_back_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cfac0)
Location: block/blk-core.c:599
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814cfac0-ffffffff814cfbab: bio_attempt_back_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_back_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814db1b0)
Location: block/blk-core.c:599
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814db1b0-ffffffff814db29b: bio_attempt_back_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_back_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f3ff0)
Location: block/blk-core.c:599
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814f3ff0-ffffffff814f40f2: bio_attempt_back_merge (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>enum bio_merge_status</code>
</li>
</ul>
</details>
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

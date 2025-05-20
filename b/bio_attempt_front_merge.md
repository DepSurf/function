# Function: <code>bio_attempt_front_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_front_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813babe0)
Location: block/blk-core.c:1567
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_attempt_merge
```
**Symbols:**

```
ffffffff813babe0-ffffffff813bace9: bio_attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_front_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fe970)
Location: block/blk-core.c:1528
Inline: True
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff813fe970-ffffffff813fea6e: bio_attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_front_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81418360)
Location: block/blk-core.c:1501
Inline: True
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81418360-ffffffff81418452: bio_attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_front_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814261c0)
Location: block/blk-core.c:1604
Inline: True
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814261c0-ffffffff814262b0: bio_attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_front_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81451600)
Location: block/blk-core.c:1724
Inline: True
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81451600-ffffffff814516f3: bio_attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_front_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81484870)
Location: block/blk-core.c:1821
Inline: True
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81484870-ffffffff81484965: bio_attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_front_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149f820)
Location: block/blk-core.c:618
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8149f820-ffffffff8149f8f8: bio_attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_front_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd930)
Location: block/blk-core.c:616
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814cd930-ffffffff814cda0c: bio_attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_front_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e6c30)
Location: block/blk-core.c:621
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814e6c30-ffffffff814e6d24: bio_attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool bio_attempt_front_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815459d0)
Location: block/blk-core.c:675
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff815459d0-ffffffff81545af7: bio_attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_front_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81568ef0)
Location: block/blk-merge.c:957
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81568ef0-ffffffff81568ff1: bio_attempt_front_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_front_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81570c20)
Location: block/blk-merge.c:960
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81570c20-ffffffff81570f60: bio_attempt_front_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_front_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d52d0)
Location: block/blk-merge.c:943
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff815d52d0-ffffffff815d561a: bio_attempt_front_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_front_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff816810c0)
Location: block/blk-merge.c:940
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff816810c0-ffffffff816813ed: bio_attempt_front_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_front_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173e630)
Location: block/blk-merge.c:1007
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8173e630-ffffffff8173e97d: bio_attempt_front_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_front_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8177ab90)
Location: block/blk-merge.c:1003
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8177ab90-ffffffff8177aedd: bio_attempt_front_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_front_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bcf70)
Location: block/blk-merge.c:999
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff817bcf70-ffffffff817bd2c5: bio_attempt_front_merge (STB_LOCAL)
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
bool bio_attempt_front_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e4540)
Location: block/blk-core.c:621
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffff8000105e4540-ffff8000105e468c: bio_attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_front_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c07917bc)
Location: block/blk-core.c:621
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
c07917bc-c07918ec: bio_attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_front_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0000000007782e0)
Location: block/blk-core.c:621
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
c0000000007782e0-c000000000778468: bio_attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_front_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000425cf4)
Location: block/blk-core.c:621
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffe000425cf4-ffffffe000425df4: bio_attempt_front_merge (STB_GLOBAL)
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
bool bio_attempt_front_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814df210)
Location: block/blk-core.c:621
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814df210-ffffffff814df304: bio_attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_front_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cfbb0)
Location: block/blk-core.c:621
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814cfbb0-ffffffff814cfca4: bio_attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_front_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814db2a0)
Location: block/blk-core.c:621
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814db2a0-ffffffff814db394: bio_attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_front_merge(struct request *req, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f4100)
Location: block/blk-core.c:621
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814f4100-ffffffff814f420b: bio_attempt_front_merge (STB_GLOBAL)
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

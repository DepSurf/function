# Function: <code>bio_attempt_discard_merge</code>

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
bool bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814262b0)
Location: block/blk-core.c:1628
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff814262b0-ffffffff81426455: bio_attempt_discard_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81451700)
Location: block/blk-core.c:1748
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff81451700-ffffffff814518a5: bio_attempt_discard_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81484970)
Location: block/blk-core.c:1845
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81484970-ffffffff81484b20: bio_attempt_discard_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149f900)
Location: block/blk-core.c:641
Inline: True
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8149f900-ffffffff8149fa9d: bio_attempt_discard_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cda10)
Location: block/blk-core.c:639
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814cda10-ffffffff814cdbc2: bio_attempt_discard_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e6d30)
Location: block/blk-core.c:645
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814e6d30-ffffffff814e6ee2: bio_attempt_discard_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81545b00)
Location: block/blk-core.c:701
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81545b00-ffffffff81545caa: bio_attempt_discard_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81567710)
Location: block/blk-merge.c:983
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81567710-ffffffff81567903: bio_attempt_discard_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8156fda0)
Location: block/blk-merge.c:986
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8156fda0-ffffffff8156ff85: bio_attempt_discard_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d4440)
Location: block/blk-merge.c:969
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff815d4440-ffffffff815d4621: bio_attempt_discard_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81680290)
Location: block/blk-merge.c:966
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81680290-ffffffff81680440: bio_attempt_discard_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173d660)
Location: block/blk-merge.c:1035
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8173d660-ffffffff8173d7e9: bio_attempt_discard_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81779be0)
Location: block/blk-merge.c:1031
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81779be0-ffffffff81779d69: bio_attempt_discard_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bbfb0)
Location: block/blk-merge.c:1027
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff817bbfb0-ffffffff817bc141: bio_attempt_discard_merge (STB_LOCAL)
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
bool bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e4690)
Location: block/blk-core.c:645
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffff8000105e4690-ffff8000105e484c: bio_attempt_discard_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c07918ec)
Location: block/blk-core.c:645
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
c07918ec-c0791a8c: bio_attempt_discard_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000778470)
Location: block/blk-core.c:645
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
c000000000778470-c0000000007786c0: bio_attempt_discard_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000425df4)
Location: block/blk-core.c:645
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffe000425df4-ffffffe000425f6e: bio_attempt_discard_merge (STB_GLOBAL)
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
bool bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814df310)
Location: block/blk-core.c:645
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814df310-ffffffff814df4c2: bio_attempt_discard_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cfcb0)
Location: block/blk-core.c:645
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814cfcb0-ffffffff814cfe62: bio_attempt_discard_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814db3a0)
Location: block/blk-core.c:645
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814db3a0-ffffffff814db552: bio_attempt_discard_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool bio_attempt_discard_merge(struct request_queue *q, struct request *req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f4210)
Location: block/blk-core.c:645
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814f4210-ffffffff814f43c2: bio_attempt_discard_merge (STB_GLOBAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
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

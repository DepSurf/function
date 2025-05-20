# Function: <code>blk_try_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff813c1c70)
Location: block/blk-merge.c:778
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq.c:blk_mq_attempt_merge
```
**Symbols:**

```
ffffffff813c1c70-ffffffff813c1ca7: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81405c10)
Location: block/blk-merge.c:810
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81405c10-ffffffff81405c47: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8141feb0)
Location: block/blk-merge.c:801
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff8141feb0-ffffffff8141fee7: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8142de50)
Location: block/blk-merge.c:811
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff8142de50-ffffffff8142dea4: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81459070)
Location: block/blk-merge.c:812
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff81459070-ffffffff814590c4: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8148c5c0)
Location: block/blk-merge.c:843
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffff8148c5c0-ffffffff8148c613: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814a6180)
Location: block/blk-merge.c:886
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffff814a6180-ffffffff814a61d1: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d4070)
Location: block/blk-merge.c:833
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffff814d4070-ffffffff814d40c1: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814ed3a0)
Location: block/blk-merge.c:886
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffff814ed3a0-ffffffff814ed3f1: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8154cf30)
Location: block/blk-merge.c:887
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffff8154cf30-ffffffff8154cf81: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815691c5)
Location: block/blk-merge.c:906
Inline: True
Direct callers:
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff815694f0-ffffffff81569541: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81571125)
Location: block/blk-merge.c:909
Inline: True
Direct callers:
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff81571460-ffffffff815714b1: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d57e5)
Location: block/blk-merge.c:892
Inline: True
Direct callers:
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff815d5b20-ffffffff815d5b71: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff816815c5)
Location: block/blk-merge.c:889
Inline: True
Direct callers:
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff81681880-ffffffff816818f5: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173eb75)
Location: block/blk-merge.c:954
Inline: True
Direct callers:
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff8173ee70-ffffffff8173eee5: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8177b0e5)
Location: block/blk-merge.c:950
Inline: True
Direct callers:
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff8177b3e0-ffffffff8177b455: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bd4d5)
Location: block/blk-merge.c:946
Inline: True
Direct callers:
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff817bd7d0-ffffffff817bd845: blk_try_merge (STB_GLOBAL)
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
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffff8000105ebe50)
Location: block/blk-merge.c:886
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffff8000105ebe50-ffff8000105ebef0: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c079835c)
Location: block/blk-merge.c:886
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
c079835c-c07983e8: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c000000000781370)
Location: block/blk-merge.c:886
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
c000000000781370-c000000000781404: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffe00042bb6e)
Location: block/blk-merge.c:886
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffe00042bb6e-ffffffe00042bbee: blk_try_merge (STB_GLOBAL)
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
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e5980)
Location: block/blk-merge.c:886
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffff814e5980-ffffffff814e59d1: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d5f30)
Location: block/blk-merge.c:886
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffff814d5f30-ffffffff814d5f81: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e1a10)
Location: block/blk-merge.c:886
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffff814e1a10-ffffffff814e1a61: blk_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum elv_merge blk_try_merge(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814fa8d0)
Location: block/blk-merge.c:886
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffff814fa8d0-ffffffff814fa921: blk_try_merge (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>enum elv_merge</code>
</li>
</ul>
</details>
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
